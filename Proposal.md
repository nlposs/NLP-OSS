Workshop for Natural Language Processing Open Source Software (NLP-OSS)
====


With great scientific breakthrough comes solid engineering. The Natural Language Processing (NLP) community has benefited greatly from the open culture in sharing knowledge, data, and software. The primary objective of this workshop is to further the sharing of insights on the engineering and community aspects of creating, developing, and maintaining NLP open source software (OSS) which we seldom talk about in scientific publications. Our secondary goal is to promote synergies between different open source projects and encourage cross-software collaborations and comparisons.

We refer to Natural Language Processing OSS as an umbrella term that not only covers traditional syntactic, semantic, phonetic, and pragmatic applications; we extend the definition to include
task-specific applications (e.g., machine translation, information retrieval, question-answering systems),
low-level string processing that contains valid linguistic information (e.g. unicode creation for new languages, language-based character set definitions) and
machine learning / artificial intelligence frameworks with functionalities focusing on text applications.

There are many workshops focusing open language resource/annotation creation and curation (e.g. BUCC, WAC, LOD, GWN, LAW). Moreover, we have the flagship LREC conference dedicated to linguistic resources. However, the engineering aspects of NLP OSS is overlooked and under-discussed within the community. To our best knowledge, this is the first workshop proposal that focuses more on the building aspect of NLP and lesser so on scientific novelty or state-of-art development.

More often than not, NLP OSS developers/users interact in silos communities within the ecologies of their respective projects. In the earlier days of NLP, linguistic software was often monolithic and the learning curve to install, use, and extend the tools was steep and frustrating.

With the advent of cross programming-language support for NLP and high-level languages like Python, R, Ruby, and Julia, we are starting to see the synergies between cross-community support across NLP OSS.

One classic example is NLTK’s support for Stanford NLP tools which provides a Pythonic interface to the Stanford tools written in Java. More recently, the REST-ful API from Stanford CoreNLP tools has alleviated a host of issues that are related to cross OSS interfaces in NLTK. The developers have also interacted across their respective code repositories to raise issues and give code reviews (c.f. https://github.com/nltk/nltk/pull/1249 ).  Beyond the diamond sharpening effect of cross-OSS collaborations, the result of the successful interface between the tools opens door to easily benchmark annotations created by NLTK and Stanford CoreNLP.

Another example of precious OSS knowledge comes from SpaCy developer, where Montani (2017, https://ines.io/blog/spacy-commercial-open-source-nlp) shared her thoughts and challenges of commercial NLP OSS.  

We hope that our NLP-OSS workshop becomes the intellectual forum to collate this type of knowledge, announce new software/features, promote the open source culture and best practices that go beyond the conferences.


## Call for Papers

We invite topics related to NLP-OSS under broadly categorized into (i) software development, (ii) scientific contribution (iii) NLP-OSS case studies.

 - **Software Development**
   - Designing and developing NLP OSS
   - Licensing issues in NLP OSS
   - Backwards compatibility and stale code in NLP OSS
   - Growing an NLP OSS community
   - Maintaining and motivating NLP OSS community
   - Best practices for NLP OSS documentations and tests
   - Contribution to OSS without coding
   - Incentivizing OSS contributions in NLP

 - **Scientific Contribution**
   - Benchmarking OSS for specific NLP task(s)
   - Demonstration and tutorial of NLP OSS
   - New NLP OSS introductions
   - Small but useful NLP OSS
   - Machine learning vs NLP OSS
   - Citations and references for NLP OSS
   - OSS vs experiment replicability
   - Gaps between existing NLP OSS
   - Task independent NLP OSS


 - **Case studies**
   - Case studies of how a specific bug is fixed or feature is added
   - Writing wrappers for other NLP OSS
   - Writing open-source APIs for open data
   - Teaching NLP with OSS
   - Avoiding the hammer OSS


## Workshop Structure

To promote closer interaction, all accepted publications will be presented in the poster format and be required to give a 1 slide (90 seconds?) introduction of their work at the beginning of the session. For the rest of the workshop, invited talks will be given by developers and maintainers of prominent NLP OSS projects and we plan to close the workshop with a panel session with the invited speakers and the audience of the workshop.

## Expected Crowd Size:

50-ish?


## Organizers

 - [Lucy Park](https://github.com/e9t), NAVER Corp.
 
     Lucy is a research scientist at NAVER. During her Ph.D. studies at Seoul National University, she investigated better representations for text, and started several open source projects such as KoNLPy. Her current research area is machine translation -- focused on user log analysis and multilingual NMT.
     
 - [Masato Hagiwara](http://masatohagiwara.net/), Duolingo Inc.
 - [Dmitrijs Milajevs](http://www.eecs.qmul.ac.uk/~dm303/), NIST and Queen Mary University of London
 - [Liling Tan](https://github.com/alvations), Rakuten Institute of Technology


## Invited Speakers (Confirmed)

- [Christopher Manning](https://nlp.stanford.edu/manning/), Stanford University
- [Matthew Honnibal and Ines Montani](https://explosion.ai), Explosion AI


## Programme Committee (Hopeful list)

 - [Martin Andrews](http://mdda.net), Red Cat Labs
 - Francis Bond
 - Jason Baldridge
 - [Fred Blain](https://fredblain.org), University of Sheffield
 - Steven Bird
 - Paul Boersma (Praat)
 - James Bradbury, Salesforce Research
 - [Denny Britz](http://blog.dennybritz.com/about/), Prediction Machines
 - Marine Carpuat
 - Kyunghyun Cho
 - François Chollet
 - Grzegorz Chrupała
 - Dan Flickinger
 - Hal Daumé III
 - [Jon Dehdari](http://jon.dehdari.org), Think Big Analytics
 - Chris Dyer
 - [Christian Federmann](http://www.cfedermann.de), Microsoft Research 
 - Ulrich Germann
 - João Graça
 - Spence Green
 - Paul Groth
 - Joel Grus
 - Kenneth Heathfield
 - Hieu Hoang
 - Chris Hokamp
 - [Matthew Honnibal](https://explosion.ai), Explosion AI
 - Marcin Junczys-Dowmunt
 - David Jurgen
 - [Sung Kim](https://www.cse.ust.hk/~hunkim/), Hong Kong University of Science and Technology
 - Andreas Kirkedal
 - Philipp Koehn
 - [Christopher Manning](https://nlp.stanford.edu/manning/), Stanford University
 - Tomas Mikolov
 - [Ines Montani](https://ines.io), Explosion AI
 - [Andreas Müller](http://amueller.github.io), Columbia University 
 - [Graham Neubig](http://www.phontron.com/), Carnegie Mellon University
 - [Vlad Niculae](http://vene.ro), Cornell CIS
 - [Joel Nothman](http://www.joelnothman.com), University of Sydney
 - Daniel Povey (Kaldi)
 - Matt Post
 - [David Przybilla](http://alejandro.pictures), Idio
 - [Delip Rao](http://deliprao.com), Joostware AI Research Corp
 - [Radim Řehůřek](https://radimrehurek.com/), RaRe Technologies
 - [Elijah Rippeth](https://erip.github.io), MITRE Corporation
 - Rico Sennrich
 - [Dan Simonson](http://thedansimonson.com), Georgetown University
 - Nathan Schneider
 - Nikolay Shmyrev (cmu-sphinx)
 - [Vered Shwartz](http://u.cs.biu.ac.il/~havivv/), Bar-Ilan University
 - Pontus Stenetorp (BRAT)
 - Dario Taraborelli
 - Rachael Tatman
 - Joel Tetrault
 - Jorg Tiedemann
 - Josef van Genabith
 - Maarten van Gompel
 - [Emiel van Miltenburg](http://www.emielvanmiltenburg.nl), Vrije Universiteit Amsterdam
 - Gaël Varoquaux
 - David Weenink  (Praat)
 - [Marcos Zampieri](http://uni-koeln.de/~mzampie2/index.html),  University of Wolverhampton
 - Torsten Zesch


<!--
Verbal Endorsements
====

Exclude to avoid conflict of interest

 - Tim Baldwin (COLING workshop chair) https://twitter.com/eltimster/status/904928371603320832
 - Yoav Goldberg (COLING workshop co-chair)
 - Emily Bender (COLING PC co-chair) https://twitter.com/emilymbender/status/904870675722027008
 - Leon Derczynski (COLING PC co-chair)

-->
