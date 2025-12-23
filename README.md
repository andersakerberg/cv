# CV Generation

This repository contains my CV in Markdown format with scripts to generate PDF and DOCX versions.

## Prerequisites

- Node.js (v14 or higher)
- npm or npx

## Generating PDF

To generate a PDF from the Markdown file:

```bash
npx --yes md-to-pdf CV.md
```

This will create `CV.pdf` in the same directory.

## Generating DOCX

To generate a DOCX (Word) file from the Markdown file:

```bash
npx --yes markdown-docx -i CV.md -o CV.docx
```

This will create `CV.docx` in the same directory.

## Files

- `CV.md` - Source Markdown file
- `CV.pdf` - Generated PDF (run `npx --yes md-to-pdf CV.md` to regenerate)
- `CV.docx` - Generated DOCX (run `npx --yes markdown-docx -i CV.md -o CV.docx` to regenerate)
- `image.png` - Profile picture

## Quick Commands

**Generate both PDF and DOCX:**
```bash
npx --yes md-to-pdf CV.md && npx --yes markdown-docx -i CV.md -o CV.docx
```

