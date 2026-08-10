# Awesome-Workplace-Search-Platform

## Top Workplace Search Platform Tools Ecosystem



**Curated List of SaaS/Commercial Products & Open-Source GitHub Projects**  

*Focused on Enterprise/Workplace Search, Unified Knowledge Retrieval, Permission-Aware Search & AI-Powered Company Search*  

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Workplace Search**. These tools index and search across company applications (docs, chat, tickets, code, email, etc.), respect existing permissions, and increasingly offer AI-powered answers and agents grounded in internal knowledge.



**Examples** include Glean, Elastic Workplace Search, Google Cloud Search, Microsoft Search, Guru, Slab Search, Stack Overflow for Teams Search, Algolia Workplace, Lucidworks Workplace, and IBM Watson Discovery (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted workplace and enterprise search — ideal for organizations that want full data sovereignty, no per-seat enterprise pricing, and the ability to run air-gapped or on-prem.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Glean](https://www.glean.com/)**  

  Leading AI-powered workplace search platform that connects to dozens of SaaS apps, respects permissions, and delivers personalized search plus generative answers across company knowledge.



- **[Elastic Workplace Search / Search AI](https://www.elastic.co/)**  

  Enterprise search capabilities built on Elasticsearch, offering connectors, relevance tuning, and AI-enhanced search experiences (note: legacy Workplace Search product evolved into broader Search AI offerings).



- **[Google Cloud Search](https://workspace.google.com/products/cloud-search/)**  

  Search across Google Workspace and connected third-party data sources with Google’s ranking and security model.



- **[Microsoft Search](https://www.microsoft.com/en-us/microsoft-search)**  

  Unified search experience across Microsoft 365, SharePoint, Teams, and other Microsoft and partner sources.



- **[Guru](https://www.getguru.com/)**, **[Slab](https://slab.com/)**, **[Stack Overflow for Teams](https://stackoverflow.co/teams/)**  

  Knowledge management platforms with strong internal search, verification, and Q&A capabilities focused on company knowledge bases.



- **[Algolia](https://www.algolia.com/)**, **[Lucidworks](https://lucidworks.com/)**, **[IBM Watson Discovery](https://www.ibm.com/products/watson-discovery)**  

  Search and relevance platforms that can be applied to workplace and enterprise knowledge retrieval use cases, often with AI/NLP enhancements.



## Open-Source GitHub Projects



- **[Onyx (formerly Danswer)](https://github.com/onyx-dot-app/onyx)**  

  Leading open-source alternative to Glean. Self-hostable AI enterprise search with 40+ connectors, permission-aware retrieval, AI chat with citations, agents, and deep research capabilities. MIT licensed.



- **[Xyne](https://github.com/xynehq/xyne)**  

  AI-first open-source search and answer engine for work. Connects to workplace apps, indexes data with relationship graphs, and provides permission-aware search plus answers — positioned as an open-source Glean/Gemini/Copilot alternative.



- **[OpenBeam](https://openbeam.work/)**  

  Open-source enterprise AI search platform focused on hybrid search, agents, connectors, and full self-hosting with data sovereignty.



- **[Omni](https://github.com/getomnico/omni)**  

  Open-source workplace search and chat built on Postgres (ParadeDB + pgvector). Hybrid BM25 + vector search with connectors and a chat UI that uses tools against the index.



- **[Khoj](https://github.com/khoj-ai/khoj)**  

  Self-hostable AI second brain that searches personal and company documents, supports custom agents, and runs with local or cloud LLMs.



- **[Elasticsearch / OpenSearch based stacks](https://github.com/opensearch-project/OpenSearch)**  

  Foundational open-source search engines frequently used as the backbone for custom workplace search solutions with custom connectors and ranking.



- **[AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)**, **[LibreChat](https://github.com/danny-avila/LibreChat)**, **[Open WebUI](https://github.com/open-webui/open-webui)**  

  Open-source RAG and chat platforms that can be configured for internal knowledge search and Q&A over company documents.



- **[Emerging workplace search projects](https://github.com/)**  

  Newer open-source efforts focused on permission-aware multi-app indexing, hybrid search, and agentic retrieval for internal use.



### Additional Strong Open-Source Options



- Custom connector frameworks and RAG pipelines built on LangChain, LlamaIndex, or similar.

- Meilisearch / Typesense instances combined with workplace data connectors for simpler internal search.

- Nextcloud Search and other self-hosted collaboration suite search features.

- Many internal knowledge-base search tools released as open source by companies and communities.



**Frameworks for building custom systems**: For the closest Glean-like experience start with **Onyx**. Explore **Xyne**, **OpenBeam**, or **Omni** for alternative architectures. Use **OpenSearch/Elasticsearch** when you need maximum control over indexing and ranking. Pair any of these with open LLMs or your preferred model provider, and enforce source permissions carefully at query time.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/commercial or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workplace search involves sensitive company data and access control. Self-hosted open-source solutions give full data ownership but require careful implementation of connectors, permission syncing, security hardening, and ongoing maintenance. Commercial platforms often provide broader connector coverage, polished relevance, and managed operations out of the box.

- Always validate that search results respect source-system permissions and comply with your organization’s data governance policies.



---



**Made for knowledge workers, platform engineers, and organizations seeking sovereign internal search.**  

Let's make company knowledge more findable and under your control.
