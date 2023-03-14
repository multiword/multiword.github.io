---
title: Multiword Expressions Workshop 2023
layout: default
---

<h2>19th Workshop on Multiword Expressions (MWE 2023)</h2>

**Colocated with:** [EACL 2023](https://2023.eacl.org/) (Dubrovnik, Croatia)

**Date of the Workshop:** 6 May 2023

**Organised and sponsored by:**\
Special Interest Group on the Lexicon ([SIGLEX](http://www.siglex.org/)) of the Association for Computational Linguistics ([ACL](https://www.aclweb.org/portal/))

<a href="https://twitter.com/multiword?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-size="large" data-show-screen-name="true" data-show-count="false">@multiword</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

-----

### News

<!--
* **May 31, 2022**: Preliminary program online.
* **April 20, 2022**: LREC extended the Early-Bird Registration deadline for the main conference and workshops to May 6, 2022 (23:59 UTC+2).
* **April 12, 2022**: Paper submission deadline extended to April 17, 2022.
* **April 04, 2022**: Paper submission deadline extended to April 12, 2022.
* **March 19, 2022**: Final CFP posted.
* **March, 2022**: Invited speakers at MWE 2022: Sabine Schulte im Walde (University of Stuttgart), Steven Bird (Charles Darwin University)
* **February 21, 2022**: Second CFP posted.
* **December 21, 2021**: First CFP posted.
* **December 9, 2021**: MWE-2022 proposal accepted at LREC 2022.
-->
* **8 Feb 2023**: Paper submission deadline extended to 20 February 2023
* **2 Feb 2023**: Final CfP posted
* **19 January 2023**: Invited speaker Leo Wanner confirmed
* **16 January 2023**: Second CfP posted
* **23 December 2022**: First CfP posted
* **9 December 2022**: MWE 2023 proposal accepted to EACL 2023
* **2 November 2022**: Organising committee formed

-----

<details open markdown="block">
  <summary>
    Contents on this page
  </summary>
- [Proceedings and video recording](#proceedings-video)
- [Program](#program)
- [Keynote speakers](#keynotes) 
- [Description](#description)
- [Shared task](#shared-task)
- [Special Track on MWEs in Clinical NLP](#special-track)
- [Best paper award](#award)
- [Submission formats](#submission)
- [Paper submission and templates](#instructions)
- [Important dates](#dates)
- [Organizing Committee](#organizers)
- [Program Committee](#committee)
- [Anti-harassment policy](#antiharassment)
- [Contact](#contact)
</details>

<!-- Does not work...
* TOC
{:toc}-->

-----

### <a name="proceedings-video"> Proceedings and video recording </a>

TBD

-----

### <a name="program"> Program </a>

Tentative schedule:

| 08:30–09:00 | Registration           |
| 09:00–10:30 | Session 1              |
| 10:30–11:15 | Morning coffee break   |
| 11:15–12:45 | Session 2              |
| 12:45–14:15 | Lunch break            |
| 14:15–15:45 | Session 3              |
| 15:45–16:30 | Afternoon coffee break |
| 16:30–18:00 | Session 4              |

-----

### <a name="keynotes">Keynote speakers </a>

#### [Leo Wanner](https://www.icrea.cat/Web/ScientificStaff/leo-wanner-324), ICREA and Universitat Pompeu Fabra

**Bio:** Leo Wanner is ICREA Research Professor at the Pompeu Fabra University in Barcelona, with 230+ peer reviewed publications and 10 edited volumes. He is Associate Editor of the Computational Intelligence and Frontiers in AI, Language and Computation journals and serves as regular reviewer for a number of high-profile conferences and journals on Computational Linguistics. Throughout his career, Leo worked on a number of topics in the field, including natural language generation and summarization, concept extraction, conversational agents, hate speech recognition, and, in particular, also lexical collocation identification and classification. 

#### TBD

------

### <a name="description"> Description </a>

Multiword expressions (MWEs) are word combinations that exhibit lexical, syntactic, semantic, pragmatic, and/or statistical idiosyncrasies (Baldwin & Kim 2010), such as by and large, hot dog, pay a visit and pull one's leg. The notion encompasses closely related phenomena: idioms, compounds, light-verb constructions, phrasal verbs, rhetorical figures, collocations, institutionalised phrases, etc. Their behaviour is often unpredictable; for example, their meaning often does not result from the direct combination of the meanings of their parts. Given their irregular nature, MWEs often pose complex problems in linguistic modelling (e.g. annotation), NLP tasks (e.g. parsing), and end-user applications (e.g. natural language understanding and MT), hence still representing an open issue for computational linguistics (Constant et al. 2017).

For almost two decades, modelling and processing MWEs for NLP has been the topic of the MWE workshop organised by the [MWE section](https://multiword.org) of [SIGLEX](https://siglex.org) in conjunction with major NLP conferences since 2003. Impressive progress has been made in the field, but our understanding of MWEs still requires much research considering their need and usefulness in NLP applications. This is also relevant to domain-specific NLP pipelines that need to tackle terminologies most often realised as MWEs. Following previous years, for this 19th edition of the workshop, we identified the following topics on which contributions are particularly encouraged:

* **MWE processing and identification in specialized languages and domains:** Multiword terminology extraction from domain-specific corpora (Bonin et al. 2010) is of particular importance to various applications, such as MT (Semmar & Laib, 2017), or for the identification and monitoring of neologisms and technical jargon (Chatzitheodorou et al, 2021).  We expect approaches that deal with the processing of MWEs as well as the processing of terminology in specialised domains can benefit from each other. 
* **MWE processing to enhance end-user applications:** MWEs have gained particular attention in end-user applications, including MT (Zaninello & Birch 2020; Han et al. 2021), simplification (Kochmar et al. 2020), language learning and assessment (Paquot et al. 2019; Christiansen & Arnon 2017), social media mining (Maisto et al. 2017), and abusive language detection (Zampieri et al. 2020; Caselli et al. 2020). We believe that it is crucial to extend and deepen these first attempts to integrate and evaluate MWE technology in these and further end-user applications.
* **MWE identification and interpretation in pre-trained language models:** Most current MWE processing is limited to their identification and detection using pre-trained language models, but we still lack understanding about how MWEs are represented and dealt with therein (Nedumpozhimana & Kelleher 2021; Garcia et al. 2021, Fakharian & Cook 2021), how to better model the compositionality of MWEs from semantics (Moreau et al. 2018). Now that NLP has shifted towards end-to-end neural models like BERT, capable of solving complex tasks with little or no intermediary linguistic symbols, questions arise about the extent to which MWEs should be implicitly or explicitly modelled (Shwartz & Dagan, 2019).
* **MWE processing in low-resource languages:** The PARSEME shared tasks (Ramisch et al. 2020; 2018; Savary et al. 2017), among others, have fostered significant progress in MWE identification, providing datasets that include low-resource languages, evaluation measures, and tools that now allow fully integrating MWE identification into end-user applications. A few efforts have recently explored methods for the automatic interpretation of MWEs (Bhatia, et al. 2018; 2017), and their processing in low-resource languages (Liu & Wang 2020; Kumar et al. 2017). Resource creation and sharing should be pursued in parallel with the development of methods able to capitalize on small datasets (Han et al. 2020).

Through this workshop, we would like to bring together and encourage researchers in various NLP subfields to submit MWE-related research, so that approaches that deal with processing of MWEs including processing for low-resource languages and for various applications can benefit from each other. We also intend to consolidate the converging effects of previous joint workshops [LAW-MWE-CxG 2018](http://multiword.sourceforge.net/lawmwecxg2018/), [MWE-WN 2019](http://multiword.sourceforge.net/mwewn2019/) and [MWE-LEX 2020](http://multiword.sourceforge.net/mwelex2020/), the joint [MWE-WOAH](https://multiword.org/mwe2021/#program) panel in 2021, and the [MWE-SIGUL 2022 joint session](https://multiword.org/mwe2022/), extending our scope to MWEs in e-lexicons and WordNets, MWE annotation, as well as grammatical constructions. Correspondingly, we call for papers on research related (but not limited) to MWEs and constructions in:

* Computationally-applicable theoretical work in psycholinguistics and corpus linguistics; 
* Annotation (expert, crowdsourcing, automatic) and representation in resources such as corpora, treebanks, e-lexicons, and WordNets (also for low-resource languages); 
* Processing in syntactic and semantic frameworks (e.g. CCG, CxG, HPSG, LFG, TAG, UD, etc.); 
* Discovery and identification methods, including for specialized languages and domains such as clinical or biomedical NLP; 
* Interpretation of MWEs and understanding of text containing them; 
* Language acquisition, language learning, and non-standard language (e.g. tweets, speech); 
* Evaluation of annotation and processing techniques; 
* Retrospective comparative analyses from the PARSEME shared tasks;
* Processing for end-user applications (e.g. MT, NLU, summarisation, language learning, etc.);
* Implicit and explicit representation in pre-trained language models and end-user applications;
* Evaluation and probing of pre-trained language models; 
* Resources and tools (e.g. lexicons, identifiers) and their integration into end-user applications;
* Multiword terminology extraction;
* Adaptation and transfer of annotations and related resources to new languages and domains including low-resource ones.

-----

### <a name="shared-task">Shared task</a>

We do not have a shared task this year, but a new release of the PARSEME corpus of verbal MWEs is currently underway. We encourage submission of research papers that include analyses of the new edition of the PARSEME data and improvements over the results for PARSEME 2020 shared task as well as SemEval 2022 task 2 on idiomaticity prediction.

-----

### <a name="special-track">Special track on MWEs in clinical NLP</a>

Pursuing the MWE Section’s tradition of synergies with other communities, this year, we are organizing a joint session with the Clinical NLP workshop for shared papers/poster presentations. Since clinical texts contain an important amount of multiword expressions (e.g. medical terms or domain-specific collocations), a joint session is deemed beneficial for both communities. The goal is to foster future synergies that could address scientific challenges in the creation of resources, models and applications to deal with multiword expressions and related phenomena in the specialised domain of ClinicalNLP. Submissions describing research on MWEs in the specialized domain of ClinicalNLP, especially introducing new datasets or new tools and resources, are welcome. Papers accepted in this track will have the option to present their work in the Clinical NLP workshop at ACL 2023 as well, after being presented at MWE 2023.

-----

### <a name="award">Best paper award</a>

All full papers in the workshop will be considered by the program committee for a best paper award.

-----

### <a name="submission">Submission formats</a>

The workshop invites  two types of submissions:

* **archival submissions** that present substantially original research in both **long paper** format (8 pages + references) and **short paper** format (4 pages + references).
* **non-archival submissions** of abstracts/papers describing relevant research presented/published elsewhere (including [Findings](https://aclanthology.org/venues/findings/) papers). These will not be included in the MWE proceedings.

-----

### <a name="instructions">Paper submission and templates</a>

Papers should be submitted via [the workshop's START submission page](https://softconf.com/eacl2023/mwe2023/). Please choose the appropriate submission format (archival/non-archival). Archival papers with existing reviews will also be accepted through the ACL Rolling Review. Submissions must follow the [ACL 2023 stylesheet](https://2023.aclweb.org/calls/style_and_formatting/).

Archival papers with existing reviews from ACL Rolling Review will also be considered. A paper may not be simultaneously under review through ARR and MWE. A paper that has or will receive reviews through ARR may not be submitted for review to MWE.
To commit an ARR submission, <a href="#contact">email</a> its OpenReview forum URL (`https://openreview.net/forum?id=XXXXXXXXXXX`) to the organizers.

-----

### <a name="dates"> Important dates </a>

| What                       | When                       |
| -------------------------- | ----------------           |
| Paper submission deadline  | <s>13</s> 20 February 2023 |
| ARR commitment deadline    | 6 March 2023               |
| Notification of acceptance | <s>13</s> 15 March 2023    |
| Camera-ready papers due    | 27 March 2023              |
| Underline upload deadline  | 11 April 2023              |
| Workshop                   | 6 May 2023                 |

All deadlines are at 23:59 UTC-12 (Anywhere on Earth).

-----

### <a name="organizers"> Organizing Committee </a>

| What | Who |
| ---- | --- |
| Program chairs | [Marcos Garcia](http://www.grupolys.org/~marcos/), [Voula Giouli](https://www.ilsp.gr/en/members/giouli-voula-2/), [Shiva Taslimipoor](https://shivaat.github.io/), [Lifeng Han](https://www.research.manchester.ac.uk/portal/lifeng.han.html) |
| Publication chair | [Archna Bhatia](https://www.ihmc.us/groups/abhatia/) |
| Coordination and communication chair | [Voula Giouli](https://www.ilsp.gr/en/members/giouli-voula-2/) |
| Publicity chair | [Kilian Evang](https://kilian.evang.name/) |

-----

### <a name="committee"> Program Committee </a>

* Iñaki Alegria, University of the Basque Country
* Margarita Alonso-Ramos, Universidade da Coruña
* Tim Baldwin, University of Melbourne
* Verginica Barbu Mititelu, Romanian Academy
* Chris Biemann, Universität Hamburg
* Alexandra Birch, University of Edinburgh
* Francis Bond, Nanyang Technological University
* Claire Bonial, U.S. Army Research Laboratory
* Tiberiu Boroș, Adobe
* Jill Burstein, Educational Testing Service
* Miriam Butt , Universität Konstanz
* Marie Candito, Paris Diderot University
* Fabienne Cap, Uppsala University
* Marine Carpuat, University of Maryland
* Helena Caseli, Federal University of Sao Carlos
* Anastasia Christofidou, Academy of Athens
* Ken Church, IBM Research
* Simon Clematide, University of Zürich
* Matthieu Constant, Université de Lorraine
* Paul Cook, University of New Brunswick
* Silvio Cordeiro, Bloomin
* Monika Czerepowicka, University of Warmia and Mazury
* Béatrice Daille, Nantes University
* Myriam de Lhonneux, University of Copenhagen
* Koenraad Desmedt, University of Bergen
* Mona Diab, George Washington University
* Gaël Dias, University of Caen Basse-Normandie
* Rafael Ehren, Heinrich Heine University Düsseldorf
* Ismail El Maarouf, Adarga Ltd
* Gülşen Eryiğit, Istanbul Technical University
* Meghdad Farahmand, University of Geneva
* Christiane Fellbaum, Princeton University
* Joaquim Ferreira da Silva, New University of Lisbon
* Teresa Flera, Uni Warsaw
* Karën Fort, Sorbonne Université
* Aggeliki Fotopoulou, Institute for Language & Speech Processing, ATHENA RC
* Daniela Gierschek, Uni Luxembourg
* Stefan Th. Gries, University of California
* Bruno Guillaume, Université de Lorraine
* Dhouha Hadjmed, University of Sfax
* Chikara Hashimoto, Yahoo!Japan
* Christopher Hidey, Columbia University
* Rebecca  Hwa, University of Pittsburgh
* Uxoa Iñurrieta, University of the Basque Country
* Laura Kallmeyer, Heinrich Heine University Düsseldorf
* Diptesh Kanojia, IIT Bombay
* Elma Kerz, RWTH Aachen
* Ekaterina Kochmar, University of Cambridge
* Dimitrios Kokkinakis, University of Gothenburg
* Ioannis Korkontzelos, Edge Hill University
* Iztok Kosem, Jožef Stefan” Institute
* Cvetana Krstev, University of Belgrade
* Tita Kyriakopoulou, University Paris-Est Marne-la-Vallee
* Eric Laporte, University Paris-Est Marne-la-Vallee
* Qinyuan Li , Trinity College Dublin
* Timm Lichte, University of Tübingen
* Irina Lobzhanidze, Ilia State University
* Teresa Lynn, ADAPT Centre
* Gunn Inger Lyse Samdal, University of Bergen
* Alfredo Maldonado, Trinity College Dublin
* Stella Markantonatou, Institute for Language & Speech Processing, ATHENA RC
* Yuji Matsumoto, Nara Institute of Science and Technology
* John P. McCrae, National University of Ireland, Galway
* Nurit Melnik, The Open University of Israel
* Laura A. Michaelis, University of Colorado Boulder
* Jelena Mitrović, University of Passau
* Johanna Monti, "L'Orientale" University of Naples
* Preslav Nakov, Qatar Computing Research Institute, HBKU
* Stella Neumann, RWTH Aachen
* Sanni Nimb, Det Denske Sprog- og Litteraturselskab
* Malvina Nissim, University of Groningen
* Joakim Nivre, Uppsala University
* Diarmuid Ó Séaghdha, University of Cambridge
* Jan Odijk, University of Utrecht
* Petya Osenova , Bulgarian Academy of Sciences
* Yagmur Ozturk, Grenoble Alpes University
* Martha Palmer, University of Colorado Boulder
* Pan Pan, School of Foreign Studies, South China Normal University
* Haris Papageorgiou, Institute for Language and Speech Processing
* Yannick Parmentier, University of Lorraine
* Carla Parra Escartín, Iconic Translation Machines
* Caroline Pasquer, University of Tours
* Agnieszka Patejuk, University of Oxford and Institute of Computer Science, Polish Academy of Sciences
* Marie-Sophie Pausé, independent researcher
* Pavel Pecina, Charles University
* Ted Pedersen, University of Minnesota
* Miriam R.L Petruck , International Computer Science Institute
* Scott Piao, Lancaster University
* Maciej Piasecki, Wroclaw University of Technology
* Prisca Piccirilli, Uni. Stuttgart
* Alain Polguère, Université de Lorraine
* Vinodkumar Prabhakaran, Google
* Behrang QuasemiZadeh, University of Duesseldorf
* Alexandre Rademaker, IBM Research Brazil and EMAp/FGV
* Carlos Ramisch, Aix Marseille University
* Sonia Ramotowska, Uni Amsterdam
* Livy Real, B2W 
* Martin Riedl, University of Hamburg
* Matīss Rikters, University of Tokyo
* Victoria Rosén, University of Bergen
* Mike Rosner, University of Malta
* Fatiha Sadat, Université du Québec à Montréal
* Manfred Sailer, Goethe-Universität Frankfurt am Main
* Bahar Salehi, The University of Melbourne
* Magali Sanches Duran, University of São Paulo
* Federico Sangati, Independent researcher
* Agata Savary, Université Paris-Saclay
* Nathan Schneider, Georgetown University
* Sabine Schulte im Walde, University of Stuttgart
* Matthew  Shardlow, Manchester Metropolitan University
* Vered Shwartz, Allen AI
* Kiril Simov, Bulgarian Academy of Sciences
* Noah Smith, University of Washington
* Gyri Smørdal Losnegaard, University of Bergen
* Jan Šnajder, University of Zagreb
* Ranka Stanković, University of Belgrade
* Ivelina Stoyanova, Bulgarian Academy of Sciences
* Pavel Straňák, Charles University
* Stan Szpakowicz, University of Ottawa
* Harish Tayyar Madabushi, University of Bath
* Carole Tiberius, Dutch Language Institute
* Beata Trawinski, Institut für Deutsche Sprache Mannheim
* Yulia Tsvetkov, Carnegie Mellon University
* Zdeňka Urešová, Charles University
* Ruben Urizar, University of the Basque Country
* Ashwini Vaidya, Indian Institute of Technology
* Lonneke van der Plas, University of Malta
* Bertram Vidgen, Alan Turing Institute
* Aline Villavicencio, Federal University of Rio Grande do Sul
* Veronika Vincze, Hungarian Academy of Sciences
* Martin Volk, University of Zürich
* Zeerak Waseem, University of Sheffield
* Jakub Waszczuk, University of Duesseldorf
* Eric Wehrli, University of Geneva
* Marion Weller-Di Marco, Ludwig Maximilian University of Munich
* Seid Muhie Yimam, Universität Hamburg

-----

### <a name="antiharassment"> Anti-harassment policy </a>

The workshop follows the [ACL anti-harassment
policy](https://www.aclweb.org/adminwiki/index.php?title=Anti-Harassment_Policy).

-----

### <a name="contact"> Contact </a>

For any inquiries regarding the workshop please send an email to the Organizing
Committee at [mweworkshop2023@googlegroups.com](mailto:mweworkshop2023@googlegroups.com )

Please register to [SIGLEX](../organization/members) and check the "MWE
Section" box to be registered to our [mailing list](../mailinglist).
