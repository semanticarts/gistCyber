# gistCyber
The gistCyber ontology is a sub-gist ontology. This means that it imports and builds upon the gist ontology.
Hence, the gistCyber repository is a sub-gist repository.

## Unifying Ontology of the multiple Domains of Discourse in Cybersecurity
There are many domains of discourse required in a conversation about cybersecurity. The intent of gistCyber is to give a minimalistic ontology(ies) to cover the basic needs of the community. It is important to keep the level of abstraction appropriate.

To determine the line of demarcation between a general mid-level ontology for cybersecurity and a lower-level ontology for a specialized aspect of cybersecurity is difficult. This is in part due to the large overlap in concepts used. Of specific interest to some contributors to gistCyber is the relationship between the gistCyber domain and the more specific domain of Cyber Threat Intelligence.



### Domains within Cybersecurity
1. Cybersecurity Threat Intelligence
   1. Cyber Actors
      1. Adversaries
      1. Defenders
   1. Behavior Patterns
      1. Attack Patterns
      1. Threat Lifecycles
1. Common Vulnerabilities & Exposures
1. Common Weakness Enumeration
1. Common Attack Patterns Enumeration and Classification
1. Common Platform Enumeration
1. Computing
   1. Hardware
   1. Software
   1. Firmare
   1. Network
1. Risk
   1. Financial
   1. Reputational
1. Business Intelligence
1. Assets
   1. Business
   1. Personal
1. Controls
1. Resilience

The above list is by no means all inclusive. The gistCyber ontology was created to enable 
semantic interoperability between these many sub-domains of cybersecurity.

## The Relationship between gistCyber and other Ontologies

### The gistCyber ontology has dependencies
1. Basic Formal Ontology
1. gist
1. gistComputing

### Cyber Threat Intelligence Ontology (CTIO) - As an Extension of gistCyber
The CTIO is an extension based upon the gistCyber ontology. Most of the concepts needed to represent Cyber Threat Intelligence concepts should already be defined in gistCyber. Concepts that are specialized to the domain of threat intelligence should be asserted in the CTIO.

The difference between the general cybersecurity domain and the cyber threat intelligence domain requires a clear definition of what is meant by "intelligence".
A suggested defintion:
Cyber Threat Intelligence: Information about potential or existing threats in the context of cybersecurity. CTI is information used to protect systems from harm and/or attack.

This definition of CTI considers it as a noun that indicates that CTI is a type of information. CTI is Information. It is useful to consider severl different types of CTI:
1. Operational Cyber Threat Intelligence
1. Stratefic Cyber Threat Intelligence
1. Tactical Cyber Threat Intelligence
1. Technical Cyber Threat Intelligence (not considered by some as a significant type of CTI)


There are actions performed on or with CTI:
1. gathering
1. analyzing
1. interpreting
1. sharing
1. hunting

#### The Importance of the Structured Threat Information eXchange (STIX) language
An important concept of protecting an enterprise from threat and loss is the concept of information sharing.
In order to facilitate sharing between government angencies and the private sector the Department of Homeland 
Security sponsored the development of the STIX language. The language is an exchange format not an ontology.

The STIX 2.1 specification defines many terms and concepts specific to cyber threat intelligence. Because of the extensive
use of STIX by cybersecurity pratitioners it was used the help form the foundations of gistCyber and CTIO.




