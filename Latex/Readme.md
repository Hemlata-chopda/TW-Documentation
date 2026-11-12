# LaTeX Documentation

## 1. Introduction

LaTeX is a document preparation system used to create professional academic, scientific, and technical documents. It is particularly useful for mathematical equations, research papers, and reports.

## 2. Basic Document Structure

A LaTeX document consists of a preamble and a document body.

```latex
\documentclass{article}
\usepackage{amsmath}

\begin{document}
Hello World!
\end{document}
```

**Common document classes:** `article`, `report`, `book`, `beamer`.

## 3. Packages

Packages provide additional features and formatting options.

| Package | Purpose |
|---|---|
| `amsmath` | Mathematical equations |
| `amssymb` | Mathematical symbols |
| `graphicx` | Inserting images |
| `xcolor` | Text and background colors |
| `geometry` | Page margins |
| `natbib` | Citations and bibliography |
| `tikz` | Diagrams and graphics |
| `eso-pic` | Background elements |

## 4. Text Formatting and Structure

- Bold, italic, underline and emphasized text.
- Sections, subsections and paragraphs.
- Ordered lists (`enumerate`).
- Unordered lists (`itemize`).
- Line breaks and page breaks.

## 5. Mathematical Expressions

LaTeX supports mathematical expressions in inline and display modes.

Topics covered:
- Fractions and square roots.
- Subscripts and superscripts.
- Greek letters and mathematical symbols.
- Summation, integration and derivatives.
- Aligned and multiline equations.
- Mathematical fonts.

## 6. Matrices and Tables

**Matrices:** `matrix`, `pmatrix`, `bmatrix`, `vmatrix`.

**Tables:** `tabular` environment, horizontal lines, column alignment and combining columns using `\multicolumn`.

## 7. Figures and Images

Using the `graphicx` package to insert and format images.

Important commands:
- `\includegraphics{}`
- `\caption{}`
- `\label{}`
- `\centering`

## 8. Page Formatting

- Page margins using `geometry`.
- Page orientation and numbering.
- Headers and footers.
- Page styles (`plain`, `empty`, `headings`).
- Text and heading colors.
- Watermarks and background elements.

## 9. Document Organization

- Title page and abstract.
- Table of contents using `\tableofcontents`.
- Sections and chapters.
- Cross-referencing using `\label{}`, `\ref{}` and `\pageref{}`.

## 10. Reports and Bibliography

Creating structured academic reports using the `report` document class.

Bibliography and citation management:
- `\cite{}`
- `\citet{}`
- `\citep{}`
- `\bibliographystyle{}`
- `\bibliography{}`
- `.bib` files for storing references.
- Bibliography styles such as `plain` and `agu`.

## 11. Beamer Presentations

Creating presentations using LaTeX Beamer.

Topics covered:
- Title pages and frames.
- Themes and color themes.
- Bullet points and numbered lists.
- Blocks and slide formatting.
- Spacing and colors.

## 12. Learning Outcomes

Through this course, I learned to:

- Create structured technical documents.
- Format text, equations, matrices and tables.
- Insert images and customize page layouts.
- Prepare academic reports.
- Manage references and citations.
- Add watermarks and background elements.
- Create presentations using Beamer.

## 13. Conclusion

LaTeX provides an effective way to prepare professional technical and academic documents. This repository contains my learning notes, examples, and practical work completed during the Technical Writing course.