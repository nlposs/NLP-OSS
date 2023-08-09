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
     - edit the `Additional Review Form Options` with a JSON (which I still haven't figured out how...)
