# CV Generation

This repository contains my CV in Markdown format with scripts to generate PDF and DOCX versions.

## Prerequisites

- Node.js (v14 or higher)
- npm or npx

## Generating PDF

To generate a PDF from the Markdown file:

```bash
npx --yes md-to-pdf "Anders Akerberg - Senior Fullstack Developer and DevOps Engineer.md"
```

This will create `Anders Akerberg - Senior Fullstack Developer and DevOps Engineer.pdf` in the same directory.

## Generating DOCX

To generate a DOCX (Word) file from the Markdown file:

```bash
npx --yes markdown-docx -i "Anders Akerberg - Senior Fullstack Developer and DevOps Engineer.md" -o "Anders Akerberg - Senior Fullstack Developer and DevOps Engineer.docx"
```

This will create `Anders Akerberg - Senior Fullstack Developer and DevOps Engineer.docx` in the same directory.

## Files

- `Anders Akerberg - Senior Fullstack Developer and DevOps Engineer.md` - Source Markdown file
- `Anders Akerberg - Senior Fullstack Developer and DevOps Engineer.pdf` - Generated PDF
- `Anders Akerberg - Senior Fullstack Developer and DevOps Engineer.docx` - Generated DOCX
- `image.png` - Profile picture

## Quick Commands

**Generate both PDF and DOCX:**
```bash
npx --yes md-to-pdf "Anders Akerberg - Senior Fullstack Developer and DevOps Engineer.md" && npx --yes markdown-docx -i "Anders Akerberg - Senior Fullstack Developer and DevOps Engineer.md" -o "Anders Akerberg - Senior Fullstack Developer and DevOps Engineer.docx"
```

