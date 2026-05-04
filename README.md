# jetbrains-writerside-assignment-v1

Sample Writerside documentation project built as part of a JetBrains technical writing assignment.

## What's in here

A single Writerside instance (`Help Instance`) containing a setup guide that walks new writers through:

1. Installing the Writerside plugin in IntelliJ IDEA
2. Creating a new Writerside project
3. Adding a topic
4. Building the docs locally
5. Pushing the source to GitHub

The setup guide is written as a `.topic` XML file rather than Markdown, to make use of Writerside's semantic elements (`<procedure>`, `<step>`, `<chapter>`, `<ui-path>`, `<control>`).

## Project structure

```
Writerside/
  writerside.cfg      Instance and product configuration
  hi.tree             Table of contents for the Help Instance
  topics/             Topic source files (.topic and .md)
  c.list              Categories
  v.list              Variables
  cfg/                Build profiles
  images/             Topic images
```

## Building locally

1. Open the project in IntelliJ IDEA with the Writerside plugin installed.
2. Run **Build | Build Help Instance**.
3. Use the Writerside Preview pane to inspect rendered output.

## Author

Fran Roberts
