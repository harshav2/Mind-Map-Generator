# Mind Map Generator for PDF Files

## Project Overview

The **Mind Map Generator** is a Python-based tool that automatically creates mind maps from PDF documents. It extracts text from PDFs, processes the content using large language models (LLMs), and generates a visual mind map representing key concepts and their relationships. This tool is ideal for students, researchers, and professionals who want to quickly visualize the content of large documents.

## Features

- PDF text extraction with structure preservation
- Concept analysis using advanced NLP techniques
- Automated mind map generation and visualization
- Customizable mind map appearance and structure

## How It Works

1. **PDF Text Extraction**: Uses pdfminer.six to extract text while preserving document structure.
2. **Concept Analysis**: Employs LangChain and sentence-transformers to identify key concepts and relationships.
3. **Mind Map Generation**: Utilizes matplotlib to create a visual representation of the analyzed concepts.

## Limitations

- Large PDFs may require significant processing time.
- Highly technical or specialized content may require fine-tuning of the LLM models.
- The quality of the mind map depends on the structure and clarity of the input PDF.
- The current UI for the mind map visualization may not be very readable, especially for complex or dense content.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
