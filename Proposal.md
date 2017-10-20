Workshop for Natural Language Processing Open Source Software (NLP-OSS)
====


With great scientific breakthrough comes solid engineering and open communities. The Natural Language Processing (NLP) community has benefited greatly from the open culture in sharing knowledge, data, and software. The primary objective of this workshop is to further the sharing of insights on the engineering and community aspects of creating, developing, and maintaining NLP open source software (OSS) which we seldom talk about in scientific publications. Our secondary goal is to promote synergies between different open source projects and encourage cross-software collaborations and comparisons.

We refer to Natural Language Processing OSS as an umbrella term that not only covers traditional syntactic, semantic, phonetic, and pragmatic applications; we extend the definition to include
task-specific applications (e.g., machine translation, information retrieval, question-answering systems),
low-level string processing that contains valid linguistic information (e.g. unicode creation for new languages, language-based character set definitions) and
machine learning / artificial intelligence frameworks with functionalities focusing on text applications.

There are many workshops focusing open language resource/annotation creation and curation (e.g. BUCC, WAC, LOD, GWN, LAW). Moreover, we have the flagship LREC conference dedicated to linguistic resources. However, the engineering aspects of NLP OSS is overlooked and under-discussed within the community. 

There are open source conferences and venues (such as OSCON, Open Source Summit, FOSDEM) where discussion ranges from operating system kernels to air traffic control hardware but the representation of NLP related presentation are limited. In the Machine Learning (ML) field, the Journal of Machine Learning Research - Machine Learning Open Source Software (JMLR-MLOSS)  is a forum for discussions and dissemination of ML OSS topics. We envision that the Workshop for NLP-OSS becomes a similar avenue for NLP OSS discussion.

To our best knowledge, this is the first workshop proposal in the recent years that focuses more on the building aspect of NLP and lesser so on scientific novelty or state-of-art development. A decade ago, there was the SETQA-NLP (Software Engineering, Testing, and Quality Assurance for Natural Language Processing) workshop that raised awareness of the need for good software engineering practices in NLP. In the earlier days of NLP, linguistic software was often monolithic and the learning curve to install, use, and extend the tools was steep and frustrating. More often than not, NLP OSS developers/users interact in silos communities within the ecologies of their respective projects. In addition to engineering aspects of NLP software, the open source movement has brought a community aspect that we forget in building impactful NLP technologies  

With the advent of cross programming-language support for NLP and high-level languages like Python, R, Ruby, and Julia, we are starting to see the synergies between cross-community support across NLP OSS. 

One classic example is NLTK’s support for Stanford NLP tools which provides a Pythonic interface to the Stanford tools written in Java. More recently, the REST-ful API from Stanford CoreNLP tools has alleviated a host of issues that are related to cross OSS interfaces in NLTK. The developers have also interacted across their respective code repositories to raise issues and give code reviews (c.f. https://github.com/nltk/nltk/pull/1249 ). Beyond the diamond sharpening effect of cross-OSS collaborations, the result of the successful interface between the tools opens door to easily benchmark annotations created by NLTK and Stanford CoreNLP. 

Another example of precious OSS knowledge comes from SpaCy developer, where Montani (2017, https://ines.io/blog/spacy-commercial-open-source-nlp) shared her thoughts and challenges of maintaining commerical NLP OSS, such as handling open issues on the issue tracker, model release and packaging strategy and monetizing NLP OSS for sustainability.

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

To promote closer interaction, all accepted publications will be presented in the poster format and be required to give a 1 slide (90 seconds) introduction of their work at the beginning of the session. For the rest of the workshop, invited talks will be given by developers and maintainers of prominent NLP OSS projects and we plan to close the workshop with a panel session with the invited speakers and the audience of the workshop.

## Expected Crowd Size:

50


## Organizers

 - [Lucy Park](https://github.com/e9t), NAVER Corp.
     
     Lucy is a research scientist at NAVER. During her Ph.D. studies at Seoul National University, she investigated better representations for text, and started several open source projects such as [KoNLPy](http://konlpy.org). Her current research area is machine translation -- focused on user log analysis and multilingual NMT.
     
 - [Masato Hagiwara](http://masatohagiwara.net/), Duolingo Inc.

     Masato Hagiwara is a research scientist / software engineer working at Duolingo. He received his Ph.D. degree in Information Science from Nagoya University in 2009. During his Ph.D., he worked at Google and Microsoft Research as an intern, and thereafter at Baidu Japan, focusing on search engine-related language processing research. Before joining Duolingo, he was a lead scientist at Rakuten Institute of Technology in New York. His research interests include Japanese and Chinese language processing, machine translation / transliteration, and language education. He received several paper awards from Japanese domestic conferences for his work on knowledge acquisition and transliteration. He also co-organized a couple of workshops and special sessions in Japan on noisy text processing.

 - [Dmitrijs Milajevs](http://www.eecs.qmul.ac.uk/~dm303/), NIST and Queen Mary University of London. dimazest@gmail.com
 
     Dmitrijs is a guest researcher at National Institute of Standards and Technology (NIST) working on the evaluation of information retrieval systems. He has just defended a PhD thesis on evaluation of compositional models in distributional semantics. He was responsible for a website for the [11th International Conference on Computational Semantics (IWCS 2015)](http://iwcs2015.github.io/) and a collocated hackathon.
 
 - [Liling Tan](https://github.com/alvations), Rakuten Institute of Technology
     
     Liling is a research scientist at Rakuten Institute of Technology working on Machine Translation and developing applications using language technologies. He has been actively involved in corpora creation/maintenance, Asian NLP and machine translation. He co-organized the [Workshop on NLP for Similar Languages, Varieties and Dialects (VarDial 2014-16)](http://ttg.uni-saarland.de/vardial2016/) and the DSL shared task. 


## Invited Speakers (Confirmed, depends on availability of speakers after conference assignment)

- [Christopher Manning](https://nlp.stanford.edu/manning/), Stanford University
- [Matthew Honnibal and Ines Montani](https://explosion.ai), Explosion AI
- [Joel Nothman](http://joelnothman.com), University of Sydney


## Programme Committee (Hopeful list)

 - [Martin Andrews](http://mdda.net), Red Cat Labs
 - [Francis Bond](http://www.ntu.edu.sg/home/fcbond/), Nanyang Technological University
 - [Jason Baldridge](http://www.jasonbaldridge.com/), Google 
 - [Steven Bethard](http://bethard.faculty.arizona.edu/), University of Arizona
 - [Fred Blain](https://fredblain.org), University of Sheffield
 - Steven Bird
 - James Bradbury, Salesforce Research
 - [Denny Britz](http://blog.dennybritz.com/about/), Prediction Machines
 - [Marine Carpuat](http://www.cs.umd.edu/~marine/), University of Maryland
 - [Kyunghyun Cho](http://www.kyunghyuncho.me/), New York University
 - [Grzegorz Chrupała](http://grzegorz.chrupala.me/), Tilburg University
 - [Mary Ellen Foster](http://www.dcs.gla.ac.uk/~mefoster/), University of Glasgow
 - [Hal Daumé III](https://www.umiacs.umd.edu/~hal/), University of Maryland 
 - [Jon Dehdari](http://jon.dehdari.org), Think Big Analytics
 - [Christian Federmann](http://www.cfedermann.de), Microsoft Research
 - [Joel Grus](http://joelgrus.com/), Allen Institute for Articial Intelligence
 - [Chris Hokamp](https://github.com/chrishokamp), Aylien Inc.
 - [Matthew Honnibal](https://explosion.ai), Explosion AI
 - [Sung Kim](https://www.cse.ust.hk/~hunkim/), Hong Kong University of Science and Technology
 - [Philipp Koehn](http://www.cs.jhu.edu/~phi/), Johns Hopkins University
 - [Taku Kudo](http://chasen.org/~taku/index.html.en), Google
 - [Christopher Manning](https://nlp.stanford.edu/manning/), Stanford University
 - [Diana Maynard](http://www.dcs.shef.ac.uk/~diana/), University of Sheffield
 - [Tomas Mikolov](https://research.fb.com/people/mikolov-tomas/), Facebook AI Research (FAIR)
 - [Ines Montani](https://ines.io), Explosion AI
 - [Andreas Müller](http://amueller.github.io), Columbia University
 - [Graham Neubig](http://www.phontron.com/), Carnegie Mellon University
 - [Vlad Niculae](http://vene.ro), Cornell CIS
 - [Joel Nothman](http://www.joelnothman.com), University of Sydney
 - [Matt Post](http://cs.jhu.edu/~post/),  Johns Hopkins University
 - [David Przybilla](http://alejandro.pictures), Idio
 - [Delip Rao](http://deliprao.com), Joostware AI Research Corp
 - [Radim Řehůřek](https://radimrehurek.com/), RaRe Technologies
 - [Elijah Rippeth](https://erip.github.io), MITRE Corporation
 - [Abigail See](http://cs.stanford.edu/people/abisee/), Stanford University
 - [Rico Sennrich](http://homepages.inf.ed.ac.uk/rsennric/), University of Edinburgh 
 - [Dan Simonson](http://thedansimonson.com), Georgetown University
 - Nathan Schneider
 - [Vered Shwartz](http://u.cs.biu.ac.il/~havivv/), Bar-Ilan University
 - [Pontus Stenetorp](http://pontus.stenetorp.se), University College London
 - [Rachael Tatman](http://rachaeltatman.com), Kaggle
 - [Emiel van Miltenburg](http://www.emielvanmiltenburg.nl), Vrije Universiteit Amsterdam
 - [Gaël Varoquaux](http://gael-varoquaux.info), INRIA
 - [Marcos Zampieri](http://uni-koeln.de/~mzampie2/index.html),  University of Wolverhampton


<!--
Verbal Endorsements
====

Exclude to avoid conflict of interest

 - Tim Baldwin (COLING workshop chair) https://twitter.com/eltimster/status/904928371603320832
 - Yoav Goldberg (COLING workshop co-chair)
 - Emily Bender (COLING PC co-chair) https://twitter.com/emilymbender/status/904870675722027008
 - Leon Derczynski (COLING PC co-chair)

-->

<!--
Contacted hasn't replied

 - Paul Boersma (Praat)
 - Kalina Bontcheva
 - François Chollet
 - Chris Dyer
 - Ulrich Germann
 - Spence Green
 - Paul Groth
 - Carolina Scarton
 - Kenneth Heathfield
 - Marcin Junczys-Dowmunt 
 

# Liling will try contacting
 - Dan Flickinger
 - Michael Wayne Goodman
 - Maarten van Gompel
 - João Graça
 - Josef van Genabith
 
 
# Hasn't contacted
 - Andreas Kirkedal
 - Nikolay Shmyrev (cmu-sphinx)
 - Dario Taraborelli
 - Joel Tetrault
 - Jorg Tiedemann
 - David Weenink  (Praat)
 - Torsten Zesch
 
# Replied but no clear answer (worth recontacting)

 - Daniel Povey (Kaldi)
-->
