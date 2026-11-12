# LaTeX Beamer

## Introduction

Beamer is a LaTeX document class used to create professional presentations. It allows users to design slides using LaTeX commands while maintaining consistent formatting and layouts.

## Topics Covered

- **Basic Structure:** Understanding the Beamer document class, preamble, frames, and title page.
- **Presentation Information:** Adding title, subtitle, author, institute, and date.
- **Themes:** Applying predefined themes such as Madrid, Berlin, Warsaw, and CambridgeUS.
- **Color Themes:** Customizing presentation colors using `\usecolortheme{}`.
- **Frames and Slides:** Creating and organizing individual presentation slides.
- **Lists:** Creating bullet points using `itemize` and numbered lists using `enumerate`.
- **Blocks:** Using `block`, `alertblock`, and `exampleblock`.
- **Text Formatting:** Applying bold, italic, font sizes, and text colors.
- **Spacing and Alignment:** Using `\vspace{}`, `\hspace{}`, and `\centering`.
- **Images and Tables:** Inserting images and creating tables within slides.
- **Columns:** Organizing slide content into multiple columns.
- **Slide Customization:** Formatting and arranging content for better presentations.

## Basic Example

```latex
\documentclass{beamer}

\usetheme{Madrid}

\title{My First Presentation}
\author{Your Name}
\institute{MNIT Jaipur}
\date{\today}

\begin{document}

\begin{frame}
    \titlepage
\end{frame}

\begin{frame}{Introduction}
    \begin{itemize}
        \item First Point
        \item Second Point
    \end{itemize}
\end{frame}

\end{document}
```

## Inserting Images

The `graphicx` package is used to insert images into Beamer slides.

```latex
\usepackage{graphicx}

\begin{frame}{Adding an Image}
    \centering
    \includegraphics[width=0.6\textwidth]{image.png}
    \caption{Sample Image}
\end{frame}
```

## Creating Tables

The `tabular` environment is used to create tables inside presentation slides.

```latex
\begin{frame}{Student Details}
    \centering
    \begin{tabular}{|c|c|}
        \hline
        Name & Marks \\
        \hline
        Aman & 90 \\
        Riya & 85 \\
        \hline
    \end{tabular}
\end{frame}
```

## Learning Outcomes

Through this topic, I learned to:

- Create presentations using LaTeX.
- Apply different themes and color schemes.
- Organize content using frames, lists, and blocks.
- Insert images and create tables.
- Use columns and customize slide layouts.
- Format presentation content effectively.

## Conclusion

Beamer provides a flexible way to create structured and professional presentations using LaTeX. It is especially useful for academic presentations, seminars, and technical discussions.