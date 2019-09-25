2nd Workshop for Natural Language Processing Open Source Software (NLP-OSS)
====


With great scientific breakthrough comes solid engineering and open communities. The Natural Language Processing (NLP) community has benefited greatly from the open culture in sharing knowledge, data, and software. The primary objective of this workshop is to further the sharing of insights on the engineering and community aspects of creating, developing, and maintaining NLP open source software (OSS), which we seldom talk about in scientific publications. Our secondary goal is to promote synergies between different open source projects and encourage cross-software collaborations and comparisons.

We refer to Natural Language Processing OSS as an umbrella term that not only covers traditional syntactic, semantic, phonetic, and pragmatic applications; we extend the definition to include task-specific applications (e.g., machine translation, information retrieval, question-answering systems), low-level string processing that contains valid linguistic information (e.g. Unicode creation for new languages, language-based character set definitions) and machine learning/artificial intelligence frameworks with functionalities focusing on text applications.

There are many workshops focusing on the creation and curation of open language resources and annotations (e.g. BUCC, GWN, LAW, LOD, WAC). Moreover, we have the flagship LREC conference dedicated to linguistic resources. However, the engineering aspects of NLP-OSS are overlooked and under-discussed within the community. There are open source conferences and venues (such as FOSDEM, OSCON, Open Source Summit) where discussions range from operating system kernels to air traffic control hardware but the representation of NLP related presentations is limited. In the Machine Learning (ML) field, the Journal of Machine Learning Research - Machine Learning Open Source Software (JMLR-MLOSS) is a forum for discussions and dissemination of ML OSS topics. We envision that the Workshop for NLP-OSS becomes a similar avenue for NLP-OSS discussions.

A decade ago, there was also the SETQA-NLP (Software Engineering, Testing, and Quality Assurance for Natural Language Processing) workshop that raised awareness of the need for good software engineering practices in NLP. In the earlier days of NLP, linguistic software was often monolithic and the learning curve to install, use, and extend the tools was steep and frustrating. More often than not, NLP-OSS developers/users interact in siloed communities within the ecologies of their respective projects. In addition to engineering aspects of NLP software, the open source movement has brought a community aspect that we often overlook in building impactful NLP technologies.

One example of NLP-OSS synergy is NLTK's support for Stanford NLP tools which provide a Pythonic interface to the Stanford tools written in Java. More recently, the REST-ful API from Stanford CoreNLP tools has alleviated a host of issues that are related to cross-OSS interfaces in NLTK (c.f. https://github.com/nltk/nltk/pull/1249). The developers have also interacted across their respective code repositories to raise issues and give code reviews. Beyond the diamond-sharpening effect of cross-OSS collaborations, the result of the successful interface between the tools opens the door to easily benchmark annotations created by NLTK and Stanford CoreNLP.

Another example of precious OSS knowledge comes from SpaCy developer [Montani (2017)](https://ines.io/blog/spacy-commercial-open-source-nlp), who shared her thoughts and challenges of maintaining commercial NLP-OSS, such as handling open issues on the issue tracker, model release and packaging strategy and monetizing NLP OSS for sustainability. More recently, there is also the [PyTorch Transformer](https://github.com/huggingface/pytorch-transformers) by Hugging Face, which has gathered much interest from the community by open sourcing implementations and pretrained weights of BERT-like models, in a clean and well-organized structure. The interoperability of various pretrained models trained with different tools in one library enables quick benchmarking across the models, as well as developing best practices for reading/saving serialized interoperable models.

The first NLP-OSS workshop, which was co-located with ACL 2018, was the first workshop in recent years that focused more on building quality software for NLP, open sourcing, developing useful engineering practices, and less on scientific novelty or state-of-art development. We hope that the 2nd NLP-OSS workshop could also be hosted in an *ACL conference, to be an intellectual forum to collate this type of knowledge, announce new software/features, promote the open source culture and best practices that go beyond the conferences.


## Call for Papers

We invite full papers (8 pages) or short papers (4 pages) on topics related to NLP-OSS broadly categorized into (i) software development, (ii) scientific contribution and (iii) NLP-OSS case studies.

 - **Software Development**
   - Designing and developing NLP-OSS
   - Licensing issues in NLP-OSS
   - Backwards compatibility and stale code in NLP-OSS
   - Growing, maintaining and motivating an NLP-OSS community
   - Best practices for NLP-OSS documentation and testing
   - Contribution to NLP-OSS without coding
   - Incentivizing OSS contributions in NLP
   - Commercialization and Intellectual Property of NLP-OSS
   - Defining and managing NLP-OSS project scope
   - Issues in API design for NLP
   - NLP-OSS software interoperability
   - Analysis of the NLP-OSS community

 - **Scientific Contribution**
   - Surveying OSS for specific NLP task(s)
   - Demonstration, introductions and/or tutorial of NLP-OSS
   - Small but useful NLP-OSS
   - NLP components in ML OSS
   - Citations and references for NLP-OSS
   - OSS and experiment replicability
   - Gaps between existing NLP-OSS
   - Task-generic vs task-specific software


 - **Case studies**
   - Case studies of how a specific bug is fixed or feature is added
   - Writing wrappers for other NLP-OSS
   - Writing open-source APIs for open data
   - Teaching NLP with OSS
   - NLP-OSS in the industry

## Invited Speakers

- [Chip Huyen](https://huyenchip.com), NVIDIA
- [Spencer Kelly](https://spencermounta.in/), Freelance Developer
- [Thomas Wolf](https://thomwolf.io), Huggingface

## Demographic Diversity

**Organizers:** We have 4 organizers with representation from industrial NLP/ML labs, consultancy labs and academic research.  

**PC members:** We strive to a have a balance of academic and industrial PC from diverse gender and geolocation demographics. On top of our existing PC members from NLP-OSS 2018, we've invited new PCs members by (i) recommendation of previous PC members and (ii) extending our invitation to a subset of WiNLP members on the BIG directory (we tried to contact as many as possible and in total we've sent to ~30 invitations to WiNLP members); if they have not replied and accepted the invitation, we have not listed in the PC list below. 

**Invited speakers**: Our invited speakers come from various backgrounds and have been involved with NLP open source development and may not have been that active within the ACL community. We strive to continue the tradition of inviting a diverse range of speakers to talk about NLP OSS to talk about a balance between OSS development, scientific contribution and community building around OSS. All three speakers have confirmed their participation to give an invited talk (depending on their availability after the exact conference assignment). 

To ensure diversity and inclusivity, we have drafted a [Code of Conduct](https://github.com/nlposs/NLP-OSS/blob/master/Code-of-Conduct.md) for the NLP-OSS workshop and community and we would put up the Code of Conduct on the NLP-OSS 2020 website once we have sought advice from the ACL Professional Conduct Committee.
 
## Misc
 
**Estimated no. of Attendees**: 50

**Shared Task**: No

**Special Requirements / Technical Needs**: No

**Preferred Venue**: 

 1. ACL
 2. EMNLP 
 3. COLING
 4. AACL/IJCNLP


**Previous Workshop**:

  - [First Workshop for NLP-OSS at ACL 2018](https://nlposs.github.io)
    - 10 submissions, 9 accepted publications
    - 30+ attendees
    - 3 invited speakers
    
**Expected no. of submissions**: 15-20 submissions

## Organizers

 - [Lucy Park](https://github.com/e9t), NAVER Corp.

     Lucy is a machine learning engineer at NAVER. She has participated in some open source projects, particularly [KoNLPy](http://konlpy.org) which is a tool for Korean NLP, and is also interested in open data. She received her Ph.D. in Data Mining from Seoul National University in 2016, where she has pursued various studies on text mining in the fields of manufacturing, political science, and multimedia. After her studies, she joined NAVER, a South Korea based search-engine company, and is currently working on machine translation for Papago. Her research interests include machine translation, multilingual text mining, and evaluation of machine learning algorithms.

 - [Masato Hagiwara](http://masatohagiwara.net/), Octanove Labs LLC

     Masato Hagiwara is an independent NLP/ML engineer and researcher at Octanove Labs. He received his Ph.D. degree in Information Science from Nagoya University in 2009. During his Ph.D., he worked at Google and Microsoft Research as an intern, and thereafter at Baidu Japan and Rakuten Institute of Technology, focusing on search engine-related language processing research. Most recently he was working as a Senior Machine Learning Engineer at Duolingo, focusing on educational applications of NLP. He received several paper awards from Japanese domestic conferences for his work on knowledge acquisition and transliteration. He also co-organized several workshops and shared tasks, including NLP-OSS 2018.

 - [Dmitrijs Milajevs](http://zest.id.lv/), KPMG LLP.

     Dmitrijs Milajevs is a data scientist at KMPG. Previously, he evaluated information retrieval systems at National Institute of Standards and Technology (NIST). He has defended a Ph.D. thesis on evaluation of compositional models in distributional semantics.

 - [Nelson Liu](https://cs.stanford.edu/~nfliu/),  Stanford University.

     Nelson Liu is a computer science Ph.D. student at Stanford, where he works in the Stanford NLP Group. He has contributed to the AllenNLP, torchtext, and scikit-learn projects at various points in time.
     
 - [Geeticka Chauhan](https://www.csail.mit.edu/person/geeticka-chauhan), Massachusetts Institute of Technology
 
    Geeticka Chauhan is a Ph.D. student at MIT, working on NLP for healthcare advised by Prof. Peter Szolovits. Her master thesis focused on revealing the reproducibility and generalizability problems in Relation Extraction, and experimentally showed the importance of streamlining evaluation methods in NLP challenges


 - [Liling Tan](https://github.com/alvations), Rakuten Institute of Technology

     Liling is a research scientist at Rakuten Institute of Technology working on Machine Translation and developing applications using language technologies. He has been actively involved in corpora creation/maintenance, Asian NLP and machine translation. He co-organized the [Workshop on NLP for Similar Languages, Varieties and Dialects (VarDial 2014-16)](http://ttg.uni-saarland.de/vardial2016/).


## Programme Committee 

 - [Tareq Abdo Abdullah Al-Moslmi](https://www.uib.no/en/persons/Tareq.Abdo.Abdullah.Al-Moslmi),  University of Bergen
 - [Martin Andrews](http://mdda.net), Red Cat Labs
 - Amittai Axelrod,	DiDi Chuxing (Los Angeles)
 - Tim Baldwin, University of Melbourne
 - [Marcel Bollmann](), 
 - [Francis Bond](http://www.ntu.edu.sg/home/fcbond/), Nanyang Technological University
 - [Steven Bethard](http://bethard.faculty.arizona.edu/), University of Arizona
 - [Fred Blain](https://fredblain.org), University of Sheffield
 - James Bradbury, Salesforce Research
 - [Daniel Braun](http://wwwmatthes.in.tum.de), Technical University of Munich
 - [Denny Britz](http://blog.dennybritz.com/about/), Prediction Machines
 - [Muthu Kumar Chandrasekaran](http://wing.comp.nus.edu.sg/~cmkumar/), National University of Singapore
 - Sharat Chikkerur,	Microsoft
 - [Kyunghyun Cho](http://www.kyunghyuncho.me/), New York University
 - Shamil Chollampatt,	Rakuten Institute of Technology
 - [Jon Dehdari](http://jon.dehdari.org), Think Big Analytics
 - Steve DeNeefe,	SDL
 - [Leon Derczynski](http://www.derczynski.com/itu/), IT University of Copenhagen
 - Gérard Dupont, Airbus
 - [Ignatius Ezeani](https://www.lancaster.ac.uk/scc/about-us/people/ignatius-ezeani), Lancaster University
 - [Christian Federmann](http://www.cfedermann.de), Microsoft Research
 - [Mary Ellen Foster](http://www.dcs.gla.ac.uk/~mefoster/), University of Glasgow
 - [Michael Wayne Goodman](https://goodmami.org/), Nanyang Technological University
 - [Arwen Twinkle Griffioen](https://www.linkedin.com/in/arwengriffioen/), Zendesk Inc.
 - [Joel Grus](http://joelgrus.com/), Allen Institute for Artificial Intelligence
 - [Chris Hokamp](https://github.com/chrishokamp), AYLIEN
 - [Matthew Honnibal](https://explosion.ai), Explosion AI
 - [Sung Kim](https://www.cse.ust.hk/~hunkim/), Hong Kong University of Science and Technology
 - [Thomas Kober](https://www.inf.ed.ac.uk/people/staff/Thomas_Kober.html), University of Edinburgh
 - [Philipp Koehn](http://www.cs.jhu.edu/~phi/), Johns Hopkins University
 - [Taku Kudo](http://chasen.org/~taku/index.html.en), Google
 - Varun Kumar,	Amazon Alexa
 - [Paul Pu Liang](http://www.cs.cmu.edu/~pliang/), Carnegie Mellon University
 - [Sandya Mannarswamy](https://scholar.google.co.in/citations?user=i27nd3oAAAAJ&hl=en), Independent Researcher
 - [Christopher Manning](https://nlp.stanford.edu/manning/), Stanford University
 - Laura Martinus, Explore Data Science Academy
 - [Tomas Mikolov](https://research.fb.com/people/mikolov-tomas/), Facebook AI Research (FAIR)
 - Ehsan Khoddam Mohammadi, RELX
 - [Ines Montani](https://ines.io), Explosion AI
 - [Vlad Niculae](http://vene.ro), Instituto de Telecomunicações
 - [Joel Nothman](http://www.joelnothman.com), University of Sydney
 - Yves Peirsman, 	NLP Town
 - [Tommi A Pirinen](https://www.computing.dcu.ie/~tpirinen/),	University of Hamburg
 - [Aline Paes](https://uff.academia.edu/AlinePaes),	Universidade Federal Fluminense
 - [Matt Post](http://cs.jhu.edu/~post/),  Johns Hopkins University
 - [David Przybilla](http://alejandro.pictures), Idio
 - [Amandalynne Paullada](https://linguistics.washington.edu/people/amandalynne-paullada), University of Washington
 - [Delip Rao](http://deliprao.com), AI Foundation
 - [Radim Řehůřek](https://radimrehurek.com/), RaRe Technologies
 - [Elijah Rippeth](https://erip.github.io), MITRE Corporation
 - [Mohd Sanad Zaki Rizvi](https://www.linkedin.com/in/mohd-sanad-zaki-rizvi-0238b5a6/), Analytics Vidhya
 - [Ivan Vladimir Meza Ruiz](http://turing.iimas.unam.mx/~ivanvladimir/), National University of Mexico 
 - [Carolina Scarton](http://staffwww.dcs.shef.ac.uk/people/C.Scarton/), University of Sheffield
 - [Rico Sennrich](http://homepages.inf.ed.ac.uk/rsennric/), University of Edinburgh
 - [Dan Simonson](http://thedansimonson.com), Georgetown University
 - [Ian Soboroff](https://www.nist.gov/people/ian-soboroff), NIST
 - Shilpa Suresh, Independent Researcher
 - [Tilahun Abedissa Taffa](), Kotebe Metropolitan University
 - [Tommaso Teofili](http://people.apache.org/~tommaso/), Adobe
 - [Emiel van Miltenburg](http://www.emielvanmiltenburg.nl), Vrije Universiteit Amsterdam
 - [Svitlana Vakulenko](svakulenk0.github.io), Vienna University of Economics and Business
 - [Gaël Varoquaux](http://gael-varoquaux.info), INRIA
 - [Marcos Zampieri](http://uni-koeln.de/~mzampie2/index.html),  University of Wolverhampton
 - [Maarten van Gompel](https://proycon.anaproy.nl/), Radboud University


<!--
# Contacted, have not replied yet (2020)

Karin Sim Smith, Lingo24
Tilahun Abedissa,	Addis Ababa University
Anca Dumitrache,	FD Mediagroep
Eunsol Choi,	University of Washington
Teresa Lynn,	Dublin City University
Ana Marasović,	Computational Linguistics Department, Heidelberg University
Pamela Shapiro,	Johns Hopkins University
Abhilasha Ravichander,	Carnegie Mellon University
Natalie Schluter,	IT University of Copenhagen
Aakanksha Naik,	Carnegie Mellon University
Lucie Flekova,	Amazon Alexa AI
Ivan Vladimir, Meza Ruiz	IIMAS/UNAM
Marzieh Fadaee,	University of Amsterdam
Ebube Chuba,	IBM
Shilpa Suresh,	  
Erika Varis Doggett,	Watt Disney Studios
Jude Khouja,	Microsoft
Katarzyna Podlaska,	Samsung R&D
Chris Emmery,	Tilburg University, University of Antwerp
Kelvin Cohen,	University of Boulder, Colorado
Jade Z. Abbott,	Retro Rabbit
Laura Martinus,	Explore AI

Yoav Goldberg
Emily Bender



# Contacted hasn't replied (2018)

 - Paul Boersma (Praat)
 - Kalina Bontcheva
 - François Chollet
 - Chris Dyer
 - Ulrich Germann
 - Spence Green
 - Paul Groth
 - Kenneth Heathfield
 - Marcin Junczys-Dowmunt


# Hasn't contacted (2018)
 - Andreas Kirkedal
 - Nikolay Shmyrev (cmu-sphinx)
 - Dario Taraborelli
 - Joel Tetrault
 - Jorg Tiedemann
 - David Weenink  (Praat)
 - Torsten Zesch

# Replied but no clear answer (2018, worth recontacting)
 - Daniel Povey (Kaldi)

-->

<!--
## Workshop Structure
## Let's hide the workshop structure (for now), we'll re-publish this after the acceptance.

To promote closer interaction, all accepted publications will be presented in the poster format and be required to give a 1 slide (90 seconds) introduction of their work at the beginning of the session. For the rest of the workshop, invited talks will be given by developers and maintainers of prominent NLP-OSS projects and we plan to close the workshop with a panel session with the invited speakers and the audience of the workshop.
-->

