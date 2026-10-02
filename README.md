# Office Skills (Curated Harness Edition)

> Curated collection of high-impact document parsing, OCR, table extraction, Office format conversion, and workflow automation skills for AI agents.

Forked from [claude-office-skills/skills](https://github.com/claude-office-skills/skills), streamlined and curated specifically for technical, fiscal, legal, and operational workflows.

---

## 🚀 Office MCP Server

**39 tools** for Office and document manipulation via Model Context Protocol (MCP).

| Module | Tools | Capabilities |
|--------|-------|--------------|
| **PDF** | 10 | Extract, merge, split, compress, watermark, forms, OCR |
| **Spreadsheet** | 7 | Read/write Excel, analyze, formulas, pivot tables |
| **Document** | 6 | Create/edit Word, templates, merge documents |
| **Conversion** | 9 | xlsx⇔csv, docx⇔md, json→xlsx, batch convert |
| **Presentation** | 7 | Create PPT, extract, Markdown→slides, HTML export |

Located in `mcp-servers/office-mcp`.

```bash
cd mcp-servers/office-mcp
npm install
npm run build
```

---

## 📚 Curated Skills Catalog

### 1. Document Parsing, OCR & Table Extraction
* **`doc-parser`**: IBM Docling document parser for complex layouts and documents.
* **`layout-analyzer`**: Surya layout analyzer for structured document hierarchy and text bounding.
* **`table-extractor`**: Camelot precise table extraction from PDFs to tabular data.
* **`smart-ocr`**: PaddleOCR for dense and rotated text.
* **`pdf-ocr`**: Scanned PDF text extraction via OCR.
* **`pdf-extraction`**: pdfplumber for extracting text, forms, and tables.
* **`pdf-merge-split`**: Merge and split PDF documents.
* **`pdf-converter`**: Convert PDF to/from Word, Excel, and image formats.
* **`pdf-form-filler`**: Fill out interactive PDF forms.
* **`pdf-compress`**: Compress PDF file size without losing readability.
* **`pdf-to-docx`**: Convert PDFs to editable DOCX documents.

### 2. Format Conversion & Bridges
* **`office-to-md`**: Microsoft MarkItDown for converting DOCX, XLSX, and PDF to clean Markdown.
* **`md-to-office`**: Pandoc-based Markdown to Word/PowerPoint/PDF conversion.
* **`batch-convert`**: Pipeline for batch conversion across multiple document formats.

### 3. Core Office Manipulation
* **`xlsx-manipulation`**: Python openpyxl for Excel spreadsheets, formulas, and cells.
* **`docx-manipulation`**: python-docx for Word document editing and template injection.
* **`pptx-manipulation`**: python-pptx for PowerPoint generation.
* **`excel-automation`**: xlwings advanced Excel automation.
* **`official-skills/`**: Official Anthropic guides for DOCX, XLSX, PPTX, and PDF.

### 4. Presentations & Visuals
* **`md-slides`**: Marp Markdown-to-presentation workflows.
* **`dev-slides`**: Slidev Vue-based developer slides.
* **`html-slides`**: reveal.js HTML presentation decks.
* **`html-to-ppt`**: HTML to PowerPoint converter.

### 5. Workflows & Business Automations
* **`trello-automation`**: Trello Kanban boards, lists, cards, and checklist automation.
* **`n8n-workflow`**: Architecture and node templates for n8n workflow pipelines.
* **`whatsapp-automation`**: WhatsApp business messaging and webhook integration patterns.

### 6. Legal & Contract Analysis
* **`contract-review`**: Risk analysis, completeness checklists, and recommendations.
* **`contract-template`**: Smart contract and agreement templates.
* **`nda-generator`**: Non-disclosure agreement generation.

### 7. Reports & Data Analysis
* **`data-analysis`**: Spreadsheet analysis, data profiling, and statistical summaries.
* **`changelog-generator`**: Release notes from Git commits and work logs.
* **`weekly-report`**: Consistent project status summaries.
* **`meeting-notes`**: Structured meeting minutes and action items.

---

## License

MIT License.
