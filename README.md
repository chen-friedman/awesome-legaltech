# Awesome Legal AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![GitHub Stars](https://img.shields.io/github/stars/chen-friedman/awesome-legaltech?style=social)](https://github.com/chen-friedman/awesome-legaltech) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

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

**Quality-First Curation** → Only actively maintained, production-ready projects  
**Global Coverage** → Worldwide scope with jurisdiction-specific tagging (🇺🇸 🇪🇺 🇬🇧 🇩🇪 🇮🇳)  
**Production Focus** → Real-world tools that legal professionals actually use  
**Rich Datasets** → High-value benchmarks and training data for AI development  
**Active Communities** → Thriving ecosystems and collaborative projects  

> **New to Legal AI?** Start with our [Quick Start Guide](#quick-start-guide) below!

---

## Table of Contents

| **Quick Navigation** | **Count** | **Best For** |
|----------------------|-----------|--------------|
| [NLP Libraries & Domain Models](#nlp-libraries--domain-models) | 6 projects | Text processing & analysis |
| [AI-Powered Contract & Document Analytics](#ai-powered-contract--document-analytics) | 5 platforms | Contract intelligence |
| [Legal Research & Case Law Data/APIs](#legal-research--case-law-dataapis) | 6 resources | Research & citations |
| [E-Discovery & Litigation](#e-discovery--litigation) | 3 tools | Legal discovery |
| [Speech Recognition & Transcription](#speech-recognition--transcription) | 8 tools | Audio/video transcription |
| [Document Signing & Collaboration](#document-signing--collaboration) | 3 platforms | Digital signatures & wikis |
| [Document Management, OCR & PDF](#document-management-ocr--pdf) | 9 solutions | Document processing |
| [Document Assembly & Rules-as-Code](#document-assembly--rules-as-code) | 4 platforms | Automation & workflows |
| [Datasets & Benchmarks](#datasets--benchmarks) | 8 collections | Training & evaluation |
| [General-Purpose Document Intelligence](#general-purpose-document-intelligence-useful-for-legal) | 6 tools | Document understanding |
| [Learning, Communities & Curations](#learning-communities--curations) | 2 communities | Education & networking |

**Total: 60+ High-Quality Open-Source Legal Tech Resources**

---

## Quick Start Guide

### For Legal Professionals
1. **Start with**: [AI-Powered Contract Analytics](#ai-powered-contract--document-analytics) for document review
2. **Research tools**: [Legal Research & Case Law APIs](#legal-research--case-law-dataapis) for case discovery
3. **Document processing**: [Document Management & OCR](#document-management-ocr--pdf) for digitization

### For Developers
1. **Begin with**: [NLP Libraries & Models](#nlp-libraries--domain-models) for text processing
2. **Training data**: [Datasets & Benchmarks](#datasets--benchmarks) for model development  
3. **Infrastructure**: [Document Intelligence](#general-purpose-document-intelligence-useful-for-legal) for pipelines

### For Organizations
1. **Enterprise solutions**: [OpenContracts](https://github.com/JSv4/OpenContracts) for contract analytics
2. **Document workflows**: [docassemble](https://github.com/jhpyle/docassemble) for automation
3. **Case management**: [CourtListener](https://github.com/freelawproject/courtlistener) for legal data

---

## NLP Libraries & Domain Models

*Essential tools for processing and understanding legal text with specialized language models*

| **Project** | **Focus** | **Scope** | **Status** |
|-------------|-----------|-----------|------------|
| **[LexNLP](https://github.com/LexPredict/lexpredict-lexnlp)** | Information extraction from unstructured legal text (Python) | Global | ![Active](https://img.shields.io/badge/status-active-green) |
| **[Blackstone](https://github.com/ICLRandD/Blackstone)** | spaCy pipeline for long-form legal text processing | Global | ![Active](https://img.shields.io/badge/status-active-green) |
| **[LEGAL-BERT](https://huggingface.co/nlpaueb/legal-bert-base-uncased)** | Pretrained BERT variants for legal corpora (contracts, ECHR, EU law) | EU/Global | ![Stable](https://img.shields.io/badge/status-stable-blue) |
| **[InLegalBERT](https://github.com/Law-AI/pretraining-bert)** 🇮🇳 | BERT models and recipes for Indian law corpora | India | ![Active](https://img.shields.io/badge/status-active-green) |
| **[CaseHOLD](https://github.com/reglab/casehold)** | Tasks and baselines for case-law holdings analysis | Global | ![Research](https://img.shields.io/badge/status-research-orange) |
| **[LeXLMs](https://github.com/coastalcph/lexlms)** | Corpora and probing tasks for legal language models | Multilingual | ![Research](https://img.shields.io/badge/status-research-orange) |

---

## AI-Powered Contract & Document Analytics

*Enterprise-grade platforms for intelligent contract analysis and document understanding*

| **Project** | **Features** | **Best For** | **Maturity** |
|-------------|--------------|--------------|--------------|
| **[OpenContracts](https://github.com/JSv4/OpenContracts)** | Enterprise document analytics with AI-powered analysis (GPL-3) | Large organizations | ![Enterprise](https://img.shields.io/badge/maturity-enterprise-darkgreen) |
| **[ContraxSuite](https://github.com/LexPredict/lexpredict-contraxsuite)** | Full contract analytics & document platform (AGPL) | Commercial use | ![Production](https://img.shields.io/badge/maturity-production-green) |
| **[LawGlance](https://github.com/lawglance/lawglance)** | Free, open-source RAG-based AI legal assistant | SME & individuals | ![Community](https://img.shields.io/badge/maturity-community-blue) |
| **[OpenEDGAR](https://github.com/LexPredict/openedgar)** 🇺🇸 | Framework for searchable EDGAR filings databases | US Securities | ![Stable](https://img.shields.io/badge/maturity-stable-lightblue) |
| **[CUAD Tools](https://github.com/TheAtticusProject/cuad)** | Code and data interfaces for Contract Understanding | Research | ![Research](https://img.shields.io/badge/maturity-research-orange) |

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

---

## E-Discovery & Litigation

*Specialized tools for legal discovery, document review, and litigation support*

| **Project** | **Capabilities** | **Use Case** | **License** |
|-------------|------------------|--------------|-------------|
| **[FreeEed](https://github.com/shmsoft/FreeEed)** | Complete eDiscovery processing (OCR, indexing, metadata) | Large-scale discovery | ![Open Source](https://img.shields.io/badge/license-Apache-blue) |
| **[FreeDiscovery](https://github.com/FreeDiscovery/FreeDiscovery)** | Information retrieval engine based on scikit-learn | Document analysis | ![Open Source](https://img.shields.io/badge/license-BSD-green) |
| **[FOIAMachine](https://github.com/cirlabs/foiamachine)** 🇺🇸 | Manage and send FOIA requests with agency directory | Government transparency | ![Open Source](https://img.shields.io/badge/license-MIT-lightblue) |

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

---

## Document Signing & Collaboration

*Platforms for digital document signing and collaborative documentation*

| **Project** | **Primary Use** | **Best For** | **License** |
|-------------|-----------------|--------------|-------------|
| **[Documenso](https://github.com/documenso/documenso)** | Open-source DocuSign alternative | Digital signatures | ![AGPL](https://img.shields.io/badge/license-AGPL-blue) |
| **[DocuSeal](https://github.com/docusealco/docuseal)** | Document filling and signing platform | PDF forms & signatures | ![AGPL](https://img.shields.io/badge/license-AGPL-blue) |
| **[Docmost](https://github.com/docmost/docmost)** | Collaborative wiki and documentation software | Team documentation | ![AGPL](https://img.shields.io/badge/license-AGPL-blue) |

---

## Document Management, OCR & PDF

*Essential tools for document digitization, management, and processing workflows*

| **Project** | **Core Function** | **Performance** | **Special Features** |
|-------------|-------------------|-----------------|---------------------|
| **[paperless-ngx](https://github.com/paperless-ngx/paperless-ngx)** | Self-hosted document management system | ![High](https://img.shields.io/badge/performance-high-green) | Searchable archive, AI tagging |
| **[Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)** | Local web-based PDF toolbox | ![Fast](https://img.shields.io/badge/performance-fast-brightgreen) | Split/merge/convert/optimize |
| **[OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF)** | Add OCR text layer to scanned PDFs | ![Reliable](https://img.shields.io/badge/performance-reliable-blue) | Searchable PDF/A output |
| **[Paperless-AI](https://github.com/clusterzx/paperless-ai)** | AI addon for paperless-ngx | ![Smart](https://img.shields.io/badge/performance-smart-purple) | Semantic search, auto-classification |
| **[paperless-gpt](https://github.com/icereed/paperless-gpt)** | ChatGPT integration for paperless-ngx | ![AI](https://img.shields.io/badge/feature-AI_chat-orange) | Document Q&A, AI assistance |
| **[Tesseract](https://github.com/tesseract-ocr/tesseract)** | Industry-standard OCR engine | ![Standard](https://img.shields.io/badge/status-industry_standard-darkgreen) | Text recognition, 100+ languages |
| **[EasyOCR](https://github.com/JaidedAI/EasyOCR)** | Ready-to-use OCR with 80+ languages | ![Easy](https://img.shields.io/badge/usability-easy-brightgreen) | Quick text extraction |
| **[markitdown](https://github.com/microsoft/markitdown)** | Convert documents to Markdown | ![Convert](https://img.shields.io/badge/feature-conversion-lightblue) | PDF/DOCX/PPTX to Markdown |
| **[ExifTool](https://github.com/exiftool/exiftool)** | Read/write metadata in files | ![Metadata](https://img.shields.io/badge/focus-metadata-purple) | Digital evidence analysis |

---

## Document Assembly & Rules-as-Code

*Platforms for automating legal document creation and implementing legal logic*

| **Project** | **Primary Use** | **Target Users** | **Technical Level** |
|-------------|-----------------|------------------|-------------------|
| **[docassemble](https://github.com/jhpyle/docassemble)** | Expert-system platform for guided interviews | Legal professionals | ![Medium](https://img.shields.io/badge/technical-medium-orange) |
| **[AssemblyLine](https://github.com/SuffolkLITLab/docassemble-AssemblyLine)** 🇺🇸 | Court-form automation toolkit | Court systems | ![Low](https://img.shields.io/badge/technical-low-green) |
| **[Blawx](https://github.com/Lexpedite/blawx)** | Visual Rules-as-Code environment | Legal technologists | ![High](https://img.shields.io/badge/technical-high-red) |
| **[Catala](https://github.com/CatalaLang/catala)** | Programming language for statute implementation | Developers | ![High](https://img.shields.io/badge/technical-high-red) |

---

## Datasets & Benchmarks

*High-quality training data and evaluation benchmarks for legal AI development*

| **Dataset** | **Content Type** | **Coverage** | **Scale** | **Best For** |
|-------------|------------------|--------------|-----------|--------------|
| **[Pile of Law](https://github.com/Breakend/PileOfLaw)** 🇺🇸 | Legal/administrative texts | US-centric | ![Large](https://img.shields.io/badge/scale-large-green) | Language model training |
| **[MultiLegalPile](https://huggingface.co/datasets/joelniklaus/Multi_Legal_Pile)** 🌍 | Multilingual legal corpus | 24 languages | ![Massive](https://img.shields.io/badge/scale-massive-darkgreen) | Multilingual models |
| **[LexGLUE](https://github.com/coastalcph/lex-glue)** 🇪🇺🇺🇸 | Multi-task benchmark | EU/US/Multi | ![Medium](https://img.shields.io/badge/scale-medium-blue) | Legal NLU evaluation |
| **[LEXTREME](https://arxiv.org/html/2301.13126v3)** 🌍 | Multilingual legal tasks | 24 languages | ![Large](https://img.shields.io/badge/scale-large-green) | Cross-lingual evaluation |
| **[LegalBench](https://github.com/HazyResearch/legalbench)** | Legal reasoning tasks | Global | ![Comprehensive](https://img.shields.io/badge/scale-comprehensive-purple) | LLM legal reasoning |
| **[LegalBench-RAG](https://github.com/zeroentropy-ai/legalbenchrag)** | Contract retrieval benchmark | Global | ![Focused](https://img.shields.io/badge/scale-focused-orange) | RAG system evaluation |
| **[CUAD](https://github.com/TheAtticusProject/cuad)** | Contract clause annotations | Global | ![Specialized](https://img.shields.io/badge/scale-specialized-lightblue) | Contract understanding |
| **[CaseHOLD](https://github.com/reglab/casehold)** 🇺🇸 | Case holdings analysis | United States | ![Targeted](https://img.shields.io/badge/scale-targeted-yellow) | Legal reasoning |

---

## General-Purpose Document Intelligence (useful for legal)

*Not legal-specific, but widely used in legal AI pipelines for document processing*

| **Project** | **Specialty** | **Input Types** | **Performance** |
|-------------|---------------|-----------------|-----------------|
| **[GROBID](https://github.com/kermitt2/grobid)** | ML extraction of document structure | PDF → TEI/XML | ![High](https://img.shields.io/badge/accuracy-high-green) |
| **[Unstructured](https://github.com/Unstructured-IO/unstructured)** | Pre-processing for RAG pipelines | PDF/Office/HTML | ![Versatile](https://img.shields.io/badge/type-versatile-blue) |
| **[Layout Parser](https://github.com/Layout-Parser/layout-parser)** | Deep learning layout detection | Multi-format | ![Advanced](https://img.shields.io/badge/tech-advanced-purple) |
| **[Docling](https://github.com/docling-project/docling)** | Modern document parsing | PDF/DOCX/PPTX/HTML | ![Modern](https://img.shields.io/badge/approach-modern-lightgreen) |
| **[Nougat](https://github.com/facebookresearch/nougat)** | Neural OCR for academic documents | Academic PDFs | ![Specialized](https://img.shields.io/badge/focus-specialized-orange) |
| **[Marker](https://github.com/datalab-to/marker)** | Fast PDF to Markdown conversion | PDF | ![Fast](https://img.shields.io/badge/speed-fast-brightgreen) |

---

## Learning, Communities & Curations

*Essential communities and learning resources for legal AI professionals*

| **Resource** | **Focus** | **Community Size** | **Activity Level** |
|--------------|-----------|-------------------|-------------------|
| **[Free Law Project](https://github.com/freelawproject)** | Open legal data ecosystem | ![Large](https://img.shields.io/badge/size-large-green) | ![Very Active](https://img.shields.io/badge/activity-very_active-brightgreen) |
| **[Awesome Legal NLP](https://github.com/maastrichtlawtech/awesome-legal-nlp)** | Curated academic research | ![Medium](https://img.shields.io/badge/size-medium-blue) | ![Active](https://img.shields.io/badge/activity-active-green) |

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
**Powered by [Legal Tech Systems](https://legaltech.systems)**

---

**Star this repo if you found it helpful!**

[![GitHub Stars](https://img.shields.io/github/stars/chen-friedman/awesome-legaltech?style=for-the-badge&logo=github)](https://github.com/chen-friedman/awesome-legaltech/stargazers)

**Made with ❤️ for the legal tech community**

</div>
