# $\LaTeX$-templates <!-- omit from toc -->

- [What it is](#what-it-is)
- [How to use it](#how-to-use-it)
    - [`templates` directory](#templates-directory)
    - [`images` directory](#images-directory)
    - [`packages` directory](#packages-directory)
    - [`packages.sty` file](#packagessty-file)
    - [`biblatex-styles` directory](#biblatex-styles-directory)

## What it is

This repository contains my $\LaTeX$ templates. Inspired by hundreds of config snippets people freely shared online and shortcuts I found while learning $\LaTeX$, this repo has been slowly built over time. Everything was modified to fit my needs.

## How to use it

### `templates` directory

The `templates` directory contains the following sub-directories:

-   `basic`: The main template, it should be used for most things
-   `invoice`: A template used to create an invoice for a client
-   `mla`: A MLA template
-   `apa`: An APA template
-   `cse`: A CSE template

These template directories contain a main `template.tex` file. This is the file **you should copy somewhere else** and use for your project.

The directories **may** also contain the following files. You should not move them and probably won't need to modify them.

-   `environment.tex`
    -   This file contains custom functions, environments, variables and package settings. It was inspired by hundreds of config snippets people freely shared online and shortcuts I found while learning $\LaTeX$. It was modified to fit my needs. **You probably should explore this file to see what is available.**
-   `title_page_XXX.tex`
    -   The files with this name are title pages. You may modify them or create new ones to suit your needs, but leave them in this directory. You will be able to import them through the `template.tex` file you copied for your project.
-   `page_settings.tex`
    -   This file contains settings such as line spread, text width, margins, footers, headers, etc.
-   `packages.sty`
    -   This file only exists if there is a need to override the default `packages.sty` placed at the root of the repository for compatibility. It is a list of imports used in the other files of the template.

The `basic` template also contains an extra `template_notes.tex` which is a simpler and smaller version of its main `template.tex`.

### `images` directory

This directory contains the images required by other template files of the repo. For example, title pages use a school/institution logo. Therefore, these logos are placed in the `images` directory.

### `packages` directory

This directory contains custom packages that aren't available (to my knowledge) in the main tex distribution.

### `packages.sty` file

This file is placed at the root of the repository and contains the necessary imports for the templates to work.

### `biblatex-styles` directory

This directory contains custom biblatex styles that I have needed in the past. **They might not be working properly.**
