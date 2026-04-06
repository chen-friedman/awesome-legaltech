# Awesome Legaltech [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![GitHub Stars](https://img.shields.io/github/stars/chen-friedman/awesome-legaltech?style=social)](https://github.com/chen-friedman/awesome-legaltech) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

<div align="center">

### **The Ultimate Collection of Open-Source Legal Technology & AI Resources**

*Curating the best production-ready tools, datasets, and communities for legal professionals and developers*

[![Legal Tech](https://img.shields.io/badge/Legal%20Tech-Open%20Source-blue?style=for-the-badge&logo=scale&logoColor=white)](https://github.com/topics/legal-tech)
[![AI Powered](https://img.shields.io/badge/AI%20Powered-Legal%20Solutions-purple?style=for-the-badge&logo=brain&logoColor=white)](https://github.com/topics/legal-ai)
[![Global Scope](https://img.shields.io/badge/Global-Jurisdiction%20Tagged-green?style=for-the-badge&logo=world&logoColor=white)](https://github.com/topics/global)

**[🇬🇧 English](README.md) | [🇮🇱 עברית](README_HE.md)**

</div>

---

## What Makes This List Special?

**Rigorous Quality Standards** → Only production-ready, actively maintained projects with real-world adoption  
**Global Legal Coverage** → Worldwide scope with clear jurisdiction tagging (🇺🇸 🇪🇺 🇬🇧 🇩🇪 🇮🇳 🇮🇱 🌍)  
**Practitioner-Tested Tools** → Real solutions that legal professionals deploy in actual workflows  
**Premium AI Resources** → Curated datasets, benchmarks, and models purpose-built for legal applications  
**Thriving Ecosystems** → Active communities driving innovation and collaborative development  

> **New to Legal AI?** Start with our [Quick Start Guide](#quick-start-guide) below!

---

## Table of Contents

| **Quick Navigation** | **Count** | **Best For** |
|----------------------|-----------|--------------|
| [NLP Libraries & Domain Models](#nlp-libraries--domain-models) | 10 projects | Text processing & analysis |
| [AI-Powered Contract & Document Analytics](#ai-powered-contract--document-analytics) | 5 platforms | Contract intelligence |
| [RAG & AI Infrastructure](#rag--ai-infrastructure) | 8 tools | Building legal AI apps |
| [Agentic AI & Automation](#agentic-ai--automation) | 5 tools | AI agents & workflow automation |
| [Legal Research & Case Law Data/APIs](#legal-research--case-law-dataapis) | 9 resources | Research & citations |
| [E-Discovery & Litigation](#e-discovery--litigation) | 6 tools | Legal discovery & annotation |
| [Speech Recognition & Transcription](#speech-recognition--transcription) | 10 tools | Audio/video transcription |
| [Document Signing & Collaboration](#document-signing--collaboration) | 5 platforms | Digital signatures & wikis |
| [Document Management, OCR & PDF](#document-management-ocr--pdf) | 14 solutions | Document processing |
| [Document Assembly & Rules-as-Code](#document-assembly--rules-as-code) | 7 platforms | Automation & workflows |
| [Knowledge Management](#knowledge-management) | 5 tools | Research notes & PKM |
| [AI Agent Skills for Legal Work](#ai-agent-skills-for-legal-work) | 14 skills | Legal AI automation |
| [Datasets & Benchmarks](#datasets--benchmarks) | 10 collections | Training & evaluation |
| [General-Purpose Document Intelligence](#general-purpose-document-intelligence-useful-for-legal) | 6 tools | Document understanding |
| [Learning, Communities & Curations](#learning-communities--curations) | 6 communities | Education & networking |

**Total: 120+ High-Quality Open-Source Legal Tech Resources**

---

## Quick Start Guide

### For Legal Professionals
1. **Start with**: [AI-Powered Contract Analytics](#ai-powered-contract--document-analytics) for document review
2. **Research tools**: [Legal Research & Case Law APIs](#legal-research--case-law-dataapis) for case discovery
3. **Document processing**: [Document Management & OCR](#document-management-ocr--pdf) for digitization

### For Developers
1. **Begin with**: [NLP Libraries & Models](#nlp-libraries--domain-models) for text processing
2. **Training data**: [Datasets & Benchmarks](#datasets--benchmarks) for model development  
3. **AI infrastructure**: [RAG & AI Infrastructure](#rag--ai-infrastructure) for building pipelines

### For Organizations
1. **Enterprise solutions**: [OpenContracts](https://github.com/JSv4/OpenContracts) for contract analytics
2. **Document workflows**: [docassemble](https://github.com/jhpyle/docassemble) for automation
3. **Case management**: [CourtListener](https://github.com/freelawproject/courtlistener) for legal data

---

## NLP Libraries & Domain Models

*Essential tools for processing and understanding legal text with specialized language models*

| **Project** | **Description** | **Scope** | **Stars** | **License** |
|-------------|-----------------|-----------|-----------|-------------|
| **[Hugging Face Transformers](https://github.com/huggingface/transformers)** | Universal toolkit for fine-tuning and running transformer models on legal text | Global | ⭐ 159k | Apache-2.0 |
| **[spaCy](https://github.com/explosion/spaCy)** | Industrial-strength NLP in Python — foundation for many legal NLP pipelines | Global | ⭐ 33k | MIT |
| **[Sentence Transformers](https://github.com/UKPLab/sentence-transformers)** | State-of-the-art text embeddings for semantic legal search | Global | ⭐ 19k | Apache-2.0 |
| **[LexNLP](https://github.com/LexPredict/lexpredict-lexnlp)** | Information extraction from unstructured legal text (Python) | Global | — | Apache-2.0 |
| **[Blackstone](https://github.com/ICLRandD/Blackstone)** | spaCy pipeline for long-form legal text processing | Global | — | MIT |
| **[LEGAL-BERT](https://huggingface.co/nlpaueb/legal-bert-base-uncased)** | Pretrained BERT variants for legal corpora (contracts, ECHR, EU law) | EU/Global | — | — |
| **[InLegalBERT](https://github.com/Law-AI/pretraining-bert)** 🇮🇳 | BERT models and recipes for Indian law corpora | India | — | — |
| **[LeXLMs](https://github.com/coastalcph/lexlms)** | Corpora and probing tasks for legal language models | Multilingual | — | — |
| **[Legal-HeBERT](https://github.com/avichaychriqui/Legal-HeBERT)** 🇮🇱 | BERT model for Hebrew legal and legislative domains | Israel | — | — |
| **[CaseHOLD](https://github.com/reglab/casehold)** | Tasks and baselines for case-law holdings analysis | Global | — | — |

---

## AI-Powered Contract & Document Analytics

*Enterprise-grade platforms for intelligent contract analysis and document understanding*

| **Project** | **Features** | **Best For** | **Maturity** |
|-------------|--------------|--------------|---------------|
| **[OpenContracts](https://github.com/JSv4/OpenContracts)** | Enterprise document analytics with AI-powered analysis (GPL-3) | Large organizations | ![Enterprise](https://img.shields.io/badge/maturity-enterprise-darkgreen) |
| **[ContraxSuite](https://github.com/LexPredict/lexpredict-contraxsuite)** | Full contract analytics & document platform (AGPL) | Commercial use | ![Production](https://img.shields.io/badge/maturity-production-green) |
| **[LawGlance](https://github.com/lawglance/lawglance)** | Free, open-source RAG-based AI legal assistant | SME & individuals | ![Community](https://img.shields.io/badge/maturity-community-blue) |
| **[OpenEDGAR](https://github.com/LexPredict/openedgar)** 🇺🇸 | Framework for searchable EDGAR filings databases | US Securities | ![Stable](https://img.shields.io/badge/maturity-stable-lightblue) |
| **[CUAD Tools](https://github.com/TheAtticusProject/cuad)** | Code and data interfaces for Contract Understanding | Research | ![Research](https://img.shields.io/badge/maturity-research-orange) |

---

## RAG & AI Infrastructure

*Core infrastructure for building retrieval-augmented and AI-powered legal applications*

| **Project** | **Description** | **Stars** | **License** |
|-------------|-----------------|-----------|-------------|
| **[Ollama](https://github.com/ollama/ollama)** | Run large language models locally — essential for confidential legal documents | ⭐ 168k | MIT |
| **[LangChain](https://github.com/langchain-ai/langchain)** | The agent engineering platform — build LLM apps and RAG pipelines | ⭐ 133k | MIT |
| **[Open WebUI](https://github.com/open-webui/open-webui)** | Self-hosted ChatGPT-like interface for local and remote LLMs | ⭐ 130k | — |
| **[LlamaIndex](https://github.com/run-llama/llama_index)** | Data framework for building LLM applications over your documents | ⭐ 48k | MIT |
| **[Qdrant](https://github.com/qdrant/qdrant)** | High-performance vector database for semantic search and AI applications | ⭐ 30k | Apache-2.0 |
| **[Chroma](https://github.com/chroma-core/chroma)** | Open-source AI-native vector database for embeddings | ⭐ 27k | Apache-2.0 |
| **[Haystack](https://github.com/deepset-ai/haystack)** | Production-grade NLP framework for document search and QA pipelines | ⭐ 25k | Apache-2.0 |
| **[pgvector](https://github.com/pgvector/pgvector)** | Vector similarity search extension for PostgreSQL — zero-infra RAG | ⭐ 21k | — |

---

## Agentic AI & Automation

*Frameworks and platforms for building AI agents and automating legal workflows*

| **Project** | **Description** | **Stars** | **License** |
|-------------|-----------------|-----------|-------------|
| **[n8n](https://github.com/n8n-io/n8n)** | Fair-code workflow automation with 400+ integrations and native AI — ideal for legal ops | ⭐ 183k | — |
| **[Browser Use](https://github.com/browser-use/browser-use)** | AI agents that control a browser to automate web-based legal research | ⭐ 86k | MIT |
| **[AutoGen](https://github.com/microsoft/autogen)** | Microsoft’s multi-agent framework for orchestrating complex AI workflows | ⭐ 57k | CC-BY-4.0 |
| **[CrewAI](https://github.com/crewAIInc/crewAI)** | Framework for orchestrating role-playing autonomous AI agents | ⭐ 48k | MIT |
| **[Activepieces](https://github.com/activepieces/activepieces)** | Open-source no-code automation with MCP support and self-hosting | ⭐ 22k | — |

---

## Legal Research & Case Law Data/APIs

*Comprehensive databases and APIs for legal research and case law discovery*

| **Project** | **Coverage** | **Jurisdiction** | **API Access** |
|-------------|--------------|------------------|----------------|
| **[CourtListener](https://github.com/freelawproject/courtlistener)** 🇺🇸 | Primary legal data & research platform | United States | ![API](https://img.shields.io/badge/API-available-green) |
| **[Juriscraper](https://github.com/freelawproject/juriscraper)** 🇺🇸 | Scrapers for opinions, oral arguments, PACER content | United States | ![Tools](https://img.shields.io/badge/type-tools-blue) |
| **[Eyecite](https://github.com/freelawproject/eyecite)** 🇺🇸 | Fast, robust legal citation extractor | United States | ![Library](https://img.shields.io/badge/type-library-purple) |
| **[Caselaw Access Project](https://lil.law.harvard.edu/our-work/caselaw-access-project/)** 🇺🇸 | 6.7M+ U.S. court decisions with API | United States | ![API](https://img.shields.io/badge/API-available-green) |
| **[UK National Archives](https://nationalarchives.github.io/ds-find-caselaw-docs/public/)** 🇬🇧 | Public API for UK court judgments | United Kingdom | ![API](https://img.shields.io/badge/API-available-green) |
| **[Open Legal Data](https://github.com/openlegaldata/oldp)** 🇩🇪 | German legal data platform & API | Germany | ![Platform](https://img.shields.io/badge/type-platform-orange) |
| **[EUR-Lex SPARQL](https://eur-lex.europa.eu/content/help/data-reuse/sparql-endpoint.html)** 🇪🇺 | Official EU law SPARQL API — access all EU legislation and case law | European Union | ![API](https://img.shields.io/badge/API-available-green) |
| **[Open Knesset](https://github.com/hasadna/Open-Knesset)** 🇮🇱 | Open data platform for Israeli Knesset legislative proceedings and members | Israel | ![Platform](https://img.shields.io/badge/type-platform-orange) |
| **[OpenAlex](https://github.com/ourresearch/openalex-api-tutorials)** | Fully open catalog of 250M+ scholarly works including legal research | Global | ![API](https://img.shields.io/badge/API-available-green) |

---

## E-Discovery & Litigation

*Specialized tools for legal discovery, document review, annotation, and litigation support*

| **Project** | **Capabilities** | **Use Case** | **Stars** |
|-------------|------------------|--------------|----------|
| **[Label Studio](https://github.com/HumanSignal/label-studio)** | Multi-type data labeling and annotation tool | Legal document annotation & NLP training data | ⭐ 27k |
| **[doccano](https://github.com/doccano/doccano)** | Open source annotation tool for ML practitioners | NLP training data from legal corpora | ⭐ 11k |
| **[Apache Tika](https://github.com/apache/tika)** | Detects and extracts metadata and text from 1000+ file types | eDiscovery content analysis | ⭐ 4k |
| **[FreeEed](https://github.com/shmsoft/FreeEed)** | Complete eDiscovery processing (OCR, indexing, metadata) | Large-scale discovery | — |
| **[FreeDiscovery](https://github.com/FreeDiscovery/FreeDiscovery)** | Information retrieval engine based on scikit-learn | Document analysis | — |
| **[FOIAMachine](https://github.com/cirlabs/foiamachine)** 🇺🇸 | Manage and send FOIA requests with agency directory | Government transparency | — |

---

## Speech Recognition & Transcription

*Essential tools for converting audio/video to text in legal workflows*

| **Project** | **Specialty** | **Performance** | **Use Case** |
|-------------|---------------|-----------------|--------------|
| **[Whisper](https://github.com/openai/whisper)** | General-purpose speech recognition by OpenAI | ![High](https://img.shields.io/badge/accuracy-high-green) | Multilingual transcription |
| **[WhisperX](https://github.com/m-bain/whisperX)** | Fast ASR with word-level timestamps and speaker diarization | ![Ultra Fast](https://img.shields.io/badge/speed-70x_realtime-brightgreen) | Speaker identification |
| **[faster-whisper](https://github.com/guillaumekln/faster-whisper)** | Optimized Whisper implementation | ![Fast](https://img.shields.io/badge/performance-fast-green) | Efficient transcription |
| **[insanely-fast-whisper](https://github.com/Vaibhavs10/insanely-fast-whisper)** | Ultra-fast Whisper implementation | ![Insane](https://img.shields.io/badge/speed-insane-brightgreen) | Batch processing |
| **[WhisperLiveKit](https://github.com/QuentinFuxa/WhisperLiveKit)** | Real-time speech recognition with Whisper | ![Real-time](https://img.shields.io/badge/mode-realtime-blue) | Live transcription |
| **[whisper-diarization](https://github.com/MahmoudAshraf97/whisper-diarization)** | Speaker diarization with Whisper | ![Specialized](https://img.shields.io/badge/focus-diarization-orange) | Multi-speaker identification |
| **[Vibe](https://github.com/thewh1teagle/vibe)** | Desktop transcription app with Whisper | ![Desktop](https://img.shields.io/badge/platform-desktop-lightblue) | Self-hosted transcription |
| **[Scriberr](https://github.com/rishikanthc/Scriberr)** | Transcription and note-taking tool | ![Notes](https://img.shields.io/badge/feature-notes-purple) | Meeting transcription |
| **[hebrew_whisper](https://github.com/ShmuelRonen/hebrew_whisper)** 🇮🇱 | GUI for Hebrew transcription using ivrit.ai Whisper models | ![Hebrew](https://img.shields.io/badge/language-Hebrew-blue) | Hebrew legal transcription |
| **[ivrit.ai Whisper Turbo](https://huggingface.co/ivrit-ai/whisper-large-v3-turbo-ct2)** 🇮🇱 | Optimized Hebrew Whisper model with 388 hours training data | ![Optimized](https://img.shields.io/badge/performance-optimized-green) | Hebrew speech recognition |

---

## Document Signing & Collaboration

*Platforms for digital document signing, secure notes, and collaborative documentation*

| **Project** | **Primary Use** | **Stars** | **License** |
|-------------|-----------------|-----------|-------------|
| **[Documenso](https://github.com/documenso/documenso)** | Open-source DocuSign alternative | — | AGPL |
| **[DocuSeal](https://github.com/docusealco/docuseal)** | Document filling and signing platform | — | AGPL |
| **[OpenSign](https://github.com/OpenSignLabs/OpenSign)** | Free & open-source DocuSign alternative with self-hosting | ⭐ 6k | — |
| **[Notesnook](https://github.com/streetwriters/notesnook)** | Fully open source & E2E-encrypted note-taking — ideal for sensitive legal work | ⭐ 14k | GPL-3.0 |
| **[Docmost](https://github.com/docmost/docmost)** | Collaborative wiki and documentation software | — | AGPL |

---

## Document Management, OCR & PDF

*Essential tools for document digitization, management, and processing workflows*

| **Project** | **Core Function** | **Stars** | **License** |
|-------------|-------------------|-----------|-------------|
| **[markitdown](https://github.com/microsoft/markitdown)** | Convert PDF/DOCX/PPTX and more to Markdown | ⭐ 93k | MIT |
| **[Tesseract](https://github.com/tesseract-ocr/tesseract)** | Industry-standard OCR engine, 100+ languages | ⭐ 58k | Apache-2.0 |
| **[Docling](https://github.com/docling-project/docling)** | Modern document parsing — PDF/DOCX/PPTX/HTML | ⭐ 57k | MIT |
| **[Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)** | Local web-based PDF toolbox (split/merge/convert/OCR) | ⭐ 50k | GPL-3.0 |
| **[Gotenberg](https://github.com/gotenberg/gotenberg)** | Developer-friendly API for converting HTML/DOCX/more to PDF | ⭐ 12k | MIT |
| **[pdfplumber](https://github.com/jsvine/pdfplumber)** | Extract text, tables, and metadata from PDFs with precision | ⭐ 10k | MIT |
| **[PyMuPDF](https://github.com/pymupdf/PyMuPDF)** | High-performance Python library for PDF extraction, annotation, and rendering | ⭐ 9k | AGPL-3.0 |
| **[WeasyPrint](https://github.com/Kozea/WeasyPrint)** | Convert HTML/CSS to PDF — great for generating court-ready documents | ⭐ 9k | BSD-3-Clause |
| **[OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF)** | Add searchable OCR text layer to scanned PDFs | — | MPL-2.0 |
| **[docTR](https://github.com/mindee/doctr)** | Deep learning OCR engine with strong accuracy on structured documents | ⭐ 6k | Apache-2.0 |
| **[EasyOCR](https://github.com/JaidedAI/EasyOCR)** | Ready-to-use OCR with 80+ languages | — | Apache-2.0 |
| **[paperless-ngx](https://github.com/paperless-ngx/paperless-ngx)** | Self-hosted document management system with AI tagging | — | GPL-3.0 |
| **[Paperless-AI](https://github.com/clusterzx/paperless-ai)** | AI addon for paperless-ngx (semantic search, auto-classification) | — | — |
| **[ExifTool](https://github.com/exiftool/exiftool)** | Read/write metadata in files — digital evidence analysis | — | GPL |

---

## Document Assembly & Rules-as-Code

*Platforms for automating legal document creation and implementing legal logic as code*

| **Project** | **Primary Use** | **Target Users** | **Technical Level** |
|-------------|-----------------|------------------|---------------------|
| **[docassemble](https://github.com/jhpyle/docassemble)** | Expert-system platform for guided interviews | Legal professionals | ![Medium](https://img.shields.io/badge/technical-medium-orange) |
| **[AssemblyLine](https://github.com/SuffolkLITLab/docassemble-AssemblyLine)** 🇺🇸 | Court-form automation toolkit | Court systems | ![Low](https://img.shields.io/badge/technical-low-green) |
| **[python-docx-template](https://github.com/elapouya/python-docx-template)** | Jinja2-based template engine for generating Word legal documents | Developers | ![Low](https://img.shields.io/badge/technical-low-green) |
| **[Blawx](https://github.com/Lexpedite/blawx)** | Visual Rules-as-Code environment | Legal technologists | ![High](https://img.shields.io/badge/technical-high-red) |
| **[Catala](https://github.com/CatalaLang/catala)** | Programming language for faithful statute implementation | Developers | ![High](https://img.shields.io/badge/technical-high-red) |
| **[OpenFisca](https://github.com/openfisca/openfisca-core)** | Open legislation simulation engine — used by governments to model social laws | Govtech / Developers | ![High](https://img.shields.io/badge/technical-high-red) |
| **[LEOS](https://code.europa.eu/leos/core)** 🇪🇺 | Legislative editing platform for AkomaNtoso XML format | EU institutions | ![Enterprise](https://img.shields.io/badge/maturity-enterprise-darkgreen) |

---

## Knowledge Management

*Tools for building personal knowledge bases, research notes, and collaborative workspaces*

| **Project** | **Description** | **Stars** | **License** |
|-------------|-----------------|-----------|-------------|
| **[AFFiNE](https://github.com/toeverything/AFFiNE)** | Next-gen knowledge base combining docs, whiteboard, and database — privacy-first | ⭐ 67k | — |
| **[Memos](https://github.com/usememos/memos)** | Open-source, self-hosted note-taking built for quick capture — Markdown-native | ⭐ 59k | MIT |
| **[SiYuan](https://github.com/siyuan-note/siyuan)** | Privacy-first, self-hosted personal knowledge management with full encryption | ⭐ 42k | AGPL-3.0 |
| **[Logseq](https://github.com/logseq/logseq)** | Privacy-first open-source platform for knowledge management — loved by researchers and lawyers | ⭐ 42k | AGPL-3.0 |
| **[Obsidian](https://github.com/obsidianmd/obsidian-releases)** | Markdown-based personal knowledge base, widely used by legal professionals | ⭐ 16k | — |

---

## AI Agent Skills for Legal Work

*Open-source skills that teach AI agents (Claude, etc.) to perform specialized legal tasks — from contract review to compliance checks*

> **What are Agent Skills?** Skills are instruction sets that AI agents load dynamically to perform specialized tasks. Learn more at [lawcal.ai/resources/skills](https://lawcal.ai/resources/skills).

### Legal-Specific Skills

*From [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) — Apache-2.0 licensed*

| **Skill** | **What It Does** |
|-----------|------------------|
| **[legal-risk-assessment](https://github.com/anthropics/knowledge-work-plugins/tree/main/legal/skills/legal-risk-assessment)** | Severity × likelihood risk matrix with escalation criteria |
| **[review-contract](https://github.com/anthropics/knowledge-work-plugins/tree/main/legal/skills/review-contract)** | Contract review against negotiation playbook; generates redlines |
| **[triage-nda](https://github.com/anthropics/knowledge-work-plugins/tree/main/legal/skills/triage-nda)** | Rapid NDA triage → GREEN / YELLOW / RED routing |
| **[compliance-check](https://github.com/anthropics/knowledge-work-plugins/tree/main/legal/skills/compliance-check)** | Surfaces applicable regulations and required approvals |
| **[compliance-tracking](https://github.com/anthropics/knowledge-work-plugins/tree/main/operations/skills/compliance-tracking)** | GDPR/CCPA/DPA review, data subject requests, regulatory monitoring |
| **[legal-response](https://github.com/anthropics/knowledge-work-plugins/tree/main/legal/skills/legal-response)** | Templated responses to litigation holds, subpoenas, data requests |
| **[vendor-check](https://github.com/anthropics/knowledge-work-plugins/tree/main/legal/skills/vendor-check)** | Consolidated view of vendor agreements + deadline tracking |
| **[signature-request](https://github.com/anthropics/knowledge-work-plugins/tree/main/legal/skills/signature-request)** | Pre-signature checklist + e-signature routing |
| **[brief](https://github.com/anthropics/knowledge-work-plugins/tree/main/legal/skills/brief)** | Daily legal briefing across email, calendar, and contracts |
| **[meeting-briefing](https://github.com/anthropics/knowledge-work-plugins/tree/main/legal/skills/meeting-briefing)** | Structured pre-meeting briefing for negotiations/compliance reviews |

### Document Processing Skills

*From [anthropics/skills](https://github.com/anthropics/skills)*

| **Skill** | **What It Does** |
|-----------|------------------|
| **[pdf](https://github.com/anthropics/skills/tree/main/skills/pdf)** | Extract text/tables, create, merge/split, and fill PDF forms |
| **[docx](https://github.com/anthropics/skills/tree/main/skills/docx)** | Create, read, edit Word documents with formatting and templates |
| **[pptx](https://github.com/anthropics/skills/tree/main/skills/pptx)** | Create and edit PowerPoint presentations programmatically |
| **[xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx)** | Create, edit, and analyze spreadsheets with formulas and charts |

---

## Datasets & Benchmarks

*High-quality training data and evaluation benchmarks for legal AI development*

| **Dataset** | **Content Type** | **Coverage** | **Scale** | **Best For** |
|-------------|------------------|--------------|-----------|---------------|
| **[Pile of Law](https://github.com/Breakend/PileOfLaw)** 🇺🇸 | Legal/administrative texts | US-centric | ![Large](https://img.shields.io/badge/scale-large-green) | Language model training |
| **[MultiLegalPile](https://huggingface.co/datasets/joelniklaus/Multi_Legal_Pile)** 🌍 | Multilingual legal corpus | 24 languages | ![Massive](https://img.shields.io/badge/scale-massive-darkgreen) | Multilingual models |
| **[LexGLUE](https://github.com/coastalcph/lex-glue)** 🇪🇺🇺🇸 | Multi-task benchmark | EU/US/Multi | ![Medium](https://img.shields.io/badge/scale-medium-blue) | Legal NLU evaluation |
| **[LEXTREME](https://arxiv.org/html/2301.13126v3)** 🌍 | Multilingual legal tasks | 24 languages | ![Large](https://img.shields.io/badge/scale-large-green) | Cross-lingual evaluation |
| **[LegalBench](https://github.com/HazyResearch/legalbench)** | Legal reasoning tasks | Global | ![Comprehensive](https://img.shields.io/badge/scale-comprehensive-purple) | LLM legal reasoning |
| **[LegalBench-RAG](https://github.com/zeroentropy-ai/legalbenchrag)** | Contract retrieval benchmark | Global | ![Focused](https://img.shields.io/badge/scale-focused-orange) | RAG system evaluation |
| **[CUAD](https://github.com/TheAtticusProject/cuad)** | Contract clause annotations | Global | ![Specialized](https://img.shields.io/badge/scale-specialized-lightblue) | Contract understanding |
| **[CaseHOLD](https://github.com/reglab/casehold)** 🇺🇸 | Case holdings analysis | United States | ![Targeted](https://img.shields.io/badge/scale-targeted-yellow) | Legal reasoning |
| **[ivrit.ai datasets](https://github.com/ivrit-ai/ivrit.ai)** 🇮🇱 | Hebrew speech dataset creation platform | Israel | ![Platform](https://img.shields.io/badge/type-platform-orange) | Hebrew model training |
| **[crowd-transcribe-v5](https://huggingface.co/datasets/ivrit-ai/crowd-transcribe-v5)** 🇮🇱 | Hebrew speech dataset with 388 hours transcribed data | Israel | ![Large](https://img.shields.io/badge/scale-large-green) | Hebrew speech models |

---

## General-Purpose Document Intelligence (useful for legal)

*Not legal-specific, but widely used in legal AI pipelines for document processing*

| **Project** | **Specialty** | **Input Types** | **Performance** |
|-------------|---------------|-----------------|-----------------|
| **[GROBID](https://github.com/kermitt2/grobid)** | ML extraction of document structure | PDF → TEI/XML | ![High](https://img.shields.io/badge/accuracy-high-green) |
| **[Unstructured](https://github.com/Unstructured-IO/unstructured)** | Pre-processing for RAG pipelines | PDF/Office/HTML | ![Versatile](https://img.shields.io/badge/type-versatile-blue) |
| **[Layout Parser](https://github.com/Layout-Parser/layout-parser)** | Deep learning layout detection | Multi-format | ![Advanced](https://img.shields.io/badge/tech-advanced-purple) |
| **[Nougat](https://github.com/facebookresearch/nougat)** | Neural OCR for academic documents | Academic PDFs | ![Specialized](https://img.shields.io/badge/focus-specialized-orange) |
| **[Marker](https://github.com/datalab-to/marker)** | Fast PDF to Markdown conversion | PDF | ![Fast](https://img.shields.io/badge/speed-fast-brightgreen) |
| **[Docling](https://github.com/docling-project/docling)** | Modern document parsing | PDF/DOCX/PPTX/HTML | ![Modern](https://img.shields.io/badge/approach-modern-lightgreen) |

---

## Learning, Communities & Curations

*Essential communities and learning resources for legal AI professionals*

| **Resource** | **Focus** | **Link** | **Activity Level** |
|--------------|-----------|----------|--------------------|
| **[Free Law Project](https://github.com/freelawproject)** | Open legal data ecosystem | GitHub Org | ![Very Active](https://img.shields.io/badge/activity-very_active-brightgreen) |
| **[Awesome Legal NLP](https://github.com/maastrichtlawtech/awesome-legal-nlp)** | Curated academic research | GitHub | ![Active](https://img.shields.io/badge/activity-active-green) |
| **[Legal ML Datasets](https://github.com/neelguha/legal-ml-datasets)** | Comprehensive legal ML datasets collection | GitHub | ![Active](https://img.shields.io/badge/activity-active-green) |
| **[Awesome Legal Data](https://github.com/openlegaldata/awesome-legal-data)** | Curated open-source tools for the legal industry | GitHub | ![Active](https://img.shields.io/badge/activity-active-green) |
| **[Stanford CodeX FutureLaw](https://law.stanford.edu/codex-the-stanford-center-for-legal-informatics/)** | Annual legal tech conference from Stanford Law | Website | ![Annual](https://img.shields.io/badge/activity-annual-orange) |
| **[EOLE Conference](https://eolevent.eu)** 🇪🇺 | European Open Source & Free Software Law Event | Website | ![Annual](https://img.shields.io/badge/activity-annual-orange) |

---

## Contributing

We'd love your help making this list even better! Here's how to contribute:

### Submission Guidelines

**Must Have:**
- Open-source with OSI-approved license
- Clear documentation and README
- Active maintenance (commits within 12 months)
- Clear relevance to legal workflows

**Nice to Have:**
- Community adoption (GitHub stars)
- Production usage examples
- Testing and CI/CD
- Performance benchmarks

### How to Submit

1. **Fork** this repository
2. **Add** your project in the appropriate section (alphabetical order)
3. **Include**: Name, one-line description, primary link(s), jurisdiction flag if applicable
4. **Test** your links and formatting
5. **Submit** a pull request with a clear description

### Optional Quality Checks

```bash
# Link checker
npx lychee --no-progress --accept 200,999 README.md

# Awesome list linter  
npx awesome-lint
```

---

## Curation Policy

| **We Include** | **We Exclude** |
|----------------|----------------|
| Open-source projects only | Closed-source SaaS platforms |
| Global scope (jurisdiction-tagged) | Internal/private tools |
| Production-ready tools | Abandoned experimental repos |
| High-value datasets/benchmarks | Low-quality or duplicate data |
| Active, reputable communities | Inactive or harmful communities |

**Quality First:** We prioritize well-maintained projects with good documentation and real-world usage over comprehensive coverage.

---

## License

<div align="center">

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

**CC0 1.0 Universal** – No rights reserved. 

*Feel free to copy, remix, and build upon this list.*

`By contributing, you agree to license your contribution under CC0.`

</div>

---

<div align="center">

### **Credits**

**Curated by [Chen Friedman](https://www.linkedin.com/in/chenfriedman/)**  
**Powered by [Lawcal AI](https://lawcal.ai)**

---

**Star this repo if you found it helpful!**

[![GitHub Stars](https://img.shields.io/github/stars/chen-friedman/awesome-legaltech?style=for-the-badge&logo=github)](https://github.com/chen-friedman/awesome-legaltech/stargazers)

**Made with ❤️ for the legal tech community**

</div>
