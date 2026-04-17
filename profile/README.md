
# LambdaGeo 🔷

> **Semantic technologies and geospatial intelligence for environmental modeling**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Research](https://img.shields.io/badge/Research-Geoinformatics-green)](https://lambdageo.github.io)
[![JOSS](https://joss.theoj.org/papers/status/pending.svg)](https://joss.theoj.org)

🌐 [Website](https://lambdageo.github.io) • 📧 [Contact](mailto:sergio.costa@ufma.br) • 🎓 [Publications](#-publications--citation)

---

## 🎯 Mission

LambdaGeo develops **open-source tools** that bridge **Linked Data**, **Semantic Web**, and **Geospatial Analysis** — with focus on coastal ecosystems, mangrove dynamics, and climate change resilience.

We believe that semantic technologies can make environmental data more **interoperable**, **reproducible**, and **actionable** for researchers, policymakers, and communities.

---

## 🔬 Core Projects

| Repository | Description | Tech Stack | Status |
|-----------|-------------|-----------|--------|
| [**qgissparql**](https://github.com/LambdaGeo/qgissparql) | 🔗 QGIS plugin for **bidirectional RDF ↔ GIS integration**. Import SPARQL results as layers; export layers as GeoSPARQL triples. | Python, QGIS, RDFLib, SPARQL | ✅ JOSS submission in progress |
| [**rdfmapper**](https://github.com/LambdaGeo/rdfmapper) | 🐍 Declarative **Object-RDF Mapper** for Python. Map classes to RDF with decorators, auto-generate SHACL shapes, and run dynamic SPARQL queries. | Python, RDFLib, SHACL | ✅ Published on PyPI |
| [**brmangue**](https://github.com/LambdaGeo/brmangue) | 🌿 Spatially explicit **Cellular Automata model** for mangrove vulnerability to sea-level rise. Built on TerraME/Lua for Brazilian coastal zones. | Lua, TerraME, GIS | 🧪 Applied case studies |

---

## 🔗 Ecosystem Integration

LambdaGeo tools are designed to interoperate with the **[DisSModel](https://github.com/DisSModel)** ecosystem:

```
DisSModel (distributed spatial modeling framework)
    │
    ├── dissmodel-core      → Simulation engine (Python)
    ├── dissmodel-ca        → Cellular Automata library
    └── dissmodel-platform  → Scalable execution (FastAPI + Docker)
    
LambdaGeo (semantic geospatial layer)
    │
    ├── qgissparql          → GIS ↔ Linked Data bridge
    ├── rdfmapper           → Python ↔ RDF abstraction
    └── brmangue            → Domain model (mangroves + SLR)
```

👉 *Use `rdfmapper` to annotate DisSModel outputs as Linked Data, or `qgissparql` to visualize semantic results directly in QGIS.*

---

## 🚀 Getting Started

### For Researchers
```bash
# Install rdfmapper for semantic data modeling
pip install rdfmapper-py

# Clone QGISSPARQL for GIS integration
git clone https://github.com/LambdaGeo/qgissparql
# → Install via QGIS Plugin Manager or copy to plugins/ directory
```

### For Developers
```bash
# Contribute to rdfmapper
git clone https://github.com/LambdaGeo/rdfmapper
cd rdfmapper
pip install -e ".[dev]"
pytest tests/ -v
```

📚 Full documentation: [lambdageo.github.io](https://lambdageo.github.io)

---

## 📊 Research Impact

### Case Studies
- 🇧🇷 **Maranhão Island**: Mangrove migration modeling under sea-level rise scenarios *(Bezerra & Costa, 2014; 2025)*
- 🌍 **Baixada Maranhense (Ramsar site)**: Integrated assessment of anthropic pressure and climate vulnerability

### Publications & Citation
If you use LambdaGeo tools in academic work, please cite:

```bibtex
@software{lambdageo2026,
  author       = {Costa, Sergio Souza and Goiabeira, Felipe and Santos Junior, Nerval},
  title        = {LambdaGeo: Semantic Tools for Geospatial Research},
  year         = {2026},
  publisher    = {GitHub},
  url          = {https://github.com/LambdaGeo},
  doi          = {10.5281/zenodo.xxxxxxx}  ← Add Zenodo DOI when available
}
```

📄 Preprints and papers: [Google Scholar](https://scholar.google.com/citations?user=YOUR_ID) • [ORCID](https://orcid.org/YOUR_ORCID)

---

## 🤝 Contributing

We welcome contributions from researchers, developers, and domain experts!

- 🐛 Report bugs or request features via [Issues](https://github.com/LambdaGeo/qgissparql/issues)
- 💬 Discuss ideas in [Discussions](https://github.com/LambdaGeo/qgissparql/discussions)
- 📝 Submit improvements via Pull Requests (see [CONTRIBUTING.md](https://github.com/LambdaGeo/qgissparql/blob/main/CONTRIBUTING.MD))
- 🌐 Help translate documentation (currently EN/PT-BR)

---

## 👥 Team & Affiliations

**Lead**: [Sérgio Souza Costa](https://github.com/profsergiocosta) — Professor, Federal University of Maranhão (UFMA) • PhD, INPE/Brazil

**LambdaGeo Research Group**  
Universidade Federal do Maranhão (UFMA) • Department of Computing • São Luís, MA, Brazil

🔗 Part of the broader **[DisSModel](https://github.com/DisSModel)** initiative for open, reproducible spatial modeling.

---

> *"Making geospatial knowledge semantic, interoperable, and open."*
