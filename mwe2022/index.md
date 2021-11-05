---
title: Multiword Expressions Workshop 2022
layout: default
---

<!-- * TOC
{:toc} -->

## 18th Workshop on Multiword Expressions (MWE 2022)
**Planned to be colocated with [LREC 2022](https://lrec2022.lrec-conf.org/) (Marseille, France)**

**Organised and sponsored by:**\
Special Interest Group on the Lexicon ([SIGLEX](http://www.siglex.org/)) of the Association for Computational Linguistics ([ACL](https://www.aclweb.org/portal/))

<a href="https://twitter.com/multiword?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-size="large" data-show-screen-name="true" data-show-count="false">@multiword</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

-----

### News

* **November, 2022**: MWE-2022 proposal submitted to LREC 2022.

-----

<details open markdown="block">
  <summary>
    Contents on this page
  </summary>
<!---- [Program](#program)--->
<!---- [Keynote talk](#keynote)--->
<!---- [Accepted papers](#papers)--->
- [Description](#description)
- [Submission modalities](#submission)
- [Organizers](#organizers)
- [Program committee](#committee)
- [Contact](#contact)
</details>

-----

<!---### <a name="papers"> Accepted papers </a>--->

### <a name="description"> Description </a>

Multiword expressions (MWEs) are word combinations which exhibit lexical, syntactic, semantic, pragmatic and/or statistical idiosyncrasies ([Baldwin &amp; Kim 2010](https://people.eng.unimelb.edu.au/tbaldwin/pubs/handbook2009.pdf)), such as by and large, hot dog, pay a visit and pull one's leg. The notion encompasses closely related phenomena: idioms, compounds, light-verb constructions, phrasal verbs, rhetorical figures, collocations, institutionalised phrases, etc. Their behaviour is often unpredictable; for example, their meaning often does not result from the direct combination of the meanings of their parts. Given their irregular nature, MWEs often pose complex problems in linguistic modelling (e.g. annotation), NLP tasks (e.g. parsing), and end-user applications (e.g. natural language understanding and MT), hence still representing an open issue for computational linguistics ([Constant et al. 2017](https://www.aclweb.org/anthology/J17-4005/)).

For almost two decades, modelling and processing MWEs for NLP has been the topic of the MWE workshop organised by the [MWE section](https://multiword.org/) of [SIGLEX](http://www.siglex.org/) in conjunction with major NLP conferences since 2003. Impressive progress has been made in the field, but our understanding of MWEs still requires much research considering its need and usefulness in NLP applications. For this 18th edition of the workshop, we identified three topics on which contributions are particularly encouraged:

- **MWE processing in low-resource languages:** The PARSEME shared tasks ([Ramisch et al. 2020](https://www.aclweb.org/anthology/2020.mwe-1.14/); [Ramisch et al. 2018](https://www.aclweb.org/anthology/W18-4925/); [Savary et al. 2017](https://www.aclweb.org/anthology/W17-1704/)), among others, have fostered significant progress in MWE identification, providing datasets that include low-resource languages, evaluation measures and tools that now allow fully integrating MWE identification into end-user applications. A few efforts have recently explored methods for automatic interpretation of MWEs ([Bhatia, Teng & Allen 2018](https://library.oapen.org/bitstream/handle/20.500.12657/27391/1002619.pdf?sequence=1#page=79); [Bhatia, Teng & Allen 2017](https://aclanthology.org/W17-1719.pdf)), and their processing in low-resource languages ([Liu & Wang 2020](https://ieeexplore.ieee.org/document/9310506); [Kumar et al. 2017](https://www.sciencedirect.com/science/article/pii/S1877050917314035); [Wei et al. 2015](https://ieeexplore.ieee.org/abstract/document/7451522?section=abstract)). Resource creation and sharing should be pursued in parallel to the development of methods able to capitalize on small datasets.
- **MWE identification and interpretation in pre-trained language models:** Most current MWE processing is limited to their identification and detection using pre-trained language models, but we lack understanding about how MWEs are represented and dealt with therein ([Nedumpozhimana & Kelleher 2021](https://aclanthology.org/2021.mwe-1.7.pdf); [Garcia et al. 2021](https://aclanthology.org/2021.eacl-main.310.pdf), [Fakharian & Cook 2021](https://aclanthology.org/2021.mwe-1.4/)). Now that NLP has shifted towards end-to-end neural models like BERT, capable of solving complex end-user tasks with little or no intermediary linguistic symbols, questions arise about the extent to which MWEs should be implicitly or explicitly modelled in such models.
- **MWE processing to enhance end-user applications:** As underlined by the MWE 2021 call for papers, MWEs gained particular attention in end-user applications, including MT ([Zaninello &amp; Birch 2020](https://www.aclweb.org/anthology/2020.lrec-1.471/)), simplification ([Kochmar et al. 2020](https://www.aclweb.org/anthology/2020.lrec-1.545/), [Liu &amp; Hwa 2016](https://www.aclweb.org/anthology/N16-1040/)), language learning and assessment ([Paquot et al. 2019](https://dial.uclouvain.be/pr/boreal/object/boreal:226339), [Christiansen &amp; Arnon 2017](https://doi.org/10.1111/tops.12274)), social media mining ([Maisto et al. 2017](https://doi.org/10.4000/books.aaccademia.2441)), and abusive language detection ([Zampieri et al. 2020](https://www.aclweb.org/anthology/2020.semeval-1.188/), [Caselli et al. 2020](https://www.aclweb.org/anthology/2020.lrec-1.760/)). We believe that it is crucial to extend and deepen these first attempts to integrate and evaluate MWE technology in these and further end-user applications.

Therefore, we would like to bring together and encourage researchers in various NLP subfields to submit MWE-related research, so that approaches that deal with processing of MWEs including processing for low-resource languages and for various applications can benefit from each other. We also intend to consolidate the converging effects of previous joint workshops [LAW-MWE-CxG 2018](http://multiword.sourceforge.net/lawmwecxg2018/), [MWE-WN 2019](http://multiword.sourceforge.net/mwewn2019/) and [MWE-LEX 2020](http://multiword.sourceforge.net/mwelex2020/), and the [joint MWE-WOAH panel in 2021](https://multiword.org/mwe2021/#program), extending our scope to MWEs in e-lexicons and WordNets, MWE annotation, as well as grammatical constructions. Correspondingly, we will call for papers on research related (but not limited) to MWEs and constructions in:
- Computationally-applicable theoretical work in psycholinguistics and corpus linguistics
- Annotation and representation in resources such as corpora, treebanks, e-lexicons, and WordNets
- Processing in syntactic and semantic frameworks (e.g. CCG, CxG, HPSG, LFG, TAG, UD, etc.)
- Discovery and identification methods
- Interpretation of MWEs and understanding of text containing them
- Language acquisition, language learning, and non-standard language (e.g. tweets, speech)
- Evaluation of annotation and processing techniques
- Retrospective comparative analyses from the PARSEME shared tasks
- Processing for end-user applications (e.g. MT, NLU, summarisation, language learning, etc.)
- Implicit and explicit representation in pre-trained language models and end-user applications
- Evaluation and probing of pre-trained language models and end-user applications
- Resources and tools (e.g. lexicons, identifiers) and their integration into end-user applications
- Theoretical and computational linguistic description and modelling in low-resource languages
- Annotation guidelines and methods in low-resource languages (expert, crowdsourcing, automatic)
- Adaptation and transfer of annotations and related resources to low-resource languages
- Processing in low-resource languages (supervised, semi-supervised, and unsupervised methods for identification, discovery, and interpretation)
- Evaluation of annotations and processing techniques for low-resource languages
- Processing for end-user applications in low-resource languages

##### Joint session with SIGUL 2022 Workshop

The MWE Section would like to pursue its efforts in building bridges with other communities. We intend to organise a joint session with the workshop of the [Special Interest Group on Under-resourced Languages](http://www.elra.info/en/sig/sigul/), SIGUL 2022, which proposal was also submitted to be co-located with LREC 2022. The goal is to foster future synergies that could address scientific challenges in the creation of resources, models and applications to deal with multiword expressions and related phenomena in low-resource scenarios, in accordance with one of our special topics in MWE 2022.  The session format is currently under discussion. This would require some overlap between the schedules of both workshops, implying synchronisation as to whether both of them take place before or after LREC 2022.

-----

### <a name="submission"> Submission modalities </a>
The workshop will invite two types of submissions:
- **Archival submissions** present substantially original research. Submissions will follow the [LREC stylesheet](https://lrec2022.lrec-conf.org/en/submission2022/authors-kit/). They can be **long papers** (8 content pages + references) or **short papers** (4 content pages + references). One **extra page** will be granted for the final versions. The decisions as to **oral or poster presentations** will be taken by the PC chairs, with no distinction in the proceedings. Submission will be **double-blind**.
- **Non-archival submissions** of abstracts will also be considered for presentation, but not included in the proceedings. Abstracts will go through a light reviewing process.

-----

### <a name="organizers"> Organizers </a>

- **Program chairs:** [Archna Bhatia](https://www.ihmc.us/groups/abhatia/),
[Paul Cook](http://cs.unb.ca/~ccook1/), and [Shiva Taslimipoor](https://shivaat.github.io/)
- **Publication chairs:** [Marcos Garcia](http://www.grupolys.org/~marcos/)
- **Communication chair:** [Carlos Ramisch](https://pageperso.lis-lab.fr/carlos.ramisch/)

-----

### <a name="committee"> Program committee </a>

<details markdown="block">
  <summary>
    See the full list
  </summary>

  - Tim Baldwin, University of Melbourne (Australia)
  - Verginica Barbu Mititelu, Romanian Academy (Romania)
  - Francis Bond, Nanyang Technological University (Singapore)
  - Claire Bonial, U.S. Army Research Laboratory (USA)
  - Tiberiu Boroș, Adobe (Romania)
  - Marie Candito, Paris Diderot University (France)
  - Anastasia Christofidou, Academy of Athens (Greece)
  - Ken Church, IBM Research (USA)
  - Matthieu Constant, Université de Lorraine (France)
  - Monika Czerepowicka, University of Warmia and Mazury (Poland)
  - Myriam de Lhonneux, University of Copenhagen (Denmark)
  - Gaël Dias, University of Caen Basse-Normandie (France)
  - Gülşen Eryiğit, Istanbul Technical University (Turkey)
  - Meghdad Farahmand, University of Geneva (Switzerland)
  - Christiane Fellbaum, Princeton University (USA)
  - Joaquim Ferreira da Silva, New University of Lisbon (Portugal)
  - Aggeliki Fotopoulou, ILSP/RC "Athena" (Greece)
  - Voula Giouli, Institute for Language and Speech Processing (Greece)
  - Stefan Th. Gries, University of California (USA)
  - Uxoa Iñurrieta, University of the Basque Country (Spain)
  - Diptesh Kanojia, IIT Bombay (India)
  - Ioannis Korkontzelos, Edge Hill University (UK)
  - Cvetana Krstev, University of Belgrade (Serbia)
  - Eric Laporte, University Paris-Est Marne-la-Vallee (France)
  - Timm Lichte, University of Duesseldorf (Germany)
  - Irina Lobzhanidze, Ilia State University (Georgia)
  - Teresa Lynn, ADAPT Centre (Ireland)
  - Gunn Inger Lyse Samdal, University of Bergen (Norway)
  - Stella Markantonatou, Institute for Language and Speech Processing (Greece)
  - Yuji Matsumoto, Nara Institute of Science and Technology (Japan)
  - Jan Odijk, University of Utrecht (Netherlands)
  - Haris Papageorgiou, Institute for Language and Speech Processing (Greece)
  - Yannick Parmentier, Université d'Orléans (France)
  - Pavel Pecina, Charles University (Czech Republic)
  - Ted Pedersen, University of Minnesota (USA)
  - Scott Piao, Lancaster University (UK)
  - Alain Polguère, Université de Lorraine (France); Livy Real, B2W (Brazil)
  - Fatiha Sadat, Université du Québec à Montréal (Canada)
  - Magali Sanches Duran, University of São Paulo (Brazil)
  - Sabine Schulte im Walde, University of Stuttgart (Germany)
  - Matthew Shardlow, Manchester Metropolitan University (UK)
  - Ivelina Stoyanova, Bulgarian Academy of Sciences (Bulgaria)
  - Pavel Straňák, Charles University (Czech Republic)
  - Stan Szpakowicz, University of Ottawa (Canada)
  - Carole Tiberius, Dutch Language Institute (Netherlands)
  - Beata Trawinski, Institut für Deutsche Sprache Mannheim (Germany)
  - Zdeňka Urešová, Charles University (Czech Republic)
  - Ruben Urizar, University of the Basque Country (Spain)
  - Lonneke van der Plas, University of Malta (Malta)
  - Veronika Vincze, Hungarian Academy of Sciences (Hungary)
  - Martin Volk, University of Zürich (Switzerland)
  - Zeerak Waseem, University of Sheffield (UK)
  - Marion Weller-Di Marco, Ludwig Maximilian University of Munich (Germany)
  - Jelena Mitrović, University of Passau (Germany)
  - Petya Osenova , Bulgarian Academy of Sciences (Bulgaria)
  - Ashwini Vaidya, Indian Institute of Technology (India).
</details>

-----

### <a name="contact"> Contact </a>

For any inquiries regarding the workshop please send an email to [mweworkshop2022@gmail.com ](mweworkshop2022@gmail.com )

Please register to [SIGLEX](../organization/members) and check the "MWE Section" box to be registered to our [mailing list](../mailinglist).
