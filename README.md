# Word Document Enhancer

**Improve document content and return a Word file, without the copy-paste relay.**

## The problem

Copy a document into an AI chat. Ask for improvements. Copy it back. Repair the headings. Repair the lists. Wonder why this was called a shortcut.

Document Enhancer automates the content-improvement round trip for Word documents.

## The solution

A Python CLI/API that reads a DOCX file, converts its content into Markdown, asks an AI model to improve the writing, and creates an enhanced Word document.

## What it does

- DOCX input and enhanced DOCX output.
- Grammar, clarity, and professionalism improvements.
- Markdown intermediate representation for model processing.
- Handling for headings, lists, and tables.
- Command-line and API entry points.

## Engineering highlights

Connects Word extraction, AI-assisted editing, and document generation through a reusable Python pipeline. CLI and API entry points make the same content-improvement workflow available to individual users and larger document-processing systems.

## Technology

Python, OpenAI integration, DOCX/Markdown conversion, API wrapper.

## Source code

This repository documents the project, its capabilities, and the engineering behind it. The application source code is maintained privately.
