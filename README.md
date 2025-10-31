# Obsidian PDF Embed Plugin

A plugin to embed PDF documents into markdown notes.

This plugin allows you to easily embed PDF documents into your Obsidian notes. It provides several commands to streamline your workflow and offers a variety of settings for customization.

## Features

- **Embed PDFs in new notes:** Create a new note with a PDF embedded in it.
- **Embed PDFs at cursor:** Embed a PDF directly at your cursor's position in the active note.
- **Embed the currently opened PDF:** Quickly embed the PDF you are currently viewing.
- **Batch embed from a directory:** Embed multiple PDFs from a directory at once, either as a single combined Markdown file or as multiple individual Markdown files.
- **Customizable file naming:** Use templates to define how your new notes are named, and the plugin will intelligently handle file extensions when creating single combined Markdown files.

## How to Use

The plugin provides the following commands:

- **Embed PDF document (new file):** Opens a modal to select a PDF file, then creates a new note with the PDF embedded.
- **Embed PDF at cursor:** Opens a modal to select a PDF file, then inserts the embed link at the cursor's position in the active note.
- **Embed currently opened PDF:** Inserts the embed link for the currently opened PDF at the cursor's position in the active note.
- **Embed PDFs from directory:** Opens a modal to select a source directory for PDFs. After selecting the PDFs, you will be asked if you want to "Create a single combined MD file, or One MD file per PDF?". If you choose to create a single file, you will be prompted to enter a file name (without extension).
