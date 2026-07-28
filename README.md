# CoreSense Ontology — published artifacts

This repository is **generated**. It holds the published form of the CoreSense
Ontology (CSO) and exists so that the permanent identifier

> **<https://w3id.org/coresense/cso>**

has a stable, public, anonymously-resolvable target. Content negotiation on that
identifier serves the HTML documentation to browsers and the Turtle to
reasoners, from the same URL.

| Format | File |
| --- | --- |
| Documentation (HTML) | [`index.html`](https://coresenseeu.github.io/cso/) |
| Turtle | [`cso.ttl`](https://coresenseeu.github.io/cso/cso.ttl) |
| RDF/XML | [`cso.owl`](https://coresenseeu.github.io/cso/cso.owl) |
| JSON-LD | [`cso.jsonld`](https://coresenseeu.github.io/cso/cso.jsonld) |
| N-Triples | [`cso.nt`](https://coresenseeu.github.io/cso/cso.nt) |

## Do not edit this repository

Every file here is overwritten by the release workflow in
**[CoreSenseEU/ontology](https://github.com/CoreSenseEU/ontology)**, which is
where the ontology is authored and where issues and pull requests belong. Edits
made here will be lost on the next release.

The documentation is generated with [Widoco](https://github.com/dgarijo/Widoco)
from `build/cso.ttl`, itself produced by ROBOT (merge → reason → relax → reduce
→ annotate → convert). See the contributor guide in the source repository.

## License

Apache License 2.0 — Copyright © 2022–2026 The CORESENSE Consortium.
