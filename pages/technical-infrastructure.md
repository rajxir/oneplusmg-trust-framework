---
title: 'Technical Infrastructure'
description: Introduction to Technical Infrastructure
---


## Infrastructure Vision

### [B1MG Secure cross-border data access roadmap v2.0](https://zenodo.org/record/5018526#.YXGlNNbMKdY): June 2021 <span class="badge badge-primary">Informational<i class="fa-sharp fa-solid fa-circle-info"></i></span>

A  roadmap presented here is to define the timelines to provide a proof of concept demonstrator of secure cross border data access, describe the technologies required to develop such a demonstrator, and to detail the work that has gone into determining the roadmap and requirement for the proof of concept demonstrator. The roadmap also outlines how it is expected that the work carried out towards the initial proof of concept will support the developing roadmap for 2022 and beyond, as the proof of concept evolves from a demonstrator with synthetic data to a production system accessing real genetic and phenotypic data.

### [B1MG Secure Access Demonstrator](https://zenodo.org/record/7590822) <span class="badge badge-dark">Recommended<i class="fa-solid fa-thumbs-up"></i></span>

The 1+MG data infrastructure needs to be defined to ensure data managed within the federated network are compliant with the European and national legislation on data protection, security, and ELSI principles agreed in 1+MG. At the same time the aim is to maximise the Findability, Accessibility, Interoperability and Reusability of the 1+MG data, according to FAIR principles. 

In this deliverable a Proof of Concept (PoC) was built using existing standards, applications, and services to demonstrate cross border data access for two 1+MG use cases; rare disease and cancer. The intention is to create a technical infrastructure baseline and advancement for the next iteration of implementation data protection principles according to the GDPR

## Infrastructure Components

The 1+MG technical infrastructure is broken down into five functionalities as defined in the 2021 paper titled, [“Towards a Proof of Concept of Federated Infrastructure for the EU 1+ Million Genome Initiative”](https://zenodo.org/record/6089583).  This includes: Data Discovery, Data Reception, Storage and Interfaces, Data Access Management, and Processing.  These functionalities were originally defined as follows:

### <a href="{{'/data-discovery' | relative_url}}">Data Discovery</a>
Data discoverability Provides the public visibility to the combined 1+MG dataset by making selected descriptive metadata searchable. Data discovery service will collect summary level (but not sensitive) descriptions of all data available from the signatory states. It will link directly to Data Access Management where users can apply for data access.

### <a href="{{'/data-reception' | relative_url}}">Data Reception</a>
Uniform processes (such as quality control and standardisation) to receive (download) or access (API) both data and metadata in a consistent way enabling infrastructure to adhere to global standards and principles (e.g. GA4GH, FAIR) for genotypic and phenotypic data. Data reception means logically describing datasets to an extent that they can become actionable on the 1+MG infrastructure even if they are stored nationally or locally. 

### <a href="{{'/storage-and-interfaces' | relative_url}}">Storage & Interfaces</a>
Organisations store data and offer interfaces (APIs) following international standards that form the technically interoperable infrastructure backbone. Service building is assumed to leverage national and European investments in e-infrastructure capacities. Storage & interfaces need to provide techniques ensuring data privacy and confidentiality.

### <a href="{{'/access-management' | relative_url}}">Data Access Management Tools</a>
Sensitive data needs specialised services to manage data in an ELSI-compliant way. These include e.g. central access portal, central access review process, single collaboration/data use agreement. These tools store user applications for data use and the decisions from the data controllers, i.e. data access authorisations within the legal framework, as well as APIs and standards to communicate access rights to downstream infrastructure services. Together, these tools and processes facilitate and audit secure access for users on a chosen Data Processing service platform.

### <a href="{{'/data-processing' | relative_url}}">Processing</a>
Local, high-performance and cloud computing must fulfil appropriate security standards to provide processing capacities for human data coordinated in 1+MG. Distinct processing events happen on the infrastructure: Localisation of the data and code to the appropriate platform (local or distributed) and data analysis by the individual data user who has acquired the access rights for the intended data use. 


Global Alliance for Genomics and Health (GA4GH) standards are used to link the different applications supporting the five technical functionalities within the B1MG Proof of Concept.  The chosen standards aligned with the functionalities can be seen in the diagram below.  While none of these standards are required for a Node to implement, they can be seen as the interoperability backbone of the infrastructure.

<img src="{{ 'assets/img/data-infrastructure.png' | relative_url }}" class="m-2" style="max-width: 100%; max-height: 100%; vertical-align: middle" alt="Cancer Proof of Concept Schema" />

<figcaption class="text-center">Proof of Concept Schema</figcaption>

<!--<img src="{{ 'assets/img/technical-infrastructure-figure2.png' | relative_url }}" class="m-2" style="max-width: 100%; max-height: 100%; vertical-align: middle" alt="Rare Disease Proof of Concept Schema" />

<figcaption class="text-center">Rare Disease Proof of Concept Schema</figcaption>-->

## [European Genomes Dashboard](https://dashboard.onemilliongenomes.eu/)
This dashboard shows the current number of genomic datasets across the 1+MG Member States.

## User Portal & Central Services
* Under development by the European Genomic Data Infrastructure project, the User Portal will be the main European-level entry point for data access within the infrastructure.



**We are still working on the content for this page.** If you are interested in adding to the page, then:

[Feel free to contribute](how_to_contribute){: class="btn btn-primary btn-lg rounded-pill"}

This is a community-driven website, so contributions are welcome! You will, of course, be listed as a contributor on the page.



