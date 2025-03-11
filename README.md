# QoS Ontology

## Purpose and Scope

The QoS Ontology enables the management of qos sessions for network applications that require guaranteed network latency or throughput.
This ontology aligns with the [CAMARA API for Quality-on-Demand (QoD)](https://camaraproject.org/quality-on-demand/).

## Vocabulary Development

This ontology is developed following the guidelines of the [LOT methodology](https://lot.linkeddata.es).

### Requirements

The requirements of this ontology are written as competency questions/natural language statements, which have been captured in a [CSV file](./requirements/requirements.csv).

### Ontology Model

The following diagrams shows the classes and properties defined in the ontology. The diagram follows the [Chowlk notation](https://chowlk.linkeddata.es/notation.html).

![QoS Ontology Diagram](diagrams/qos-figures.svg)

### Ontology Code (OWL)

The OWL code of the ontology, serialized in Turtle format, is available [here](./ontology/ontology.ttl).

### Examples

Sample RDF datasets are provided in the [examples folder](./examples/rdf/).

### Evaluation

This ontology is evaluated using the following tools:
- [OOPS](https://oops.linkeddata.es)
- [FOOPS](https://foops.linkeddata.es/FAIR_validator.html)
- SPARQL queries

The evaluation reports from OOPS and FOOPS, along with the SPARQL queries, are available in the [evaluation folder](./evaluation/).

### Documentation

The ontology documentation was generated using the WIDOCO tool and published online at: https://w3id.org/candil/qos

We encourage to locally develop the ontology documentation before publishing it online. For this, we recommend running WIDOCO tool via Docker container.

To generate the documentation, execute the following command:

```bash
./generate-docs.sh
```

## Acknowledgements

This work was partially supported by the following projects:

- **UNICO 5G I+D 6G-DATADRIVEN**: Redes de próxima generación (B5G y 6G) impulsadas por datos para la fabricación sostenible y la respuesta a emergencias. Ministerio de Asuntos Económicos y Transformación Digital. European Union NextGenerationEU.
- **UNICO 5G I+D 6G-CHRONOS**: Arquitectura asistida por IA para 5G-6G con red determinista para comunicaciones industriales. Ministerio de Asuntos Económicos y Transformación Digital. European Union NextGenerationEU.

![UNICO](./images/ack-logo.png)
