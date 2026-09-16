# Graph Theory AI

We explore the use of large language models to track and support progress on open problems in graph theory.

## Projects

* [**Mathpocalypse**](https://github.com/graph-theory-AI/mathpocalypse-project): A pilot study that runs an open-weight LLM over papers in graph theory and combinatorics, with an initial corpus drawn from the *Journal of Graph Theory*. The model is asked to carefully re-check the proofs and flag any potentially incorrect arguments.

* [**Graph Conjectures**](https://github.com/graph-theory-AI/graph-conjectures): A browsable, status-annotated mirror of the **graph theory category** of [Open Problem Garden](http://www.openproblemgarden.org/category/graph_theory), extended with **new conjectures mined from recent arXiv papers**.

* [**Graph Theory LLM Proofs**](https://github.com/graph-theory-AI/Graph-Theory-LLM-Proofs): AI-assisted attempts at the open problems catalogued in **Graph Conjectures**. For each problem a frontier model is asked for a proof, a counterexample, or a meaningful partial result; every claimed resolution is then re-examined by an adversarial reviewer model that re-derives each step, checks the cited sources, and reproduces computational claims where possible. The claims that survive review are written up as self-contained notes for human referees.
