# LambdaGeo

**Research group in Computing and Geotechnologies** at the [Federal University of Maranhão (UFMA)](https://www.ufma.br), São Luís, Brazil. Registered in the [CNPq Directory of Research Groups](http://dgp.cnpq.br/dgp/espelhogrupo/771872).

We work at the intersection of Computer Engineering, Geosciences and Open Science, building open, reproducible tools for spatial simulation, land-change modelling and semantic data integration.

> *"Do dado aberto ao modelo verificado, em código que qualquer um pode rodar."*  
> *From open data to a verified model, in code anyone can run.*

🌐 **[lambdageo.ufma.br](https://lambdageo.ufma.br)** · ✉️ [lambdageo@ufma.br](mailto:lambdageo@ufma.br)

---

## Main project: DisSModel and DisSLUCC

A Python ecosystem for discrete spatial simulation and land-change modelling, an independent alternative to INPE's TerraME/LuccME (which remain the reference). Its packages live in the **[DisSModel](https://github.com/DisSModel)** organization ([documentation](https://dissmodel.github.io/)); the reference outputs, benchmarks, study cases and workflow live here. The [repository map](https://dissmodel.github.io/repository-map.html) shows how they connect.

**Verification against TerraME/LuccME**
- [luccme-goldens](https://github.com/LambdaGeo/luccme-goldens) · [terrame-goldens](https://github.com/LambdaGeo/terrame-goldens): reference outputs of TerraME/LuccME, pinned by SHA-256.
- [disscube-benchmark](https://github.com/LambdaGeo/disscube-benchmark) · [disslucc-benchmark](https://github.com/LambdaGeo/disslucc-benchmark): parity benchmarks of the DisSModel packages against those references.

**Workflows and study cases**
- [open-lucc-workflow](https://github.com/LambdaGeo/open-lucc-workflow): a traceable land-use change experiment built from open data.
- [disscube-grids](https://github.com/LambdaGeo/disscube-grids): study-area examples that build gridded variables from open data.
- [rescience-lulcc](https://github.com/LambdaGeo/rescience-lulcc) · [lulcc-goldens](https://github.com/LambdaGeo/lulcc-goldens): replication of a published land-change study for ReScience C.
- [brmangue-terrame](https://github.com/LambdaGeo/brmangue-terrame): cellular automata model of sea-level rise impacts on mangroves along the Brazilian coast.

## Linked Data and geoinformatics

- [qgissparql](https://github.com/LambdaGeo/qgissparql): QGIS plugin to import Linked Data from SPARQL endpoints as spatial layers.
- [rdfmapper](https://github.com/LambdaGeo/rdfmapper): declarative Object-RDF mapper for Python.
- [dbcells-ontology](https://github.com/LambdaGeo/dbcells-ontology): RDF vocabulary for publishing land-change models as Linked Data.

## Functional programming

- [terrahs](https://github.com/LambdaGeo/terrahs): a Haskell GIS toolkit, rewritten without its original TerraLib dependency.
- [playreg](https://github.com/LambdaGeo/playreg): a regular-expression engine based on Brzozowski derivatives.

## Tools

- [geomosaic](https://github.com/LambdaGeo/geomosaic): a Python tool for building geospatial mosaics.
- [fielddash](https://github.com/LambdaGeo/fielddash): schema-driven Streamlit dashboards for field data collection.

## Papers and books

- [geospatial-modeling-python](https://github.com/LambdaGeo/geospatial-modeling-python): open textbook on geospatial Python, from the basics to DisSModel (in Portuguese).
- Code of published studies: [analise-cerrado-ma](https://github.com/LambdaGeo/analise-cerrado-ma) (deforestation in the Maranhão Cerrado) and [acuracia-slz](https://github.com/LambdaGeo/acuracia-slz) (land-cover accuracy around São Luís).
- Course textbooks: **[LambdaGeo Edu](https://github.com/lambdageo-edu)** · [lambdageo-edu.github.io](https://lambdageo-edu.github.io/).

---

## People

Led by **[Prof. Sérgio Souza Costa](https://lambdageo.ufma.br/people/sergio-costa/)**. Students interested in environmental modelling, GIS and reproducible research software are welcome: write to [lambdageo@ufma.br](mailto:lambdageo@ufma.br).
