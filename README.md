# Manish Kumar Kondoju

**Solutions Engineer / Business Systems Analyst.** Three years owning production reliability for Citi's trading systems. Now building AI tools end to end.

MS Information Systems @ Northeastern (2024–2026, GPA 3.62) · Boston, MA

[LinkedIn](https://linkedin.com/in/manishkumarkondoju) · [kondoju.m@northeastern.edu](mailto:kondoju.m@northeastern.edu)

---

## Track record

| | |
|---|---|
| **Zero** | SLA breaches across 1,200+ annual cases, 18 months |
| **45%** | Faster operational response, via Python automation |
| **80%** | Support questions resolved without a human |
| **0%** | Hallucination rate on CrimeGraphRAG, across 50 test questions |

## What I do

**Production reliability at scale.** Owned reliability and configuration for 15+ enterprise trading applications on Citi's Fixed Income & Currencies desk, in a 24x7 APAC/EMEA/NAM rotation.

**Requirements to shipped software.** Translating what the desk actually needs into use cases, acceptance criteria, and configuration that survives a Change Advisory Board.

**Governed AI in regulated environments.** SR 11-7 model risk management, PII masking ahead of LLM calls, and infosec-approved vendor review — AI that clears bank compliance.

**Applied AI, built not read.** RAG pipelines, knowledge graphs, and multi-agent systems — learned by shipping working software with them.

## Selected work

**[CrimeGraphRAG](https://github.com/ManishKondoju/CrimeInvestigationGraph)** — Zero-hallucination crime investigation platform. Every question compiles into Cypher and runs against a Neo4j knowledge graph *before* the model sees anything, so the LLM can only format what the database actually returned. 1,307 nodes, 3,500+ relationships, 9-entity schema, 4–6s end-to-end.
`Python 3.11` `Neo4j` `LangChain` `Streamlit` `D3.js` `scikit-learn`

**[AgenticSystem](https://github.com/ManishKondoju/AgenticSystem)** — Six coordinated agents taking a raw dataset through profiling, table QA, anomaly detection, and reporting. Agents hand off structured intermediate results rather than raw text, which keeps errors from compounding down the chain.
`CrewAI` `Google TAPAS` `Isolation Forest` `Streamlit` `Plotly`

**[Prompt2Track](https://github.com/ManishKondoju/Prompt2Track)** — One text prompt becomes a finished track: lyrics, album art, and generated music. Three generative models orchestrated behind a single request, with long-running audio jobs handled asynchronously so the interface never blocks. 99.7% pipeline success rate. [Live demo](https://prompt2-track.vercel.app)
`React 18` `FastAPI` `MusicGen Large` `DALL·E 3` `GPT-4`

**[Health Compass](https://github.com/ManishKondoju/Health_Compass)** — RAG platform turning medical questions, lab reports, and symptom logs into answers cited straight back to MedlinePlus, CDC, WHO, and NHS. 700+ indexed documents, 13 specialist categories with urgency detection. [Live demo](https://healthcompass22.streamlit.app/)
`Python` `ChromaDB` `Sentence-Transformers` `OpenRouter (Llama 3.2)` `OCR`

## Toolkit

**Languages** Python · SQL · JavaScript · Shell/Bash · PowerShell
**AI & automation** LangChain · CrewAI · AutoGen · RAG pipelines · MCP integrations · Claude Code · n8n
**Cloud & DevOps** AWS · Azure DevOps · Terraform · Docker · Kubernetes
**Data & analytics** Oracle SQL · Neo4j · Power BI · Tableau · BigQuery · Snowflake
**ITSM & monitoring** ServiceNow · Jira · Confluence · Splunk · ITRS Geneos · Grafana · Datadog

**Certified** AWS Solutions Architect – Associate (2024) · Oracle Database SQL Certified Associate (2024) · ITIL v4 Foundation (2022)

---

> I would rather learn a technology by shipping something with it than by reading about it. That is why the reliability work and the building work are the same job.

**Open to** Solutions Engineer · Business Analyst · Application Analyst · System Analyst · Product Owner · AI Consultant roles.
