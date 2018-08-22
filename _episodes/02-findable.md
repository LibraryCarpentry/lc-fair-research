---
title: "Findable"
teaching: 0
exercises: 0
questions:
- "Key question"
objectives:
- "First objective."
keypoints:
- "First key point."
---

> ## For data & software to be findable:  
> F1. (meta)data are assigned a globally unique and eternally persistent identifier or PID  
> F2. data are described with rich metadata  
> F3. (meta)data are registered or indexed in a searchable resource  
> F4. metadata specify the data identifier  
{: .checklist}

Your institution’s/repository’s role:  
- Assign a globally unique PID upon publication (or draft upload) 
- Provide metadata schema in human- & machine-readable format (PID, author names, subject areas, etc)
- Support structured input of metadata (submission forms or XML schema)
- Index (meta)data to enable effective searching
- Allow metadata upload & assign corresponding PID

Your role as a researcher:  
- Check datasets that you use for PIDs & cite them
- Ensure that your datasets get published with PIDs
- Choose repositories that automate PID registration
- Report this requirement to repositories that don’t assign PIDs
- Add rich metadata (describe the dataset’s context, quality, condition & characteristics)
- Should be understandable by researchers from different disciplines (ask a friend to proofread)

## PIDs in the wild

To start, we can have a look at the following paper which includes a note regarding the availability of the supporting data and link (in the form of a digital object identifier or DOI) to the reference:  

include img of paper screenshot...  

Paper:  
Koen Kole, Rik G.H. Lindeboom, Marijke P.A. Baltissen, Pascal W.T.C. Jansen, Michiel Vermeulen, Paul Tiesinga, Tansu Celikel (2017):
Proteomic landscape of the primary somatosensory cortex upon sensory deprivation, GigaScience, Volume 6, Issue 10, 1 October 2017, Pages 1–10. DOI https://doi.org/10.1093/gigascience/gix082

Quiz  
Do you see the note?  
Can you think about other aspects of the paper that can benefit from PIDs?  


Note in the paper:
“Availability of the supporting data
Data supporting this work are available in the GigaScience repository, GigaDB [14]. The raw mass spectrometry proteomics data have been deposited in the ProteomeXchange Consortium via the PRIDE partner repository [15] with the dataset identifier PXD005971”

Reference:
[14] Kole K, Baltissen M, Lindeboom R et al.   Supporting data for “Proteomic landscape of the primary somatosensory cortex upon sensory deprivation.” GigaScience Database  2017. http://doi.org/10.5524/100336 

A PID is
Provenance
Metadata
Policies & Guarantees 
Machine readability
Metrics

## PID 101 for Researchers (or: Resolving some PID myths)
A PID is a „long lasting reference to a digital resource“
There are different sorts of PIDs & different uses,(e.g. for articles, data, persons, organizations, …)
PIDs are offered by organizations - Ask your institute/library
You do NOT have to pay for PIDs (by yourself)!
PIDs are mostly used for (persistent) citation – All published resources should have one
A correct citation always includes a PID → look in your citation manager
Metadata behind a PID are most important – please take care when providing them
PIDs are not perfect (they are issued by organizations, aka humans!)
PIDs are really useful & fun – they make yourself & your work more visible! 


## Anatomy of a PID  
Digital object identifiers or DOIs are a common PID that used in the scholarly ecosystem. DataCite and CrossRef are notable non-profit organizations that operate DOI minting registries. 

International DOI Foundation (IDF) manages DOI-System 

Proxy
Prefix
Suffix

Metadata Store and DOI Fabrica

DataCite e.V. maintains and operates the infrastructure for DOI registration

![Anatomy of a DOI](../fig/anatomy-of-a-doi.jpg) 

Persistent and unique identifier for objects in the digital environment
DOIs refer to the objects not the location → remain valid 
DOIs are minted for research data, software and code, physical objects, grey literature  
DOI-System is an internationally recognised and supported standard

PIDs provide interoperable Metadata
→ Automatic ORCID profile update when DOI is minted

## Connecting research outputs
DOIs are everywhere. Examples.

Resource IDs (articles, data, software, …)
Researcher IDs
Organisation IDs, Funder IDs
Projects IDs
Instrument IDs
Ship cruises IDs
Physical sample IDs,
DMP IDs…
videos 
images 
3D models 
grey literature

![Connecting Research Outputs](../fig/datacite-arxiv-crossref.png)

https://support.datacite.org/docs/connecting-research-outputs

Bullet points about the current state of linking...
https://blog.datacite.org/citation-analysis-scholix-rda/


## Provenance?
Provenance means validation & credibility – a researcher should comply to good scientific practices and be sure about what should get a PID (and what not).
Metadata is central to visibility and citability – metadata behind a PID should be provided with consideration.
Policies behind a PID system ensure persistence in the WWW - point. At least metadata will be available for a long time.
Machine readability will be an essential part of future discoverability – resources should be checked and formats should be adjusted (as far possible).
Metrics (e.g. altmetrics) are supported by PID systems.

## Rich Metadata
https://schema.datacite.org/

## PID should be required, etc

## Publishing behaviour of researchers 

According to:

Technische Informationsbibliothek (TIB) (conducted by engage AG) (2017): Questionnaire and Dataset of the TIB Survey 2017 on information procurment and pubishing behaviour of researchers in the natural sciences and engineering. Technische Informationsbibliothek (TIB). DOI: [https://doi.org/10.22000/54](https://doi.org/10.22000/54)

- responses from 1400 scientists in the natural sciences & engineering (across Germany)
- 70% of the researchers are using DOIs for journal publications
- less than 10% use DOIs for research data
-- 56% answered that they don’t know about the option to use DOIs for other publications (datasets, conference papers etc.) 
-- 57% stated no need for DOI counselling services
-- 40% of the questioned researchers need more information
-- 30% cannot see a benefit from a DOI

## Choosing the right repository

Ask your colleagues & collaborators
Look for institutional repository at your own institution

determining the right repo for your reseearch
data are kept safe in a secure environment
data are regularly backed up and preserved (long-term) for future use
data can be easily discovered by search engines and included in online catalogues
intellectual property rights and licencing of data are managed 
access to data can be administered and usage monitored
the visibility of data can be enhanced
enables more use and citation
citation of data increases researchers scientific reputation
Decision for or against a specific repository depends on various criteria, e.g.
Data quality 
Discipline
Institutional requirements
Reputation (researcher and/or repository)
Visibility of research
Legal terms and conditions
Data value (FAIR Principles)
Exit strategy (tested?)
Certificate (based only on documents?)

Some recommendations:
→ look for the usage of PIDs
→ look for the usage of standards (DataCite, Dublin Core, discipline-specific metadata
→ look for licences offered
→ look for certifications (DSA / Core Trust Seal, DINI/nestor, WDS, …)

Searching re3data w/ exercise
https://www.re3data.org/
Out of more than 2115 repository systems listed in re3data.org in July 2018, only 809 (less than 39 %!) state to provide a PID service, with 524 of them using the DOI system

Search open access repos
http://v2.sherpa.ac.uk/opendoar/

FAIRSharing
https://fairsharing.org/databases/

## Data Journals

Another method available to researchers to cite and give credit to research data is to author works in data journals or supplemental approaches used by publishers, societies, disciplines, and/or journals. 

Articles in data journals allow authors to:
- Describe their research data (including information about process, qualities, etc)
- Explain how the data can be reused
- Improve discoverability (through citation/linking mechanisms and indexing)
- Provide information on data deposit
- Allow for further (peer) review and quality assurance
- Offer the opportunity for further recognition and awards

Examples:
- [Nature Scientific data](https://www.nature.com/sdata/) - published by Nature and established in 2013
- [Geoscience Data Journal](https://rmets.onlinelibrary.wiley.com/journal/20496060) - published by Wiley and established in 2012
- [Journal of Open Archaeology Data](https://openarchaeologydata.metajnl.com/) - published by Ubiquity and established in 2011
- [Biodiversity Data Journal](https://bdj.pensoft.net/) - published by Pensoft and established in 2013.
- [Earth System Science Data](https://www.earth-system-science-data.net/) - published by Copernicus Publications and established in 2009

Also, the following study discusses data journals in depth and reviews over 100 data journals:
Candela, L. , Castelli, D. , Manghi, P. and Tani, A. (2015), Data Journals: A Survey. J Assn Inf Sci Tec, 66: 1747-1762. doi:[10.1002/asi.23358](https://doi.org/10.1002/asi.23358)

> ## How does your discipline share data
>
> Does your discipline have a data journal? Or some other mechanism to share data? For example, the American Astronomical Society (AAS) via the publisher IOP Physics offers a [supplment series](http://iopscience.iop.org/journal/0067-0049/page/article-data) as a way for astronomers to publish data. 
{: .discussion}


List recent publications re: benefits of data sharing / software sharing

Questions:
Is FAIRSharing vs re3data comparison slide from TIB findability slides needed here?
Should we include recent thread about handle system vs DOIs in IRs (costs)
Zenodo-GitHub linking is listed in another episode, right?
Include guidance for Google schema indexing...

Notes:  
Note about authors being proactive and working with the journals/societies to improve papers referencing data, software...
