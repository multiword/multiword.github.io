---
title: Joint Workshop on Multiword Expressions and Universal Dependencies (MWE-UD 2024)
layout: default
---

<h2>Joint Workshop on Multiword Expressions and Universal Dependencies (MWE-UD 2024)</h2>

**Colocated with:** [LREC-COLING 2024](https://lrec-coling-2024.org) (Torino, Italia)

**Date of the Workshop:** May 25, 2024 

**Organised and sponsored by:**\
The Special Interest Group on the Lexicon ([SIGLEX](http://www.siglex.org/)) of the Association for Computational Linguistics ([ACL](https://www.aclweb.org/portal/)), SIGLEX's Multiword Expressions Section ([SIGLEX-MWE](https://multiword.org/organization/constitution.html)), Universal Dependencies ([UD](https://universaldependencies.org)) and [UniDive](https://unidive.lisn.upsaclay.fr) Cost Action CA21167.

<a href="https://twitter.com/multiword?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-size="large" data-show-screen-name="true" data-show-count="false">@multiword</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

-----

### News

<!--
* **13 Apr 2023**: Detailed tentative schedule online
* **22 Mar 2023**: Invited speakers Asma Ben Abacha and Goran Nenadic confirmed
* **8 Feb 2023**: Paper submission deadline extended to 20 February 2023
* **2 Feb 2023**: Final CfP posted
* **19 January 2023**: Invited speaker Leo Wanner confirmed
* **16 January 2023**: Second CfP posted
* **23 December 2022**: First CfP posted
-->
* **December 8, 2023**: MWE-UD 2024 workshop date confirmed (Workshop Date: May 25, 2024)
* **November 21, 2023**: MWE-UD 2024 proposal accepted to LREC-COLING 2024
* **August 29, 2023**: Organising committee formed
  
-----

<details open markdown="block">
  <summary>
    Contents on this page
  </summary>
<!---[Proceedings and video recording](#proceedings-video)-->
<!---[Program](#program)--> 
- [Description](#description)
- [Submission Formats](#submission)
- [Paper Submission and Templates](#instructions)
- [Best Paper Award and Travel Grants](#award)
- [Important Dates](#dates)
- [Keynote Speakers](#keynotes)
- [Organizing Committee](#organizers)
- [Program Committee](#committee)
- [Sponsors and Support](#sponsors)
- [Anti-harassment Policy](#antiharassment)
- [Contact](#contact)
</details>

<!-- Does not work...
* TOC
{:toc}

-----
-->

<!--### <a name="proceedings-video"> Proceedings and video recording </a>

TBD

-----

### <a name="program"> Program </a>

TBD
-->

------

### <a name="description"> Description </a>

Multiword expressions (MWEs) are word combinations that exhibit lexical, syntactic, semantic, pragmatic, and/or statistical idiosyncrasies (Baldwin and Kim, 2010), such as by and large, hot dog, pay a visit and pull someone's leg. The notion encompasses closely related phenomena: idioms, compounds, light-verb constructions, phrasal verbs, rhetorical figures, collocations, institutionalized phrases, etc. Their behavior is often unpredictable; for example, their meaning often does not result from the direct combination of the meanings of their parts. Given their irregular nature, MWEs often pose complex problems in linguistic modeling (e.g. annotation), NLP tasks (e.g. parsing), and end-user applications (e.g. natural language understanding and MT), hence still representing an open issue for computational linguistics (Constant et al., 2017).

Universal Dependencies (UD; De Marneffe et al., 2021) is a framework for cross-linguistically consistent treebank annotation that has so far been applied to over 100 languages. The framework aims to capture similarities as well as idiosyncrasies among typologically different languages (e.g., morphologically rich languages, pro-drop languages, and languages featuring clitic doubling). The goal in developing UD was not only to support comparative evaluation and cross-lingual learning but also to facilitate multilingual natural language processing and enable comparative linguistic studies.

After independently running a successful series of workshops, the MWE and UD communities are now joining forces to organize a joint workshop. This is a timely collaboration because the two communities clearly have overlapping interests. For instance, while UD has several dependency relations that can be used to annotate MWEs, both annotation guidelines (i.e. is syntactic irregularity and inflexibility or semantic non-compositionality the leading criterion?) and annotation practice (both across treebanks for a single language and across languages) for these relations can be improved (Schneider and Zeldes, 2021). The PARSEME MWE-annotated corpora for 26 languages build on UD annotated corpora (Savary et al., 2023). Both communities share an interest in developing guidelines, data-sets, and tools that can be applied to a wide range of typologically diverse languages, raising fundamental questions about tokenization, lemmatization, and morphological decomposition of tokens. Proposals for harmonizing annotation practice between what has been achieved in PARSEME and UD and expanding PARSEME MWE annotation to non-verbal MWEs are also central to the recently started UniDive COST action (CA21167). 

The workshop invites submissions of original research on MWE, UD, and the interplay of both. In particular, the following topics are especially relevant: 
- Sensitivity of LLMs to MWE and syntactic dependencies. Studies along the lines of Manning et al. (2020) (UD), Nedumpozhimana and Kelleher (2021), Garcia et al. (2021), Fakharian and Cook (2021), Moreau et al. (2018) (MWE), and others on the question to what extent LLMs make use of syntactic dependencies or are capable of detecting MWEs and capturing their semantics. 
- Applicability of UD and MWE annotation and discovery for low-resource and typologically diverse languages and language varieties. Both UD and PARSEME aim at universal applicability across a wide range of languages. Much theoretical, computational, and empirical work concentrates on high-resource languages however. Applying these frameworks to typologically diverse languages may lead one to reconsider the notion of token, word, and morphological segmentation, and to reassess the notion of MWE for languages that feature compounding or incorporation (Baldwin et al., 2021; Haspelmath, 2023).
- Case studies.  Studies on the  consistency,  coverage or universal applicability of MWE annotation in the UD or PARSEME frameworks, as well as studies on automatic detection and interpretation of MWEs in corpora.
- MWE and UD processing to enhance end-user applications. MWEs have gained particular attention in end-user applications, including MT (Zaninello and Birch, 2020; Han et al., 2021), simplification (Kochmar et al., 2020), language learning and assessment (Paquot et al., 2019; Christiansen and Arnon, 2017), social media mining (Maisto et al., 2017), and abusive language detection (Zampieri et al., 2020; Caselli et al., 2020). We believe that it is crucial to extend and deepen these first attempts to integrate and evaluate MWE technology in these and further end-user applications.
- Testing developed systems on the latest dataset versions. Authors are also encouraged to submit papers that test the developed systems using the recent UD 2.13 and/or PARSEME 1.3 releases.

-----

<!--### <a name="shared-task">Shared task</a>

TBD

-----
-->

### <a name="submission">Submission Formats</a>

The workshop invites  two types of submissions: 
- Archival submissions that present substantially original research in both long paper format (8 pages + references) and short paper format (4 pages + references)
- Non-archival submissions of abstracts describing relevant research presented/published elsewhere which will not be included in the MWE-UD proceedings.

-----

### <a name="instructions">Paper Submission and Templates</a>

Papers should be submitted via the workshop’s START submission page (link will be provided once available). Please choose the appropriate submission format (archival/non-archival). Submissions must follow the LREC-COLING 2024 stylesheet.

When submitting a paper from the START page, authors will be asked to provide essential information about resources (in a broad sense, i.e. also technologies, standards, evaluation kits, etc.) that have been used for the research described in the paper or are a new result of the research. Moreover, ELRA encourages all LREC-COLING authors to share the described LRs (data, tools, services, etc.) to enable their reuse and replicability of experiments (including evaluation ones)

Archival papers with existing reviews from ACL Rolling Review (ARR)) will also be considered. A paper may not be under review through ARR and MWE-UD simultaneously. A paper that has or will receive reviews through ARR may not be submitted for review to MWE-UD.


-----

### <a name="award">Best Paper Award and Travel Grants</a>

- Best paper award criteria TBD
- UniDive members with accepted papers may be eligible for travel reimbursement via UniDive.
- Accepted authors from underrepresented groups (e.g., an underrepresented counry) or accepted authors of work on low-resource languages may be eligible to apply for an ACL-SIGLEX travel grant of upto 500 USD.


-----

### <a name="dates"> (Tentative) Important Dates </a>

| What                       | When                       |
| -------------------------- | -------------------------- |
| Paper submission deadline  | February 25, 2024                        |
| ARR commitment deadline    | March 25, 2024                        |
| Notification of acceptance | April 1, 2024                        |
| Camera-ready papers due    | April 8, 2024                        |
| Underline upload deadline  | TBD                        |
| Workshop                   | May 25, 2024                        |

All deadlines are at 23:59 UTC-12 (Anywhere on Earth).

-----

### <a name="keynotes">Keynote Speakers </a>

TBD

-----

### <a name="organizers"> Organizing Committee </a>
<!--
| What | Who |
| ---- | --- |
| Program chairs | TBD |
| Publication chair | TBD |
| Coordination and communication chair | TBD |
| Publicity chair | |
-->

| Who                        | Affiliation                |
| -------------------------- | -------------------------- |
| Archna Bhatia              | Institute for Human and Machine Cognition, USA |  
| Gosse Bouma                | Groningen University, NL |
| Kilian Evang               | Heinrich Heine University Düsseldorf, DE |
| Marcos Garcia              | University of Santiago de Compostela, Galiza, Spain |
| Voula Giouli               | Institute for Language & Speech Processing, ATHENA RC, Greece |  
| Lifeng Han                 | Univ. of Manchester, UK |  
| Joakim Nivre               | Uppsala University and Research Institutes of Sweden, Sweden |

-----

### <a name="committee"> Program Committee </a>

| Who                        | Affiliation                |
| -------------------------- | -------------------------- |
| Jean-Yves Antoine          | University of Tours        |
| Verginica Barbu Mititelu   | Romanian Academy           |
| Cherifa Ben Kehlil         | University of Tours        |
| Francis Bond               | Palacký University         |
| Claire Bonial              | U.S. Army Research Laboratory |
| Tiberiu Boroș              | Adobe                      |
| Miriam Butt                | Universität Konstanz       |
| Marie Candito              | Université Paris Cité      |
| Çağrı Çöltekin             | Tübingen                   |
| Paul Cook                  | University of New Brunswick |
| Monika Czerepowicka        | University of Warmia and Mazury |
| Daniel Dakota              | Indiana University         |
| Marie-Catherine de Marneffe | UCLouvain                 |
| Valeria de Paiva           | Nuannce                    | 
| Kaja Dobrovoljc            | University of Ljubljana    |
| Rafael Ehren               | Heinrich Heine University Düsseldorf |
| Christiane Fellbaum        | Princeton University       |
| Jennifer Foster            | Dublin City University     |
| Aggeliki Fotopoulou        | Institute for Language and Speech Processing, ATHENA RC |
| Stefan Th. Gries           | UC Santa Barbara & JLU Giessen | 
| Bruno Guillaume            | Université de Lorraine     |
| Tunga Gungor               | Bogaziçi University        |
| Eleonora Guzzi             | Universidade da Coruña     |
| Cvetana Krstev             | University of Belgrade     |
| Timm Lichte                | University of Tübingen     |
| Irina Lobzhanidze          | Ilia State University      |
| Teresa Lynn                | ADAPT Centre               |
| Stella Markantonatou       | Institute for Language & Speech Processing, ATHENA RC |
| John P. McCrae             | National University of Ireland, Galway |
| Nurit Melnik               | The Open University of Israel |
| Laura A. Michaelis         | University of Colorado Boulder |
| Johanna Monti              | "L'Orientale" University of Naples |
| Jan Odijk                  | University of Utrecht      |
| Petya Osenova              | Bulgarian Academy of Sciences |
| Yannick Parmentier         | University of Lorraine     |
| Agnieszka Patejuk          | University of Oxford and Institute of Computer Science, Polish Academy of Sciences |
| Pavel Pecina               | Charles University |
| Ted Pedersen               | University of Minnesota |
| Scott Piao                 | Lancaster University |
| Martin Popel               | Charles University |
| Prokopis Prokopidis        | Institute for Language and Speech Processing, ATHENA RC |
| Carlos Ramisch             | Aix Marseille University | 
| Manfred Sailer             | Goethe-Universität Frankfurt am Main |
| Tanja Samardžić            | University of Zurich |
| Agata Savary               | Université Paris-Saclay |
| Nathan Schneider           | Georgetown University |
| Sabine Schulte im Walde    | University of Stuttgart |
| Sebastian Schuster         | Saarland University |
| Maria Simi                 | Università di Pisa |
| Kiril Simov                | Bulgarian Academy of Sciences |
| Ivelina Stoyanova          | Bulgarian Academy of Sciences |
| Stan Szpakowicz            | University of Ottawa |
| Zeerak Talat               | Simon Fraser University |
| Shiva Taslimipoor          | University of Cambridge |
| Harish Tayyar Madabushi    | University of Bath |
| Beata Trawinski            | Leibniz Institute for the German Language |
| Ashwini Vaidya             | Indian Institute of Technology |
| Amir Zeldes                | Georgetown University |
| Daniel Zeman               | Charles University |
| Marion Di Marco            | Uni Muenchen |
| Matt Shardlow              | Manchester Metropolitan Uni |
| Sadat.                     | Université du Québec à Montréal |
| Pavel Stranak              | Uni Karlova |
| Pierre André               | Centre de recherche informatique de Montréal |
| Farahmand Meghdad          | Uni Geneva |
| Gaël Dias                  | University of Caen Basse-Normandie |
| Giuseppe G. A. Celano      | Leipzig Uni |
| Philippe Blache            | Aix-Marseille Uni |
| Julia R. Bonn              | Uni Colorado Boulder | 

-----

### <a name="sponsors"> Sponsors and Support </a>

![ACL SIGLEX](siglex.png){:height="15%" width="15%"}
![UniDive](unidive_logo.png){:height="12%" width="12%"}
![LREC-COLING 2024](LOGO-LREC-COLING-2024-BASIC.png){:height="25%" width="25%"}
![Cost Action](COST_LOGO_rgb_highresolution-1200x563.png){:height="25%" width="25%"}
![EU](en-funded_by_the_eu-pos.png){:height="12%" width="12%"}

-----

### <a name="antiharassment"> Anti-harassment Policy </a>

The workshop follows the [ACL anti-harassment
policy](https://www.aclweb.org/adminwiki/index.php?title=Anti-Harassment_Policy).

-----

### <a name="contact"> Contact </a>

For any inquiries regarding the workshop, please send an email to the Organizing Committee at <mweud2024-organizers@uni-duesseldorf.de>.

Please register to [SIGLEX](../organization/members) and check the "MWE
Section" box to be registered to our [mailing list](../mailinglist).

