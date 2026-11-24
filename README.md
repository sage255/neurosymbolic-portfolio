# Agent & Ontology Portfolio

Applied Neurosymbolic AI: Prolog logic simulations, OWL ontologies, and deterministic guardrails for autonomous agents.

---

## 🎯 Program Overview & Goals
* **Focus Areas:** Symbolic Logic, Semantic Web Modeling, Graph Databases, and Agentic AI Governance
* **Target Outcome:** Three production-grade portfolio projects demonstrating deterministic reasoning and hallucination-free AI guardrails.

---

## 🗺️ Training Roadmap & Progress Tracker

### 🟪 Phase 1: Logic Fundamentals & Programming Core (Months 1–2)
* **Module 1: Symbolic & Declarative Logic (Prolog)**
  * [ ] Set up local SWI-Prolog environment
  * [ ] Master facts, rules, unification, backtracking, and recursion
  * [ ] Build a state-space logic rule matrix
* **Module 2: Programming Fundamentals (Python)**
  * [ ] Master core data structures (lists, dictionaries) and OOP basics
  * [ ] Write scripts to parse structured data and interface with logic rules
* **📁 Portfolio Milestone 1:**
  * [ ] Build and document a **Deterministic Scene & Logistics Simulator** using Prolog rules wrapped in Python (`/01-prolog-scene-simulator`)

---

### 🟩 Phase 2: Enterprise Semantic Web Modeling (Months 3–5)
* **Module 3: The Semantic Web Stack (RDF/RDFS)**
  * [ ] Model entities, classes, and properties as Subject-Predicate-Object triples
  * [ ] Write valid Turtle (`.ttl`) and N-Triples files manually
* **Module 4: Advanced Ontology Design (OWL & Protégé)**
  * [ ] Install and configure Stanford Protégé
  * [ ] Implement OWL logical restrictions, symmetry, and transitivity
  * [ ] Validate ontology consistency using a reasoner (HermiT / Pellet)
* **📁 Portfolio Milestone 2:**
  * [ ] Design and publish a production-ready **Domain Ontology** mapping complex industry rules (`/02-enterprise-domain-ontology`)

---

### 🟦 Phase 3: Graph Databases & Data Querying (Months 6–8)
* **Module 5: Graph Databases (Neo4j & Triplestores)**
  * [ ] Set up a graph database instance (Neo4j / RDF Triplestore)
  * [ ] Ingest custom ontologies and structured datasets into the graph
* **Module 6: Querying Interconnected Data (SPARQL & Cypher)**
  * [ ] Write complex SPARQL queries to traverse semantic relationships
  * [ ] Query open-source knowledge bases (Wikidata / DBpedia)

---

### 🟧 Phase 4: Modern AI & Neurosymbolic Integration (Months 9–12)
* **Module 7: Knowledge-Infused AI (GraphRAG & LangChain)**
  * [ ] Connect a Knowledge Graph to an LLM using LangChain or LlamaIndex
  * [ ] Implement GraphRAG pipelines to ground LLM outputs in verified triples
* **Module 8: Agentic AI Governance**
  * [ ] Design deterministic rule-based guardrails to constrain autonomous agent actions
* **📁 Portfolio Milestone 3 (Capstone):**
  * [ ] Build and record a demo of a **Neurosymbolic AI Guardrail System** where an LLM enforces strict ontology and compliance rules (`/03-neurosymbolic-agent-guardrails`)

---

## 📂 Repository Structure

```text
agent-ontology-portfolio/
├── 01-prolog-scene-simulator/       # Phase 1: Symbolic logic & Python integration
├── 02-enterprise-domain-ontology/   # Phase 2: RDF/OWL models & Protégé files
├── 03-neurosymbolic-agent-guardrails/ # Phase 4: GraphRAG & deterministic LLM guardrails
└── notes/                           # Reference architectures, SPARQL queries, and study logs
```

---

## 🛠️ Core Tech Stack
* **Logic & Reasoning:** SWI-Prolog, HermiT Reasoner
* **Semantic Web:** RDF, RDFS, OWL, Protégé, Turtle
* **Databases & Querying:** Neo4j, SPARQL, Cypher
* **AI & Integration:** Python, LangChain / LlamaIndex
