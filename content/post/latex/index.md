---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "LaTeX"
subtitle: "Software system for document preparation"
summary: "Software system for document preparation"
authors: [admin]
tags: []
categories: []
date: 2022-05-08T00:58:58+03:00
lastmod: 2022-05-08T00:58:58+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---


# Overview
<hr>

LaTeX is a software system for document preparation. When writing, the writer uses plain text as opposed to the formatted text found in "What You See Is What You Get" word processors like Microsoft Word, LibreOffice Writer and Apple Pages. The writer uses markup tagging conventions to define the general structure of a document to stylise text throughout a document (such as bold and italics), and to add citations and cross-references. A TeX distribution such as TeX Live or MiKTeX is used to produce an output file (such as PDF or DVI) suitable for printing or digital distribution.

LaTeX is widely used in academiafor the communication and publication of scientific documents in many fields, including mathematics, computer science, engineering, physics, chemistry, economics, linguistics, quantitative psychology, philosophy, and political science. It also has a prominent role in the preparation and publication of books and articles that contain complex multilingual materials, such as Sanskrit and Greek. LaTeX uses the TeX typesetting program for formatting its output, and is itself written in the TeX macro language.

LaTeX can be used as a standalone document preparation system, or as an intermediate format. In the latter role, for example, it is sometimes used as part of a pipeline for translating DocBook and other XML-based formats to PDF. The typesetting system offers programmable desktop publishing features and extensive facilities for automating most aspects of typesetting and desktop publishing, including numbering and cross-referencing of tables and figures, chapter and section headings, the inclusion of graphics, page layout, indexing and bibliographies.

Like TeX, LaTeX started as a writing tool for mathematicians and computer scientists, but even from early in its development, it has also been taken up by scholars who needed to write documents that include complex math expressions or non-Latin scripts,such as Arabic, Devanagari and Chinese.

LaTeX is intended to provide a high-level, descriptive markup language that accesses the power of TeX in an easier way for writers. In essence, TeX handles the layout side, while LaTeX handles the content side for document processing. LaTeX comprises a collection of TeX macros and a program to process LaTeX documents, and because the plain TeX formatting commands are elementary, it provides authors with ready-made commands for formatting and layout requirements such as chapter headings, footnotes, cross-references and bibliographies.

LaTeX was originally written in the early 1980s by Leslie Lamport at SRI International. The current version is LaTeX2e (stylised as LATEX2ε), released in 1994, but updated in 2020. LaTeX3 (LATEX3) has been under long-term development since the early 1990s. LaTeX is free software and is distributed under the LaTeX Project Public License (LPPL).

# Typesetting system
<hr>

LaTeX attempts to follow the design philosophy of separating presentation from content, so that authors can focus on the content of what they are writing without attending simultaneously to its visual appearance. In preparing a LaTeX document, the author specifies the logical structure using simple, familiar concepts such as chapter, section, table, figure, etc., and lets the LaTeX system handle the formatting and layout of these structures. As a result, it encourages the separation of the layout from the content — while still allowing manual typesetting adjustments whenever needed. This concept is similar to the mechanism by which many word processors allow styles to be defined globally for an entire document, or the use of Cascading Style Sheets in styling HTML documents.

The LaTeX system is a markup language that handles typesetting and rendering, and can be arbitrarily extended by using the underlying macro language to develop custom macros such as new environments and commands. Such macros are often collected into packages, which could then be made available to address some specific typesetting needs such as the formatting of complex mathematical expressions or graphics (e.g., the use of the align environment provided by the amsmath package to produce aligned equations).

In order to create a document in LaTeX, you first write a file, say document.tex, using your preferred text editor. Then you give your document.tex file as input to the TeX program (with the LaTeX macros loaded), which prompts TeX to write out a file suitable for onscreen viewing or printing. This write-format-preview cycle is one of the chief ways in which working with LaTeX differs from the What-You-See-Is-What-You-Get (WYSIWYG) style of document editing. It is similar to the code-compile-execute cycle known to computer programmers. Today, many LaTeX-aware editing programs make this cycle a simple matter through the pressing of a single key, while showing the output preview on the screen beside the input window. Some online LaTeX editors even automatically refresh the preview, while other online tools provide incremental editing in-place, mixed in with the preview in a streamlined single window.

# History
<hr>

LaTeX was created in the early 1980s by Leslie Lamport, when he was working at SRI. He needed to write TeX macros for his own use, and thought that with a little extra effort he could make a general package usable by others. Peter Gordon, an editor at Addison-Wesley, convinced him to write a LaTeX user's manual for publication (Lamport was initially skeptical that anyone would pay money for it); it came out in 1986 and sold hundreds of thousands of copies. Meanwhile, Lamport released versions of his LaTeX macros in 1984 and 1985. On 21 August 1989, at a TeX Users Group (TUG) meeting at Stanford, Lamport agreed to turn over maintenance and development of LaTeX to Frank Mittelbach. Mittelbach, along with Chris Rowley and Rainer Schöpf, formed the LaTeX3 team; in 1994, they released LaTeX2e, the current standard version. LaTeX3 itself has since been cancelled with version features intended for that version being back-ported to LaTeX 2e since 2018.