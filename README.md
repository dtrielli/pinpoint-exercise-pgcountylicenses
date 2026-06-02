# Pinpoint document-mining exercise: Prince George's County Board of License Commissioners

This exercise uses public Prince George's County Board of License Commissioners documents to practice document mining, AI-assisted reporting judgment, and source verification.

You will use Google Pinpoint to search a collection of public PDFs, test several AI-assisted tasks, identify possible leads, and decide what still needs verification before anything could be used in a story pitch.

## What you will practice

By the end of the exercise, you should be able to:

- Search a document collection for people, organizations, locations, license types, rule numbers, and issues.
- Use Pinpoint's Gemini tools without treating the output as automatically true.
- Summarize documents cautiously.
- Extract entities and structured fields from documents.
- Separate document-backed claims from verified facts.
- Turn possible findings into reporting questions.
- Identify what additional reporting would be needed.

## Repository contents

```text
.
├── README.md
├── data/
│   ├── manifest.txt
│   └── pdfs/
├── docs/
│   └── data-source-notes.md
└── exercise/
    ├── student-instructions.md
    ├── student-worksheet.md
    └── submission-template.md
```

## Before you begin

You will need access to Google Pinpoint or to a Pinpoint collection your instructor has already created.

If you are creating your own collection:

1. Open Google Pinpoint.
2. Create a new collection.
3. Upload the PDFs from `data/pdfs/`.
4. Wait for the documents to finish processing.
5. Keep `exercise/student-worksheet.md` open while you work.

## Main idea

Pinpoint can help you find and organize source material. Its Gemini features can also summarize, compare, extract data, label documents, and answer questions about the collection. These tools do not replace reporting.

For every useful result, ask:

- Where is the original document?
- What exactly does the document say?
- Who is making the claim?
- Does the document prove the claim, or only show that someone made it?
- What additional reporting would verify it?

## Suggested Pinpoint workflow

Use the features in this order:

1. **Manual search**: Search the collection for a concrete term, such as an establishment, location, license type, rule number, or hearing type.
2. **Summarize**: Summarize one document or a small group of documents, then check the source.
3. **Extract data**: Pull structured fields such as establishment name, licensee name, address, hearing date, matter type, alleged violation, and source document.
4. **Find answers**: Ask a collection-level question, then check whether the answer is complete and source-backed.
5. **Label documents**: If useful, group documents by type, such as agenda, minutes, administrative voting session, preliminary matters, or regular session.
6. **Story angle**: Turn one possible finding into a reporting question, not a conclusion.

## Deliverable

Complete the worksheet and write one possible story angle as a question, not a conclusion.

Your final answer should include:

- One search term you investigated.
- One document or passage that matters.
- One structured extraction example.
- One claim you would not use without more reporting.
- One possible story angle.
- The next reporting step you would take.

## License information

Original teaching materials in this repository are licensed under CC BY 4.0. Any code is licensed under the MIT License. Source documents in `data/pdfs/` were downloaded from Prince George's County public records pages and are included for educational use with attribution to the original source.
