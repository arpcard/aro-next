## ARO

The Antibiotic Resistance Ontology describes antibiotic resistance genes and mutations, their products, mechanisms, and associated phenotypes, as well as antibiotics and their molecular targets. It is integrated with the Comprehensive Antibiotic Resistance Database (https://card.mcmaster.ca), a curated resource containing high-quality reference data on the molecular basis of antimicrobial resistance. 

## ARO Next

The next major phase of ARO development has begun, addressing issues of orthogonality and fundamental ontological design, here at ARO Next. ARO Next development will be independent of the CARD website and ongoing curation, so for the time being continue to use [github.com/arpcard/aro](https://github.com/arpcard/aro) as a mirror for active curation at the Comprehensive Antibiotic Resistance Database. ARO Next will replace this active version of ARO used by CARD at a later date.

## Goals

Ontologies, also known as controlled vocabularies, provide a conceptual framework to organize knowledge, best exemplified in CARD by the ARO’s *confers_resistance_to_antibiotic* relationship; for example, CTX-M-15 *confers_resistance_to_antibiotic* cefalotin. In this example, two concepts (CTX-M-15 and cefalotin) are associated via an ontological relationship, of which the ARO uses many. These relationships allow ARO to act as a knowledge graph relating molecules, genes, mutations, resistance mechanisms, and drug targets. Yet, the ARO reflects several shortcuts in its development, as our initial goal was the rapid development of tools for ARG annotation. A lack of interoperable architecture with other ontologies hampers its utility for the broader data science community, e.g., data harmonization efforts, ontological interoperability, and well-structured data for artificial intelligence. While registered in the OBO Foundry of interoperable ontologies, ARO violates two key aspects of formal ontologies: (1) proper upper ontology structures (e.g., "object", "property", "relation") required for semantic interoperability among ontologies and (2) resolution of orthogonality, i.e., the re-use of terms from existing ontologies. For example, beta-lactamases are described in ARO:3000001 *beta-lactamase*, but ARO lacks linkages to the Gene Ontology (GO:0008800 *beta-lactamase activity*) and Chemical Entities of Biological Interest ontology (CHEBI:35627 *β-lactam*). As AMR research relies on an accurate and well-designed ARO, we are undertaking the development of the next generation of ARO here at [ARO Next](https://github.com/arpcard/aro-next) as a core activity to resolve design and orthogonality flaws. Community input into [ARO Next](https://github.com/arpcard/aro-next) is very welcome.

## License

Ontologies at the [Comprehensive Antibiotic Resistance Database](https://card.mcmaster.ca/download) are freely available under the [Creative Commons CC-BY license version 4.0](LICENSE).
