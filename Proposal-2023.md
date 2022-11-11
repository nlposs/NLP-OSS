3rd Workshop for Natural Language Processing Open Source Software (NLP-OSS)
====

With great scientific breakthrough comes solid engineering and open communities. The Natural Language Processing (NLP) community has benefited greatly from the open culture in sharing knowledge, data, and software. The primary objective of this workshop is to further the sharing of insights on the engineering and community aspects of creating, developing, and maintaining NLP open source software (OSS), which we seldom talk about in scientific publications. Our secondary goal is to promote synergies between different open source projects and encourage cross-software collaborations and comparisons.

We refer to Natural Language Processing OSS as an umbrella term that not only covers traditional syntactic, semantic, phonetic, and pragmatic applications; we extend the definition to include task-specific applications (e.g., machine translation, information retrieval, question-answering systems), low-level string processing that contains valid linguistic information (e.g. Unicode creation for new languages, language-based character set definitions) and machine learning/artificial intelligence frameworks with functionalities focusing on text applications.

There are many workshops focusing on the creation and curation of open language resources and annotations (e.g. BUCC, GWN, LAW, LOD, WAC). Moreover, we have the flagship LREC conference dedicated to linguistic resources. However, the engineering aspects of NLP-OSS are overlooked and under-discussed within the community. There are open source conferences and venues (such as FOSDEM, OSCON, Open Source Summit) where discussions range from operating system kernels to air traffic control hardware but the representation of NLP related presentations is limited. In the Machine Learning (ML) field, the Journal of Machine Learning Research - Machine Learning Open Source Software (JMLR-MLOSS) is a forum for discussions and dissemination of ML OSS topics. We envision that the Workshop for NLP-OSS becomes a similar avenue for NLP-OSS discussions.

A decade ago, there was also the SETQA-NLP (Software Engineering, Testing, and Quality Assurance for Natural Language Processing) workshop that raised awareness of the need for good software engineering practices in NLP. In the earlier days of NLP, linguistic software was often monolithic and the learning curve to install, use, and extend the tools was steep and frustrating. More often than not, NLP-OSS developers/users interact in siloed communities within the ecologies of their respective projects. In addition to engineering aspects of NLP software, the open source movement has brought a community aspect that we often overlook in building impactful NLP technologies.

More recently there have been successful workshops which examine and promote [open science](https://bigscience.huggingface.co/acl-2022) in NLP. While important and complementary, the goals of these workshops are distinct from those of NLP-OSS which focuses more on the community of practice in open-source software in support of NLP and language technologies. We expect many who participated in the BigScience workshop to participate in NLP-OSS as many of the participants are former PC members in past editions of NLP-OSS.

<!--
One example of NLP-OSS synergy is NLTK's support for Stanford NLP tools which provide a Pythonic interface to the Stanford tools written in Java. More recently, the REST-ful API from Stanford CoreNLP tools has alleviated a host of issues that are related to cross-OSS interfaces in NLTK (c.f. https://github.com/nltk/nltk/pull/1249). The developers have also interacted across their respective code repositories to raise issues and give code reviews. Beyond the diamond-sharpening effect of cross-OSS collaborations, the result of the successful interface between the tools opens the door to easily benchmark annotations created by NLTK and Stanford CoreNLP.

Another example of precious OSS knowledge comes from SpaCy developer [Montani (2017)](https://ines.io/blog/spacy-commercial-open-source-nlp), who shared her thoughts and challenges of maintaining commercial NLP-OSS, such as handling open issues on the issue tracker, model release and packaging strategy and monetizing NLP OSS for sustainability. More recently, there is also the [PyTorch Transformer](https://github.com/huggingface/pytorch-transformers) by Hugging Face, which has gathered much interest from the community by open sourcing implementations and pretrained weights of BERT-like models, in a clean and well-organized structure. The interoperability of various pretrained models trained with different tools in one library enables quick benchmarking across the models, as well as developing best practices for reading/saving serialized interoperable models. 

-->


{{Newer examples of synergy in NLP-OSS needed, see old proposals for reference https://github.com/nlposs/NLP-OSS/blob/master/nlposs-2020/Proposal-2020.md}}


The first and second NLP-OSS workshop, which was co-located with ACL 2018, was the first workshop in recent years that focused more on building quality software for NLP, open sourcing, developing useful engineering practices, and less on scientific novelty or state-of-art development. We hope that the 3rd NLP-OSS workshop could also be hosted in an *ACL conference, to be an intellectual forum to collate this type of knowledge, announce new software/features, promote the open source culture and best practices that go beyond the conferences.


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



## Demographic Diversity

**Organizers:** We have 4 organizers with representation from industrial NLP/ML labs, government organization and academic institutes.  

**PC members:** We strive to a have a balance of academic and industrial PC from diverse gender and geolocation demographics. On top of our existing PC members from NLP-OSS 2018 and 20220 editions, we've invited new PCs members by (i) recommendation of previous PC members and (ii) extending our invitation to a subset of WiNLP members on the BIG directory (we tried to contact as many as possible and in total we've sent to XXXX invitations to WiNLP members); if they have not replied and accepted the invitation, we have not listed in the PC list below. 

**Invited speakers**: Our invited speakers come from various backgrounds and have been involved with NLP open source development and may not have been that active within the ACL community. We strive to continue the tradition of inviting a diverse range of speakers to talk about NLP OSS to talk about a balance between OSS development, scientific contribution and community building around OSS. All three speakers have confirmed their participation to give an invited talk (depending on their availability after the exact conference assignment). 

 
## Misc
 
**Estimated no. of Attendees**: 50

**Shared Task**: No

**Special Requirements / Technical Needs**: No

**Preferred Venue**: 

 1. EACL / ACL / EMNLP
 2. EACL / ACL / EMNLP
 3. EACL / ACL / EMNLP


**Previous Workshop**:

  - [First Workshop for NLP-OSS at ACL 2018](https://nlposs.github.io)
    - 10 submissions, 9 accepted publications
    - 30+ attendees
    - 3 invited speakers

  - [Second Workshop for NLP-OSS at ACL 2020](https://nlposs.github.io)
    - 32 submissions, 21 accepted publications
    - 40+ attendees
    - 3 invited speakers
    
**Expected no. of submissions**: 30-40 submissions

## Organizers

 - [Geeticka Chauhan](https://www.csail.mit.edu/person/geeticka-chauhan), Massachusetts Institute of Technology
 
    Geeticka Chauhan is a Ph.D. student at MIT, working on NLP for healthcare advised by Prof. Peter Szolovits. Her master thesis focused on revealing the reproducibility and generalizability problems in Relation Extraction, and experimentally showed the importance of streamlining evaluation methods in NLP challenges

 - [Dmitrijs Milajevs](http://zest.id.lv/), Grayscale AI.

     Dmitrijs Milajevs is a data scientist at KMPG. Previously, he evaluated information retrieval systems at National Institute of Standards and Technology (NIST). He has defended a Ph.D. thesis on evaluation of compositional models in distributional semantics.

- [Elijah Rippeth](https://erip.github.io/), University of Maryland.

    Elijah Rippeth is Ph.D. student at the University of Maryland in the Department of Computer Science. His work focuses broadly on natural language processing, but with a focus on multilingual NLP, cross-lingual transfer, and machine translation. 

- Jeremy Gwinnup, Air Force Research Laboratory.

     Jeremy Gwinnup is a Research Computer Scientist in the Airman Systems Directorate of the Air Force Research Laboratory located in Dayton, Ohio USA. His research focuses on multimodal machine translation and is the topic of his studies as a Doctor of Engineering student at Johns Hopkins University.


 - [Liling Tan](https://github.com/alvations), Rakuten Institute of Technology

     Liling is a research scientist at Rakuten Institute of Technology working on Machine Translation and developing applications using language technologies. He has been actively involved in corpora creation/maintenance, Asian NLP and machine translation. He co-organized the [Workshop on NLP for Similar Languages, Varieties and Dialects (VarDial 2014-16)](http://ttg.uni-saarland.de/vardial2016/).


## Programme Committee (Confirmed from pre-proposal survey)

- Aakanksha Naik, Allen Institute for Artificial Intelligence
- Alexander Rush, Cornell, Hugging Face
- Aline   Paes, Universidade Federal Fluminense
- Arun Balajiee Lekshmi Narayanan, University of Pittsburgh
- Atnafu lambebo Tonja, Instituto Politécnico Nacional
- Atul Kr. Ojha, University of Galway
- Cassandra Jacobs, University at Buffalo
- Daniel  Braun, University of Twente
- Flammie a Pirinen, University of Norway
- Gérard Dupont, Mavenoid
- Lane Schwartz, University of Alaska Fairbanks
- Leo Boytsov, Amazon
- Lucy Park, Upstage
- Maheshwar Ghankot, Indira Gandhi National Open University
- Marco Cognetta, Tokyo Institute of Technology, Google
- Michael Wayne Goodman, LivePerson, Inc.
- Ogundepo Odunayo, University of Waterloo
- Shilpa Suresh, Harvard Medical School
- Steve DeNeefe, RWS Language Weaver
- Taha Zerrouki, Bouira University Algeria
- Thomas Kober, Zalando
- Tommaso Teofili, Roma Tre University
- Zaid Alyafeai, King Fahd University of Petroleum and Minerals
- Ziv Litmanovitz, University of Haifa
- Diana Maynard, University of Sheffield
- Marzieh Fadaee, Zeta Alpha Vector
- Mohd Sanad Zaki Rizvi, University of Edinburgh 
- Vlad Niculae, University of Amsterdam
- Aitor Soroa, HiTZ Center - Ixa, University of the Basque Country UPV/EHU
- Sagnik Ray Choudhury, University of Michigan
- Anish Mohan, Nvidia
- Jörg Tiedemann, University of Helsinki
- Tenzin Bhotia, Delhi Technological University
- Zaid Alyafeai, King Fahd University of Petroleum and Minerals


## Programme Committee (Previous PC, To follow up with)

- Abigail See
- Akiko Eriguchi
- Amandalynne Paullada
- Amittai Axelrod
- Anca Dumitrache
- Andreas Mueller
- Arwen Griffioen
- Brendan O'Connor
- Carolina Scarton
- Chris Hokamp
- Christian Federmann
- Christopher Manning
- Dan Simonson
- David Przybilla
- David M. Howcroft
- Delip Rao
- Denny Britz
- Ehsan Khoddam
- Eleftherios Avramidis
- Emiel van Miltenburg
- Emily Dinan
- Eva Maria Vecchi
- Fabio Kepler
- Francis Bond
- Frédéric Blain
- Graham Neubig
- Grzegorz Chrupała
- Hal Daumé III
- Ian Soboroff
- Ignatius Ezeani
- James Bradbury
- Jason Baldridge
- Jiatao Gu
- Joel Grus
- Joel Nothman
- Jon Dehdari
- Karin Sim Smith
- Kevin Cohen
- Kheng Hui Yeo
- Kyunghyun Cho
- Maarten van Gompel
- Madison May
- Marcel Bollmann
- Marcos Zampieri
- Marine Carpuat
- Mary Ellen Foster
- Matt Post
- Matthew Honnibal
- Micah Shlain
- Moshe Wasserblat
- Muthu Kumar Chandrasekaran
- Nelson F. Liu
- Paul Pu Liang
- Philipp Koehn
- Pontus Stenetorp
- Rachael Tatman
- Radim Rehurek
- Rico Sennrich
- Sandya Mannarswamy
- Sang Phan
- Shamil Chollampatt
- Sharat Chikkerur
- Shubhanshu Mishra
- Stephen Sloto
- Steven Bethard
- Svitlana Vakulenko
- Taku Kudo
- Tareq Al-Moslmi
- Tilahun Abedissa Taffa
- Tomas Mikolov
- Varun Kumar
- Vered Shwartz
- Yusuke Miyao
- Yves Peirsman

