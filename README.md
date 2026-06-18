# GreenKMOnto: Green Knowledge Management Ontology

## Introduction
This repository contains the ontology and SPARQL queries developed for the research paper:

**"Developing the Green Knowledge Management Ontology (GreenKMOnto): A Dynamic Framework for Green Knowledge Management in Organizations"**

*Journal: Applied Ontology*
*Status: Under review (as of June 2026)*

---

## Repository Structure

| File/Directory | Description |
|----------------|-------------|
| `GreenKMOnto.ttl` | Main ontology file in Turtle format |
| `sparql-queries/` | Folder containing all SPARQL queries (13 files) |
| `LICENSE` | MIT License file |
| `CITATION.cff` | Citation metadata for the ontology |

---

## Ontology Statistics

| Metric | Value |
|--------|-------|
| Classes | 87 |
| Object Properties | 22 |
| Data Properties | 21 |
| Equivalent Classes | 8 |
| Disjoint Axioms | 2 |
| Version | 2.0-revised |

---

## Usage
GreenKMOnto is designed for organizations seeking to systematically manage knowledge related to environmental sustainability. It provides a semantic infrastructure that integrates green knowledge assets (e.g., best practices, green technologies, policies, and evaluation criteria) with organizational processes, projects, and knowledge workers. The ontology supports monitoring green knowledge across the organization, assessing knowledge risks (e.g., difficulty, strategic importance, cost), and inferring appropriate management strategies (codification vs. personalization). It can be used in various organizational contexts—such as manufacturing, energy, and technology sectors—to align knowledge management with sustainability goals like carbon reduction, waste minimization, and resource conservation.

### Loading in Protégé
1. Open Protégé (version 5.6.9 or later).
2. Select `File` → `Open`.
3. Choose the `GreenKMOnto.ttl` file.
4. Activate the reasoner: `Reasoner` → `Start reasoner` → `Pellet`.

### Running SPARQL Queries
All competency questions (CQ11-CQ35) are available as separate SPARQL query files in the `sparql-queries/` folder:

1. In Protégé, open the `SPARQL Query` tab.
2. Copy the content of any `.rq` file from the `sparql-queries/` folder.
3. Execute the query.

### Command Line (with Apache Jena)
```bash
# Download Apache Jena
# Run a SPARQL query
arq --data GreenKMOnto.ttl --query sparql-queries/CQ11-HighPriorityKnowledge.rq
```

---

## Competency Questions

The ontology was designed to answer the following competency questions, organized into three categories:

### Knowledge Block Priority
| ID | Question |
|----|----------|
| CQ11 | What is the set of behaviors that place a knowledge block in the category of high-priority knowledge? |
| CQ12 | What behaviors contribute to categorizing a knowledge block as risk knowledge? |
| CQ13 | Which knowledge block attracts the highest level of engagement from knowledge workers? |
| CQ14 | What set of behaviors and properties determines the strategy of dealing with knowledge in the organization? |

### Knowledge Workers' Networks
| ID | Question |
|----|----------|
| CQ21 | Which knowledge worker has the most diversity in green knowledge scope? |
| CQ22 | Which knowledge worker has the most communication network? |
| CQ23 | Which knowledge worker has the most diverse communication network? |
| CQ24 | Which green knowledge block has the minimum/maximum number of involved knowledge workers? |

### Organization's Position in Green Management
| ID | Question |
|----|----------|
| CQ31 | What are the defining behaviors that designate a knowledge block as green knowledge? |
| CQ32 | Which aspect of green management has the most active knowledge blocks? |
| CQ33 | Which of the organizational processes provides the most support for green management? |
| CQ34 | Which of the organizational processes needs more attention to green management aspects? |
| CQ35 | Which aspect of green management has the most active project? |

The complete SPARQL queries for all competency questions are available in the `sparql-queries/` folder.

---

## Citation

If you use this ontology in your research, please cite the paper as:

```bibtex
@article{Sareminia2026GreenKMOnto,
  title={Developing the Green Knowledge Management Ontology (GreenKMOnto): A Dynamic Framework for Green Knowledge Management in Organizations},
  author={Sareminia, Saba},
  journal={Applied Ontology},
  year={2026},
  note={Under review}
}
```

The `CITATION.cff` file in this repository provides the same information in a machine-readable format.

---

## License
This work is licensed under the MIT License. See the `LICENSE` file for details.

---

## Links
- **GitHub Repository:** https://github.com/YourUsername/GreenKMOnto
- **Zenodo DOI:** https://doi.org/10.5281/zenodo.20126202

---

## Contact
For questions or suggestions, please contact the author:

**Saba Sareminia, Ph.D.**  
Assistant Professor  
Department of Industrial and Systems Engineering  
Isfahan University of Technology (IUT), Iran  
Email: s.sareminia@iut.ac.ir  
Website: https://saremysaba.iut.ac.ir/  
ORCID: https://orcid.org/0000-0002-8300-7288
