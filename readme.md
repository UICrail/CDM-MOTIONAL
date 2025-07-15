# About the Conceptual Data Model

The [Conceptual Data Model](https://github.com/UICrail/CDM-MOTIONAL/wiki/01-%E2%80%90-What-is-the-CDM%3F) is a product of [Europe's Rail MOTIONAL Project](https://projects.rail-research.europa.eu/eurail-fp1/).
The CDM-MOTIONAL public repository and dependent repositories shall host the Conceptual Data Model, a public MOTIONAL deliverable.
The UICrail GitHub is used, awaiting a possible setup of repositories under Europe's Rail.

The CDM repository mostly links into other repositories that are public by default; some of them may result in being private (e.g. for hosting non-public data for testing purposes).

The CDM repository wiki will be populated in due time, mostly for guidance of non-participants.

[About the CDM, its history, and rationale, see the Wiki home page.](https://github.com/UICrail/CDM-MOTIONAL/wiki)

# Main repositories
Currently, following repositories are available:
* [SemanticRSM](https://github.com/UICrail/SemanticRSM), which currently includes infrastructure topology and geometry, as well as rolling stock elements. Other RSM areas will be added later, as packages are rewritten in RDF/OWL.
* [CDM-IFC](https://github.com/UICrail/CDM-IFC), providing backgrounds regarding [IFC](https://www.buildingsmart.org/standards/bsi-standards/industry-foundation-classes/) (Industry Foundation Classes), by [buildingSMART International](https://www.buildingsmart.org/), and their usage in the CDM.
* [CDM-Signalling](https://github.com/UICrail/CDM-Signalling), providing links with the comprehensive [EULYNX DataPrep](https://eulynx.eu/resource-hub-dataprep-model/) model for signalling data.

Under the hood, the CDM also leverages established ontologies or schemas like [IFC](https://w3id.org/ifc/IFC4X3_ADD2#), [QUDT](http://qudt.org/schema/qudt/), [QUDT (unit)](https://qudt.org/2.1/vocab/unit/), [XSD](http://www.w3.org/2001/XMLSchema#), [GeoSPARQL](http://www.opengis.net/ont/geosparql), [W3C SSN](https://www.w3.org/ns/ssn/), [W3C SOSA](https://www.w3.org/ns/sosa/), ...

# Datasets

[Europe's Rail MOTIONAL Project](https://projects.rail-research.europa.eu/eurail-fp1/) is working on making available various datasets available, using the CDM vocabulary. More information available on the [Wiki](https://github.com/UICrail/CDM-MOTIONAL/wiki/03-%E2%80%90-Datasets)

# Other considerations

In addition, ongoing tasks are summed up under the (non-public) [MOTIONAL "project"](https://github.com/orgs/UICrail/projects/3) (in the sense of Github).
                                                                                                                              
# About RDF/OWL

The CDM heavily rests on Semantic Web technologies, and in particular RDF/OWL as a formal language. For introduction to RDF/OWL, we recommend:
* Demystifying OWL for the Enterprise, by Michael Uschold. 237 pages. (c) Springer Nature Switzerland AG 2022, ISBN:978-3-031-79481-0. *clear and easy introduction for absolute beginner, with practical examples using Protégé desktop*.
* An introduction to ontology engineering, by C. Maria Keet. 318 pages. (c) Individual author and college publications 2018 (http://www.collegepublications.co.uk). ISBN 978-1-84890-295-4. *with wider scope and historical depth*.

Besides, there are many introductory papers or slides available on internet, but these cannot match the paedagogic qualities of these two books.
