# vsml-ontology
Vessel Markup Language (VsML): A Vocabulary for Federated Ship Design

VsML is a vocabulary for describing vessel design parameters, spatial, functional, provenance, and logic. It is designed to federate across
existing maritime ontologies including OCX Schema, SFI Index
System, W3C Organization Ontology, and PROV-O, while also filling missing gaps in concepts and data relationships.

## Namespace

`https://vsml.no/`

## Ontology files

| Format    | File                        |
|-----------|-----------------------------|
| Turtle    | ontology/vsml.ttl           |
| RDF/XML   | ontology/vsml.owl           |
| JSON-LD   | ontology/vsml.jsonld        |

## Concepts

VsML currently defines:
- Core structural classes (Ship, Hull, Deck, Particulars)
- Object properties (authoredBy, boundBy)
- Datatype properties (hasValue, hasUnit)
- Named individuals from vessel specification data

## Instance data

`instances/gunnerus.ttl` contains RDF instance data for the
research vessel RV Gunnerus operated by NTNU.

## Related ontologies

- [OCX Schema](https://3docx.org)
- [SFI Index System](https://www.dnv.com/sfi/)
- [W3C Organization Ontology](https://www.w3.org/TR/vocab-org/)
- [PROV-O](https://www.w3.org/TR/prov-o/)
- [Ontology of Units of Measure](http://www.ontology-of-units-of-measure.org/resource/om-2/)

## Contact

Jan Bronson (janica.a.bronson@ntnu.no, janicabronson@gmail.com)