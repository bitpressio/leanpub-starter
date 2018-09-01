# leanpub-starter

Starter repo for Leanpub book manuscripts.

## Overview

The `manuscript/Book.txt` file is the entrypoint to generating the book files (PDF, ePub, Mobi). Think of it as the index that imports other files. To keep the book manuscript tidy, this starter projects breaks up the book into individual chapters and other sections.

Here's a brief overview of each file, and you can remove/add files to organize your book in the way you prefer:

* frontmatter.txt - Starts the [{frontmatter}](leanpub-auto-front-matter-main-matter-and-back-matter) portion of the book
* introduction.md - An example file within the frontmatter portion of the book
* mainmatter.txt - Divides the frontmatter from the `{mainmatter}` part of the book
* chapter01.md - The main matter sections of the book
* chapter02.md
* chapter03.md
* chapter04.md
* chapter05.md
* chapter06.md
* chapter07.md
* chapter08.md
* backmatter.txt - Ends the `{mainmatter}` part of the book and starts the `{backmatter}`
* conclusion.md - An example file witin the backmatter of the book

The `frontmatter.txt`, `mainmatter.txt`, and `backmatter.txt` files only contain their respective "instruction", because I've found that it's easy to see the division from the Book.txt file instead of hunting for the part in one of the many other files.

## Sample.txt

The `Sample.txt` file contains the material that will be available if the user downloads a sample of the book or reads the sample online. You can include any part of the book that you want to be made freely available in the sample.
