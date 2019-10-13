# Contributor Guidelines

## TOC
<!-- vscode-markdown-toc -->
1. [Tools](#Tools)
2. [File Structure](#FileStructure)
3. [Titles](#Titles)
4. [Sub Headings](#SubHeadings)
5. [Links](#Links)
6. [Images](#Images)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

---

This is the guidline for contributing to the Alaska Developers Alliance repository.

Markdown documents are used for generating our static Gatsby JS site.

## 1. <a name='Tools'></a>Tools

1. VSCode for markdown editing.
    * shift + command + v to live preview a markdown file
2. For Markdown reference check out https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet.
3. [Markdown Lint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) by David Anson is what we use to adhere to good standards and has a convenient VSCode plugin.
4. [Markdown TOC](https://marketplace.visualstudio.com/items?itemName=joffreykern.markdown-toc) plugin to automatically generate a TOC for us.
    * Generating
        1. Create your properly indented headers.
        2. cmd + shift + p to bring up VSCode commands.
        3. type "Generate TOC for Markdown".
    * Regenerating
        1. Delete the previous TOC at the top of the page.
        2. cmd + shift + p to bring up VSCode commands.
        3. type "Generate TOC for Markdown".

## 2. <a name='FileStructure'></a>File Structure

---

    1. Header + description
    2. Table of Contents (use autogen)
    3. Sub items and images

## 3. <a name='Titles'></a>Titles

---

`# Title`

`<space>`

`your description here`

H1 with a blank space after gives us horizontal line.

## 4. <a name='SubHeadings'></a>Sub headings

The # indicates the level of heading. Leave a blank space after the heading to create a horizontal line just like the title.

For instance:

`## h2 heading`

`### h3 heading`

`#### h4 heading`

## 5. <a name='Links'></a>Links

Named Link: `[Dev Alliance](https://akdevalliance.com)`

Link: `https://akdevalliance.com`

## 6. <a name='Images'></a>Images

Images should be place in the  `img/` folder.

`![Codi the Yeti - Alt Text](img/codi.png)`

![Codi the Yeti](img/codi.png)