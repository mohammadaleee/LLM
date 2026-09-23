# PDF Information Extraction using LLM

## Description

This project uses Large Language Models (LLMs) to extract structured information from PDF documents.

The system can be adapted to different types of documents and different information extraction tasks by changing the requested fields.

## Possible Use Cases

* 📄 Academic papers — title, authors, university, methodology
* 📑 Research proposals — author, professor, university, proposal title
* 📋 Reports — dates, organizations, results, key information
* 📜 Resumes/CVs — name, skills, education, experience
* 🧾 Invoices — invoice number, date, company, prices
* 📚 General documents — any user-defined fields

## Features

* PDF text extraction
* LLM-based information extraction
* Structured JSON output
* Regex-based JSON extraction
* SQLite database storage
* Customizable extraction fields

## Technologies

* Python
* PyPDF
* OpenRouter / LLM API
* JSON
* Regex
* SQLite

## Pipeline

PDF → Text Extraction → LLM → JSON → SQLite



## Example Use Case

For an academic proposal PDF, the system can extract information such as:

* Author name
* Professor name
* University name
* Proposal title

The extracted information can then be stored in a SQLite database for further processing and retrieval.
