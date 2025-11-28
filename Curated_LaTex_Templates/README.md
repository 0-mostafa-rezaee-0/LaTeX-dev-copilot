<h1 align="center">LaTeX Templates for Tech Professionals</h1>

<div align="center">
A curated collection of modern LaTeX templates specifically chosen for tech professionals who use VS Code, Docker, and modern development workflows.
</div>

---

<!-- TOC -->
***Table of Contents***


<details>
  <summary><a href="#1-1-directory-structure"><i><b>1. Directory Structure</b></i></a></summary>
</details>
&nbsp;

<details>
  <summary><a href="#2-2-available-templates"><i><b>2. Available Templates</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#21-21-acm-template">2.1 ACM Template</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#22-22-ieee-template">2.2 IEEE Template</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#23-23-elsevier-template">2.3 Elsevier Template</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#24-24-generic-templates">2.4 Generic Templates</a><br>
  </div>
</details>
&nbsp;

<details>
  <summary><a href="#3-3-recommended-external-templates"><i><b>3. Recommended External Templates</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#31-31-flexitex-template">3.1 FlexiTeX Template</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#32-32-scientific-paper-template">3.2 Scientific Paper Template</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#33-33-dissertate-template">3.3 Dissertate Template</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#34-34-research-paper-template">3.4 Research Paper Template</a><br>
  </div>
</details>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#4-4-usage-instructions"><i><b>4. Usage Instructions</b></i></a>
</div>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#5-5-template-selection-guide"><i><b>5. Template Selection Guide</b></i></a>
</div>
&nbsp;

<details>
  <summary><a href="#5-5-additional-resources"><i><b>5. Additional Resources</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#51-51-style-files">5.1 Style Files</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#52-52-documentation">5.2 Documentation</a><br>
  </div>
</details>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#6-6-contributing"><i><b>6. Contributing</b></i></a>
</div>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#7-7-references"><i><b>7. References</b></i></a>
</div>
&nbsp;

<!-- /TOC -->

# 1. Directory Structure

```
Folder PATH listing
+---acm                       <-- ACM journal template files
│       acmart-primary.zip    <-- ACM official template package
│       acmart.pdf            <-- ACM style documentation
│       README.md             <-- ACM template documentation
│
+---IEEE                      <-- IEEE journal template files
│       README.md             <-- IEEE template documentation
│
+---Elsevier                  <-- Elsevier journal template files
│       elsarticle.cls        <-- Elsevier article class file
│       elsarticle-num.bst    <-- Elsevier bibliography style
│       main.tex              <-- Sample main document
│       references.bib        <-- Sample bibliography
│
+---template1                 <-- Generic template 1
│       main.tex              <-- Main document file
│       References.bib        <-- Bibliography file
│
        README.md             <-- Curated templates overview
```

# 2. Available Templates

This directory contains ready-to-use LaTeX templates for various academic journals and publication formats. Each template follows the official formatting guidelines for its respective publisher.

## 2.1 ACM Template
The Association for Computing Machinery (ACM) template is located in the `acm/` subdirectory. It includes:
- Official ACM template package (`acmart-primary.zip`)
- ACM style documentation (`acmart.pdf`)
- Proper font styles and sizes according to ACM requirements
- Correct citation format
- Column layout following ACM guidelines

For detailed usage instructions, see the [ACM template README](acm/README.md).

## 2.2 IEEE Template
The Institute of Electrical and Electronics Engineers (IEEE) template is located in the `IEEE/` subdirectory. It provides:
- IEEE-compliant formatting guidelines
- Bibliography style matching IEEE requirements
- Figure and table layouts optimized for IEEE publications
- Proper header and footer formatting

For detailed usage instructions, see the [IEEE template README](IEEE/README.md).

## 2.3 Elsevier Template
The Elsevier template is located in the `Elsevier/` subdirectory. It includes:
- `elsarticle.cls` class file for Elsevier formatting
- `elsarticle-num.bst` bibliography style
- Sample main document (`main.tex`)
- Sample bibliography file (`references.bib`)
- Proper formatting according to Elsevier journal guidelines

## 2.4 Generic Templates
Generic templates are available in the `template1/` subdirectory for quick starts and custom projects. These provide:
- Basic LaTeX document structure (`main.tex`)
- Bibliography setup (`References.bib`)
- Ready-to-use configurations
- Easy customization options

# 3. Recommended External Templates

The following templates are recommended for tech professionals but are not included in this directory. You can download and use them separately:

## 3.1 FlexiTeX Template
**Source**: [GTkernel-PaperFactory/flexitex](https://github.com/GTkernel-PaperFactory/flexitex)

Perfect for tech professionals who want a modern development environment:
- Full Docker integration with VS Code
- GitHub Actions for CI/CD
- Built-in support for:
  - IEEE format
  - ACM format
  - USENIX format
- Automatic PDF and PDF/A generation
- Linting and quality checks

**Key Features:**
- Containerized LaTeX environment
- GitHub Copilot support
- Automated builds
- Code formatting
- Health reports

## 3.2 Scientific Paper Template
**Source**: [JDLanctot/latex_template](https://github.com/JDLanctot/latex_template)

Organized like a modern web project for better maintainability:
- Clean separation of content
- Modular file structure
- Easy figure management
- Bibliography automation
- Modern styling options

**Key Features:**
- Web-like directory structure
- Dedicated figures directory
- Reference management
- Customizable styling
- Enhanced tables

## 3.3 Dissertate Template
**Source**: [suchow/Dissertate](https://github.com/suchow/Dissertate)

Beautiful typography and professional design:
- Clean, modern aesthetics
- Multiple institution support
- Perfect for long-form technical documentation
- Professional typography
- Used by numerous universities worldwide

**Key Features:**
- Modern design
- Institution templates
- Chapter organization
- Technical documentation
- Typography focus

## 3.4 Research Paper Template
**Source**: [aalekhpatel07/ResearchPaperLaTeXTemplate](https://github.com/aalekhpatel07/ResearchPaperLaTeXTemplate)

Minimalist template for quick technical papers:
- Fast setup
- Cloud-ready
- Conference paper format
- Technical report layout
- Easy customization

**Key Features:**
- Quick start
- Overleaf compatible
- Conference ready
- Report formats
- Minimal setup

# 4. Usage Instructions

1. Choose a template from the `Curated_LaTex_Templates` directory that best fits your needs
2. Copy the template files to your working directory (e.g., `Article-1/`, `Article-2/`, etc.)
3. Follow the template's specific setup instructions (see individual README files in each template directory)
4. Use with the Docker development environment provided in this repository
5. For external templates, clone the template repository and follow their setup instructions

# 5. Template Selection Guide

## Available Templates in This Directory

| Template | Best For | Setup Complexity | Location |
|----------|----------|------------------|----------|
| ACM | ACM conferences and journals | Low | `acm/` |
| IEEE | IEEE conferences and journals | Low | `IEEE/` |
| Elsevier | Elsevier journal submissions | Low | `Elsevier/` |
| Generic | Quick starts and custom projects | Very Low | `template1/` |

## Recommended External Templates

| Template | Best For | Setup Complexity | Docker Ready |
|----------|----------|------------------|--------------|
| FlexiTeX | Modern dev workflow | Medium | Yes |
| Scientific | Organized projects | Low | Yes |
| Dissertate | Long documents | Low | Yes |
| Research | Quick papers | Very Low | Yes |

# 6. Additional Resources

## 6.1 Style Files
- [IEEE Template](https://template-selector.ieee.org/secure/templateSelector/downloadTemplate?publicationTypeId=1&titleId=1&articleId=1&fileType=4)
- [ACM Template](https://www.acm.org/publications/proceedings-template)
- [USENIX Template](https://www.usenix.org/conferences/author-resources/paper-templates)

## 6.2 Documentation
- [LaTeX Workshop VS Code Extension](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- [Docker LaTeX Guide](https://github.com/blang/latex-docker)

# 7. Contributing

If you have suggestions for additional templates or improvements, please submit a pull request or open an issue.

# 8. References

1. GTkernel-PaperFactory. (2025). FlexiTeX: Flexible LaTeX Template. GitHub. https://github.com/GTkernel-PaperFactory/flexitex
2. Lanctot, J.D. (2025). LaTeX Template for quicker scientific writing. GitHub. https://github.com/JDLanctot/latex_template
3. Suchow, J. (2025). Dissertate: Beautiful LaTeX dissertation templates. GitHub. https://github.com/suchow/Dissertate
4. Patel, A. (2025). ResearchPaperLaTeXTemplate. GitHub. https://github.com/aalekhpatel07/ResearchPaperLaTeXTemplate
