# Awesome-Intelligent-Document-Processing

# Awesome-Intelligent-Document-Processing

## Top Intelligent Document Processing (IDP) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Document Understanding, OCR, Data Extraction, Classification, Invoice/Forms Processing & Automated Capture*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Intelligent Document Processing (IDP)**. These systems use OCR, computer vision, and machine learning to classify documents, extract structured data from invoices, forms, contracts, and unstructured files, and feed downstream business processes.



**Examples** include Rossum, Nanonets, Hyperscience, ABBYY Vantage, Indico Data, Kofax TotalAgility, Ocrolus, Infrrd, Ephesoft, and Docsumo (the category leaders).



**Open-source emphasis**: IDP has a rich open-source ecosystem. **docTR**, **PaddleOCR**, **Unstructured**, LayoutLM-family models, Tesseract-based pipelines, and related tools enable teams to build capable document-understanding systems. Commercial platforms still lead in turnkey accuracy, pre-built document skills, and enterprise workflow. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Rossum](https://rossum.ai/)**  

  AI-native intelligent document processing platform focused on transactional documents with minimal template maintenance and strong extraction accuracy.



- **[Nanonets](https://nanonets.com/)**  

  Cloud IDP and OCR platform offering document classification, data extraction, and workflow automation for invoices, receipts, and custom document types.



- **[Hyperscience](https://www.hyperscience.com/)**  

  Enterprise IDP platform recognized for high automation rates, human-in-the-loop workflows, and large-scale document processing.



- **[ABBYY Vantage](https://www.abbyy.com/)**  

  Established intelligent document processing suite with strong OCR, pre-trained document skills, and enterprise capture capabilities.



- **[Indico Data](https://indicodata.ai/)**  

  Unstructured data and document intelligence platform aimed at complex, variable documents and process automation.



- **[Kofax TotalAgility](https://www.kofax.com/)**  

  Intelligent automation platform combining capture, IDP, and process orchestration for high-volume document workflows.



- **[Ocrolus](https://www.ocrolus.com/)**  

  Document AI platform specialized in financial documents (bank statements, paystubs, tax forms) with human-in-the-loop verification.



- **[Infrrd](https://www.infrrd.ai/)**  

  AI-powered document processing platform for extraction, classification, and automation across varied document types.



- **[Ephesoft](https://ephesoft.com/)**  

  Intelligent document capture and processing solution used for classification, separation, and data extraction in enterprise environments.



- **[Docsumo](https://www.docsumo.com/)**  

  Document AI platform focused on extracting data from invoices, forms, and semi-structured documents with workflow features.



## Open-Source GitHub Projects

- **[docTR (Document Text Recognition)](https://github.com/mindee/doctr)**  

  High-performance open-source deep-learning library for end-to-end OCR (text detection + recognition), actively maintained and widely used in IDP pipelines.



- **[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)**  

  Comprehensive open-source OCR toolkit supporting multilingual text detection, recognition, and document analysis with strong practical performance.



- **[Unstructured](https://github.com/Unstructured-IO/unstructured)**  

  Open-source library for extracting clean, structured content from PDFs, images, and office documents—popular in RAG and document pipelines.



- **[LayoutLM / LayoutLMv3 and document AI models](https://github.com/microsoft/unilm)**  

  Foundation models for document understanding (layout + text) that power many open and commercial IDP systems.



- **[Tesseract OCR](https://github.com/tesseract-ocr/tesseract)**  

  Classic open-source OCR engine still widely used as a baseline or component in document processing pipelines.



- **[EasyOCR](https://github.com/JaidedAI/EasyOCR)**  

  Ready-to-use open-source OCR module supporting many languages with a simple Python interface.



- **[MMOCR](https://github.com/open-mmlab/mmocr)**  

  OpenMMLab toolbox for text detection, recognition, and other OCR-related tasks based on PyTorch.



- **[Donut / OCR-free document understanding models](https://github.com/)**  

  Transformer-based approaches that parse documents with less reliance on traditional OCR pipelines.



- **[Label Studio and open annotation tools](https://github.com/HumanSignal/label-studio)**  

  Open-source data labeling platforms used to create training sets for custom document extraction models.



- **[Apache PDFBox / open PDF parsing libraries](https://github.com/apache/pdfbox)**  

  Open libraries for extracting text and structure from born-digital PDFs as part of hybrid IDP workflows.



### Additional Strong Open-Source Options

- Building extraction pipelines with **docTR or PaddleOCR + LayoutLM-family models** for custom document types.

- Using **Unstructured** to feed clean document chunks into LLM or rules-based downstream systems.

- Combining open OCR with open annotation tools to train domain-specific extractors.

- Accepting that enterprise pre-built document skills, validated accuracy SLAs, human-in-the-loop orchestration, and turnkey compliance still favor commercial platforms (Rossum, Hyperscience, ABBYY, Nanonets, Kofax, Ocrolus, etc.).

- Focusing open-source efforts on data ownership, cost control, and specialized document types.



**Frameworks for building custom systems**: Ingest documents → run OCR/layout models (docTR, PaddleOCR, LayoutLM) → extract fields with rules or fine-tuned models → validate with human review → export to ERP/CRM. Suitable for teams with ML and engineering capacity. Many enterprises still adopt commercial IDP platforms for speed, support, and out-of-the-box document coverage.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Document processing often involves sensitive personal or financial data. Open-source deployments require proper security, access controls, and compliance with privacy regulations. Accuracy of extraction should be validated for each use case. This list is not legal or compliance advice.



---

**Made for automation engineers, data teams, and operations leaders processing documents at scale.**

Let's keep document intelligence accurate, transparent, and as open as practical.
