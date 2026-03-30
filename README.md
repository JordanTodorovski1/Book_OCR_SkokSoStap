# Book_OCR_SkokSoStap

This project generates a structured Word document (.docx) from OCR-extracted text.
The final output represents a processed and formatted version of raw text that was originally extracted from images or scanned pages.

The provided file is the final stage of a pipeline that consists of the following steps:

## 1. Image/Input Source
Source content (e.g. scanned pages or images) is used as input.
## 2. OCR Processing
Text is extracted from each page using an OCR system.
Each page is converted into raw text.
## 3. Raw Text Aggregation
All extracted text is stored in a single file (e.g. raw_text.txt).
Pages are separated using markers (e.g. === page_x ===).
## 4. Parsing & Structuring
The raw text is parsed and split into pages.
Each page is mapped into a structured format (dictionary of page → text).
## 5. Document Generation
A Word document is created programmatically.
The system:
applies default formatting (Times New Roman, 12pt)
inserts a title
splits text into paragraphs
adds page breaks between pages
prepares the document for manual editing
## 6. Final Output
