Adding Reviewers to Pool
====

From https://openreview.net/group/edit?id=EMNLP/2023/Workshop/NLP-OSS/Reviewers, somehow I only found a way of manually copy+pasting the list from our PC usernames to comma-separated format then clicking `Add to Group` in batches. Unlike softconf, there's no way to add a csv or a one line per user file to the system.

Then after adding the reviewers there, we can start using the `Select All` and `Message Selected` in the same https://openreview.net/group/edit?id=EMNLP/2023/Workshop/NLP-OSS/Reviewers to communicate with the PC. 


I can't figure out how to formally invite them as described on:

 - https://docs.openreview.net/getting-started/hosting-a-venue-on-openreview/navigating-your-venue-pages
 - https://docs.openreview.net/how-to-guides/managing-groups/how-to-recruit-and-remind-recruited-reviewers

Whenever I go to https://openreview.net/group/edit?id=EMNLP/2023/Workshop/NLP-OSS/Reviewers/Invited page, it just throws an error:

> Error 404
> The server responded with the following message:
> Group Not Found: EMNLP/2023/Workshop/NLP-OSS/Reviewers/Invited
> If you'd like to report this error to the developers, please use the Feedback form.


Most probably the right way to do it is from https://openreview.net/group?id=EMNLP/2023/Workshop/NLP-OSS/Program_Chairs#venue-configuration and then click on `Full Venue Configuration` then click on `Recruitment`, then the PC invitation form will appear for "New Recruitment"


----

Modify Review Form
====

This is supposedly the official docs https://docs.openreview.net/reference/default-forms/default-review-form

To access the review, first, we start from 

 - from https://openreview.net/group?id=EMNLP/2023/Workshop/NLP-OSS/Program_Chairs#venue-configuration
 - click on `Full Venue Configuration`, 
 - then after it gets to the conference/workshop configuration page, click on `Review Stage`
 - which will open up the "New Review Stage" page, on there,
     - set the `Review Start Date` to the conference/workshop paper submission deadline
     - set the `Review Deadline` for the official review deadline from the program committee
     - set the `Review Expiration Date` (usually 1-2 days before the notification of the acceptance/rejection results)
     - change the `Review Rating Field Name`
     - change the `Review Confidence Field Name`
     - edit the `Additional Review Form Options` with a JSON, currently using:

```
{
	"review": {
		"value": {
			"param": {
				"type": "string",
				"minLength": 1,
				"maxLength": 20000,
				"input": "textarea",
				"markdown": true
			}
		},
		"order": 1,
		"description": "What is this paper about and what contributions does it make? Please describe what problem or question this paper addresses, and the main contributions that it makes towards a solution or answer. The following kinds of contributions listed on our CFP are all welcomed https://nlposs.github.io/2023/index.html#call-for-papers"
	},
	"appropriateness": {
		"value": {
			"param": {
				"type": "string",
				"enum": [
					"5: Certainly",
					"4: Probably",
					"3: Unsure",
					"2: Probably not",
					"1: Certainly not"
				],
				"input": "radio"
			}
		},
		"description": "Does this paper fit in the NLP-OSS workshop? Most papers should be in the 'certainly' 5 category. We accept various contributions ranging from empirical results, system demonstrations, case studies and theoretical / position discussions results are welcome.",
		"order": 2
	},
	"clarity": {
		"value": {
			"param": {
				"type": "string",
				"enum": [
					"5: Very clear",
					"4: Understandable by most readers",
					"3: Mostly understandable to me with some effort",
					"2: Important questions were hard to resolve even with effort",
					"1: Much of the paper is confusing"
				],
				"input": "radio"
			}

		},
		"description": "Is the discussion/experiments/tool was clearly described in the paper? For the reasonably well-prepared reader, is it clear what was done and why? Is the paper well-written and well-structured?",
		"order": 3
	},
	"soundness": {
		"value": {
			"param": {
				"type": "string",
				"enum": [
					"5: Excellent: This study is one of the most thorough I have seen, given its type.",
					"4: Strong: This study provides sufficient support for all of its claims/arguments. ",
					"3: Good: This study provides sufficient support for its major claims/arguments, some minor points may need extra support or details.",
					"2: Borderline: Some of the main claims/arguments are not sufficiently supported, there are major technical/methodological problems",
					"1: Poor: This study is not yet sufficiently thorough to warrant publication or is not relevant to NLP-OSS."
				],
				"input": "radio"
			}

		},
		"description": "How sound and thorough is this study? First, is the technical approach sound and well-chosen? Second, can one trust the claims of the paper -- are they supported by proper experiments, proofs, or other argumentation?",
		"order": 4
	},
	"recommendation": {
		"value": {
			"param": {
				"type": "string",
				"enum": [
					"5: Exciting: I'd fight to get it accepted",
					"4: Worthy: I would like to see it accepted",
					"3: Borderline: I'm ambivalent about this one",
					"2: Mediocre: I'd rather not see it in the conference",
					"1: Poor: I'd fight to have it rejected"
				],
				"input": "radio"
			}
		},
		"description": "Should the paper be accepted or rejected? There are many good submissions competing for slots at this event; how important is it to feature this one? Will people learn a lot by reading this paper or seeing it presented? In deciding on your ultimate recommendation, please think over all your scores above. But remember that no paper is perfect, and remember that we want a conference full of interesting, diverse, and timely work. If a paper has some weaknesses, but you really got a lot out of it, feel free to fight for it. If a paper is solid but you could live without it, let us know that you're ambivalent. Remember also that the author has a couple of weeks to address reviewer comments before the camera-ready deadline. ",
		"order": 5
	},
	"open_source": {
		"value": {
			"param": {
				"type": "string",
				"enum": [
					"Yes: Work done is open sourced or discussion describing open source related issues",
					"No: Work done is mainly describing unknown licensed tools / not free nor open software",
					"Unclear: Work done has not specified whether the tools demonstrated or described is open source"
				],
				"input": "radio"
			}

		},
		"description": "We want to make sure that NLP-OSS remains a venue to discuss open source tools and related issues. If the paper (i) has described experiments, features or issues that is explicitly non-open or not free source without any comparison to open source counter parts, or (ii) has described or demonstrated a tool with unclear licensing, please flag them out in your answer. We want to discourage (i) submissions and re-direct them to other appropriate venues and hopefully shepherd (ii) authors towards a clear licensing decision.",
		"order": 6
	},
	"confidence": {
		"value": {
			"param": {
				"type": "string",
				"enum": [
					"5: Positive that my evaluation is correct. I read the paper very carefully and I am very familiar with related work.",
					"4: Quite sure. I tried to check the important points carefully. It's unlikely, though conceivable, that I missed something that should affect my ratings.",
					"3: Pretty sure, but there's a chance I missed something. Although I have a good feel for this area in general, I did not carefully check the paper's details, e.g., the math, experimental design, or novelty.",
					"2: Willing to defend my evaluation, but it is fairly likely that I missed some details, didn't understand some central points, or can't be sure about the novelty of the work.",
					"1: Not my area, or paper was hard for me to understand. My evaluation is just an educated guess."
				],
				"input": "radio"
			}

		},
		"description": "How confident are you in your assessment of this paper?",
		"order": 7
	}
}
```


----

Assigning papers to Reviewers
====

From https://openreview.net/group?id=EMNLP/2023/Workshop/NLP-OSS/Program_Chairs#venue-configuration, there's a "Reviewers Paper Assignment" link but whenever I clicked on it, it just throws the error:

> Error 404
> The server responded with the following message:
> There is currently no assignment configuration ready for use. Please go to your venue request form and use the Paper Matching Setup to compute conflicts and/or affinity scores.

After some figuring out, the paper matching setup failed the first time but the second time the button never re-appeared. 

And the reviews won't start on the system until the submission deadline closes. A work-around it is after the official deadline, change the time of the end of submission to yesterday. Then click on the review assignment on 

 - https://openreview.net/group?id=EMNLP/2023/Workshop/NLP-OSS/Program_Chairs#venue-configuration
 - then click on "Reviewers Paper Assignment"
 - then the assignment system appears,
 - then go back to https://openreview.net/group?id=EMNLP/2023/Workshop/NLP-OSS/Program_Chairs#venue-configuration
 - click on "full venue configuration", then in the configuration page, click on "Revision"
 - change the time back to extended deadline
