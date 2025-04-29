# Markdown TOC Generator

A tool for automatically generating Tables of Contents for Markdown files following a specific format.

<!-- TOC -->
***Table of Contents***


<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#1-markdown-toc-generator"><i><b>1. Markdown TOC Generator</b></i></a>
</div>
&nbsp;

<details>
  <summary><a href="#2-introduction"><i><b>2. Introduction</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#21-features">2.1. Features</a><br>
  </div>
</details>
&nbsp;

<details>
  <summary><a href="#3-installation"><i><b>3. Installation</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#31-requirements">3.1. Requirements</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#32-setup">3.2. Setup</a><br>
  </div>
</details>
&nbsp;

<details>
  <summary><a href="#4-usage"><i><b>4. Usage</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#41-using-the-helper-script">4.1. Using the Helper Script</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#42-single-file-processing">4.2. Single File Processing</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#43-batch-processing">4.3. Batch Processing</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#44-inserting-toc-into-files">4.4. Inserting TOC Into Files</a><br>
  </div>
</details>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#5-toc-format"><i><b>5. TOC Format</b></i></a>
</div>
&nbsp;

<details>
  <summary><a href="#6-development"><i><b>6. Development</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#61-contributing">6.1. Contributing</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#62-license">6.2. License</a><br>
  </div>
</details>
&nbsp;

<!-- /TOC -->

# Introduction

This project provides scripts to automatically generate and insert Tables of Contents into Markdown files. The TOC follows a specific format with collapsible sections for headings that have child elements.

## Features

- Generates a Table of Contents with proper formatting and structure
- Creates collapsible blocks for headings with subheadings
- Creates simple blocks for headings without subheadings
- Automatically generates slugs for anchors
- Supports batch processing of multiple files
- Inserts or updates the TOC in-place in Markdown files

# Installation

## Requirements

- Python 3.6 or higher

## Setup

Clone this repository and make the Python scripts executable:

```bash
git clone https://github.com/yourusername/markdown-toc-generator.git
cd markdown-toc-generator
chmod +x toc_generator.py batch_toc_generator.py update_all_readmes.py toc_helper.py
```

# Usage

## Using the Helper Script

The easiest way to use the TOC generator is with the helper script:

```bash
./toc_helper.py -f README.md -i    # Insert TOC into a single file
./toc_helper.py -d . -r            # Process all README.md files recursively
./toc_helper.py -d docs -a         # Process all Markdown files in docs directory
./toc_helper.py -d . -r -a -p      # Print TOCs for all Markdown files without inserting
```

For more options, run:

```bash
./toc_helper.py --help
```

## Single File Processing

To generate a TOC for a single file:

```bash
./toc_generator.py path/to/markdown_file.md
```

## Batch Processing

To process all README.md files in a directory:

```bash
./batch_toc_generator.py path/to/directory
```

With recursive search:

```bash
./batch_toc_generator.py path/to/directory --recursive
```

## Inserting TOC Into Files

To insert the TOC directly into files (between `<!-- TOC -->` and `<!-- /TOC -->` markers):

```bash
./batch_toc_generator.py path/to/directory --insert
```

If your file doesn't have TOC markers, they will be added automatically.

# TOC Format

The TOC follows this format:

- Level 1 headings without subheadings are displayed as simple divs
- Level 1 headings with subheadings are displayed as collapsible details/summary elements
- All headings are properly indented with non-breaking spaces
- Subheadings are listed within their parent's collapsible block

# Development

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
