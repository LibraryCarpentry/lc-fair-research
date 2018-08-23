---
title: "Introduction"
teaching: 0
exercises: 0
questions:
- "Key question"
objectives:
- "First objective."
keypoints:
- "First key point."
---

## Goals of this lesson:

- To teach FAIRer research data and software management and development practices
- Focus on practical approaches to being FAIRer admitting that there are no “silver bullets”

## What is FAIR?

In 2016, the [FAIR Guiding Principles for scientific data management and stewardship](https://www.nature.com/articles/sdata201618) were published in Scientific Data. In the paper, the authors provide general guidance on machine-actionability and improvements that can be made to streamline findability, accessibility, interoperatbility, and reuability (or FAIR) of digital assets. Research is increasingly dependent on computational support and yet there are still many bottlenecks in the process. The overall aim of FAIR is to cut down on the inefficient processes in research by taking advantage of linked resources and the exchange of data so that all stakeholders in the research ecosystem, , can automate repetitive, boring, error-prone tasks.

## FAIR, FAIRer, FAIRest

In 2017, 2nd paper:
FAIR: not a standard
Different approaches
About data FAIRness for machines (and humans): 
Partly FAIR may be FAIR enough

"as open as possible, as closed as necessary"

## Different stages of FAIR
Mons et al. 2017, 6 categories:
Re-useless data
Findable (PID)
FAIR metadata
(PID + machine readable MD)
FAIR data – restricted access
FAIR data – open access
FAIR data /
open access & functionally linked 
= ‚Internet of FAIR data and services‘

doi:10.3233/ISU-170824 

## Guide to the Principles and Sub-Principles

TIB Hannover has provided the following FAIR guide with examples:
[TIB Hannover FAIR Principles Guide](https://blogs.tib.eu/wp/tib/2017/09/12/the-fair-data-principles-for-research-data)

## FAIR involves all stakeholders 

When considering FAIR, a researcher should consider different stakeholders… 1st and foremost other researchers, but that is not enough… increasingly funding bodies, institutions, publishers and infrastructure providers demand (and in the case of infrastructures try  to offer) FAIR data and software (services) … a DMP can help to cover all aspects
E.g. in mission-oriented research, industrial stakeholders have to be considered. A good DMP should include all (possible) stakeholders…. commercerial partners, publishers (data availability policy), researchers, front office, back office (data centers - information and awareness, training, storage), Institution/Organization (RDM Policy, repositories, facilities), Research funders Source: OpenAIRE Research Data Management Briefing paper: www.openaire.eu/briefpaper-rdm-infonoads, CC BY 


Barriers and strategies 

Barrier: Most research data is not accessible
Strategy: Incentivise data sharing and publication  

Barrier: Standardized metadata or documentation are not available
Strategy: Mandatory metadata required for persistent identifier registration  

Barrier: No consistent practice of citing and referencing data
Strategy: Providing citation standard DataCite Metadata Schema 4.1  

Barrier: Researchers are unwilling or unable to share data 
Strategy: Inform researchers about benefits and possibilities

Use barriers and strategies to possibly address how the various stakeholders are working to help the community?

- Funders: list an example
- Researchers: 
- Librarians: 
- Publishers: 
- Systems Providers: 

* Group exercise to find other ways they may help the system?

## Library services across the research lifecycle

Libraries actively help researchers navigate the requirements, demands, and tools that make up the research data management landscape, particularly when it comes to the organization, preservation, and sharing of research data and software. They play a vital role in directly supporting the academic enterprise by promoting data sharing and reproducibility. Through their research training and services, particularly for early career researchers and graduate students, libraries are driving a cultural shift towards effective data and software stewardship. As a trusted partner, and with an embedded understanding of their communities, libraries foster collaboration and facilitate coordination between community stakeholders and are a critical part of the discussion. 

![The integrated scientific life cycle of embedded networked sensor research.](../fig/pepe_research_lifecycle.png)

Pepe, A., Mayernik, M., Borgman, C.L. and Van de Sompel, H., 2010. [From artifacts to aggregations: Modeling scientific life cycles on the semantic web.](https://arxiv.org/abs/0906.2549?context=cs) Journal of the American Society for Information Science and Technology, 61(3), pp.567-582. arXiv: https://arxiv.org/abs/0906.2549?context=cs.

## Good data stewardship starts early

Ultimately, the FAIR principles will lead to more rigorous management and stewardship of digital assets. Stakeholders from across the research lifcycle can apply the principles at different points to the benefit of the greater community. FAIR should also be considered from the very beginning of a research project, and by applying the principles early in the process, the benefits can be further realized and create a virtuous cycle. 

From the start, there are a number of requirements and conditions that should be addressed:

- Funding agency requirements
- Trustworthy research data repositories
- Agency and instutitional data policies
- Standards for data citation, metadata, licensing
- Privacy, intellectual property rights, and copyright
- Methods and tools adapted to the scientific workflows
- Cost recovery strategies
- Motivation for FAIR approach

## Funding agecies and DMPs
Funding bodies that require Data Management Plans (DMPs) European Commission, NSF, NERC Science of the Environment, Academy of Finland, Bill & Melinda Gates, NIH, Cancer Research UK, Genome Canada, NRF National Research Foundation, MRC Medical Research Council, Netherlands ORation fo Scientific Research NWO (add screenshot of one example page/policy)

## Data Management Plans or DMPs 
https://en.wikipedia.org/wiki/Data_management_plan
addresses issues related to data management
might be required by funding bodies (NSF, EU H2020)
is a (formal) document developed at the start of a research project which outlines all aspects of data created/used
must be updated throughout the course of research
DMP, analogue to a project plan, is a living document - researchers should check them once in a while during the project(s) & DMP tools should offer the possibility to update regularly
Research data management means to organize, store, preserve and possibly share data from the beginning of a project (or from proposal writing) until the data is archived/published.
This requires persons, tools, services, etc.   
Data Management Plan (DMP) as an instrument for curating data 
Common checklist (all DMPs): 
Administrative Information
Data Collection
Documentation and metadata
Ethics and Legal Compliance
Storage and Backup
Selection and Preservation
Data Sharing
Responsibilities and Resources

Exercise using these tools?
- https://dmptool.org/
- https://dmponline.dcc.ac.uk/

DMP samples:
LIBER Data Management Plan Catalogue
https://libereurope.eu/dmpcatalogue/

Active DMPs on the horizon...
Roadmap: github.com/DMPRoadmap/roadmap/wiki/Local-installations-inventory  


## FAIR for Software?
doi:10.12688/f1000research.11407.1
Peter Doorn (2017) Does it make sense to apply the FAIR Data Principles to Software? (Software Sustainability Workshop)
software quality guidelines existed for decades 
in military, industry, academia & FLOSS
ISO 9000-3, 9126-1, 25010:2011
GNU Coding Standards & Quality Code
ECSS Software Product Assurance 
CLARIAH software quality guidelines

## Software Management Plan
The Software Sustainability Institute. (2016). Checklist for a Software Management Plan. v0.1. Available online: software.ac.uk/software-management-plans
SSI’s checklist: not just a list of questions, but a document generator tool
overlap with general FLOSS advice: OpenSource.guide/starting-a-project  & /best-practices   
be pragmatic about SMP’s format: use funder template
include SMP in DMPOnline.DCC.ac.uk
if not required: Maybe frame your Git(Hub/Lab)
issue tracker as a “living, public plan”?


## FAIR Data Action Plan
https://github.com/FAIR-Data-EG/Action-Plan 


## What does “FAIR” mean for your domain of study / research / work or field of expertise?

Group exercise
3 large groups: count 1-2-3….
or per table?
Could also include to tell us about existing / non-existing local/institutional policies, DMPs, SMPs, ELNs, plans for implementing FAIR, repositories in use, persons acting as data curators… 
HackMD collaborative notes from groups
