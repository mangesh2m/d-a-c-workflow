## Introduction

With the rise of the docs-as-code approach to documentation, Markdown has proven to be an essential backbone of the toolchain. It enables both developers and technical writers to contribute to documentation without requiring complex tags, formatting, or specialized authoring tools.

### What is Markdown?

Markdown is a lightweight **markup language** created by **John Gruber** that lets you focus squarely on creating content, without getting bogged down by the complex syntax typically found in other markup languages like HTML or XML. The simple syntax of Markdown is easy to remember and quickly becomes second nature with minimal practice.

Below is a summary of the most-used Markdown syntax, which also includes select GitHub-flavored Markdown (GFM) additions:

## Markdown Cheat Sheet

### Styling

1. Using one asterisk (`*`) or underscore (`_`) before and after content renders it in italics (e.g., *italic*); whereas using two renders it bold (e.g., **bold**). You can also _combine_ these two for ***super important*** phrases!

2. Starting a line with a greater-than sign (`>`) renders it as a **blockquote**.
   > A quote here

3. Using double tildes (`~~`) before and after content renders it as ~~crossed-out text~~.

### Lists

Lists can be ordered and unordered.

I. For **ordered** lists, simply use a number followed by a period (`.`) and a space at the start of a list item. It usually doesn't matter _which_ number you use preceding it (e.g., 1., 5.), since Markdown will automatically assign consecutive numbers in the final output.

   |Input|Output|
   |---|---|
  |<pre><code>1. First item&#x0A;5. Second item&#x0A;8. Third item</code></pre>| 1. First item<br>2. Second item<br>3. Third item|

> [!NOTE]
> Markdown natively does NOT support formatting of text like you see in the table above, so I have embedded raw HTML tags to achieve the desired appearance.
  

   
II. For **unordered** lists, use any of these characters preceding the list items :  (`+`), (`-`), or (`*`)






   
