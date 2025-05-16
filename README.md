## 🧰 How to Use This Template    
Click the green **"Use this template"** button at the top of the page, then choose **"Create a new repository"**.   
This will create your own copy of this project, which you can modify freely — no need to fork!   

---

<p align="center">
  <img src="1_Archive/1_README_images/banner.png" alt="banner" width="75%">
</p>

<h1 align="center">LaTeX Development Copilot</h1>

Next-generation LaTeX development with key advantages over Overleaf:

- **Integrated AI assistance:** Access GitHub Copilot's Claude 3.7 Sonnet capabilities through VS Code/Cursor with a single subscription — use the same powerful AI for both coding and LaTeX document writing without paying extra
- **Full-context intelligence:** Unlike Overleaf, Copilot can see and analyze your entire project structure, including references, figures, and bibliography files, resulting in much more relevant and accurate suggestions
- **Seamless live updates:** View your document changes in real-time without manually compiling — modifications to your LaTeX files instantly update in the preview, eliminating the compile-and-wait workflow required by Overleaf

---

***Table of Contents***

<details>
  <summary><a href="#1-about-this-repository"><i><b>1. About This Repository</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#11-who-is-this-for">1.1. Who Is This For?</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#12-what-will-you-learn">1.2. What Will You Learn?</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#13-prerequisites">1.3. Prerequisites</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#14-project-structure">1.4. Project Structure</a><br>
  </div>
</details>
&nbsp;

<details>
  <summary><a href="#2-tutorials"><i><b>2. Tutorials</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#21-docker-compose-setup">2.1 Docker Compose Setup</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#22-fix-cursor-chat-screenshot-wsl">2.2 Fix Cursor Chat Screenshot in WSL</a><br>
  </div>
</details>
&nbsp;

<details>
  <summary><a href="#3-journal-templates"><i><b>3. Journal's LaTeX Templates</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#31-acm-template">3.1 ACM Template</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#32-ieee-template">3.2 IEEE Template</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#33-usenix-template">3.3 USENIX Template</a><br>
  </div>
</details>
&nbsp;

<details>
  <summary><a href="#4-getting-started"><i><b>4. Getting Started</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#41-prerequisites">4.1 Prerequisites</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#42-quick-start">4.2 Quick Start</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#43-vs-code-extensions">4.3 VS Code Extensions</a><br>
  </div>
</details>
&nbsp;

<details>
  <summary><a href="#5-features"><i><b>5. Features</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#51-development-environment">5.1 Development Environment</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#52-build-system">5.2 Build System</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#53-quality-tools">5.3 Quality Tools</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#54-advantages-over-overleaf">5.4 Advantages Over Overleaf</a><br>
  </div>
</details>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#6-acknowledgments"><i><b>6. Acknowledgments</b></i></a>
</div>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#7-contact-information"><i><b>7. Contact Information</b></i></a>
</div>
&nbsp;

---

# 1. About This Repository

This repository provides a next-generation LaTeX development environment designed specifically for developers and tech professionals. It revolutionizes the document writing experience by combining:

1. **AI-powered writing assistance** through GitHub Copilot integration in VS Code/Cursor
2. **Containerized LaTeX environments** that eliminate configuration headaches
3. **Real-time preview updates** without manual compilation steps

By merging modern software development workflows with academic writing, this project bridges the gap between traditional document preparation systems (like Overleaf) and the powerful tooling that developers are accustomed to using daily.

## 1.1. Who Is This For?

This repository is ideal for:

- **Software developers** creating technical documentation who want their familiar IDE and tools
- **Technical researchers** tired of Overleaf limitations and seeking AI assistance
- **Academic writers** who want version control, containerization, and modern workflows
- **Data scientists** publishing papers who need reproducible environments
- **CS/Engineering students** comfortable with command-line and looking for a better LaTeX experience

The templates and tools are particularly valuable for professionals who want the power of AI assistance and modern development practices in their document creation process.

## 1.2. What Will You Learn?

By using this repository, you will:

- Experience seamless writing with Copilot's AI-powered completions and suggestions
- Create documents in a reproducible environment using Docker containers
- Preview changes in real-time without manual compilation steps
- Organize complex documents with modern project structures
- Apply software development best practices to document creation
- Leverage the full power of VS Code/Cursor extensions for writing
- Create professional publications using journal-specific templates

## 1.3. Prerequisites

**No specialized LaTeX knowledge required!** To get started, you only need:

1. **VS Code** or **Cursor** installed on your computer
2. **Docker Desktop** installed and running

That's it! The containerized environment handles all LaTeX installations, packages, and configurations automatically. Just open the project and start writing.

If you already have experience with LaTeX or Docker, you can skip directly to the templates or customize the environment to your preferences.

## 1.4. Project Structure

```
Folder PATH listing
+---1_Archive                 <-- Archived materials and resources
│   +---1_README_images       <-- Images used in README documentation
│   │       README.md         <-- Documentation for README images
│   │       banner.png        <-- Banner image for documentation
│   │
│       DDPM_Laryngeal_...    <-- Archived Laryngeal paper for Springer
│       DDPM_X-Ray_ArXi...    <-- Archived X-Ray paper for ArXiv
│       README.md             <-- Documentation for archived materials
│
+---2_Tutorials               <-- LaTeX tutorials and learning resources
│       docker-compos...      <-- Tutorial for Docker Compose setup
│       Fix_Cursor_Ch...      <-- Guide for fixing screenshot pasting in WSL
│       README.md             <-- Documentation for tutorials
│
+---3_Journal_Templates       <-- Templates for various academic journals
│   +---acm                   <-- ACM journal template
│   │       acmart-prim...    <-- ACM official template package
│   │       acmart.pdf        <-- ACM style documentation
│   │       README.md         <-- Documentation for ACM template
│   │
│   +---ieee                  <-- IEEE journal template
│   │       README.md         <-- Documentation for IEEE template
│   │
│   +---usenix                <-- USENIX journal template
│   │       README.md         <-- Documentation for USENIX template
│   │
│       README.md             <-- Documentation for journal templates
│
+---4_Custom_Fonts            <-- Custom font resources and configurations
│       Inter.zip             <-- Inter font package
│       Inter-Variab...       <-- Inter variable font (regular)
│       Inter-Italic...       <-- Inter variable font (italic)
│       Inter,Monts...        <-- Combined font package
│       Montserrat-...        <-- Montserrat variable font (regular)
│       Montserrat-...        <-- Montserrat variable font (italic)
│       README.md             <-- Documentation for custom fonts
│
+---Article-1                 <-- Article project 1 (empty directory)
│
+---Article-2                 <-- Article project 2 (empty directory)
│
+---Article-3                 <-- Article project 3 (empty directory)
│
+---.devcontainer             <-- VS Code development container configuration
│       devcontainer.json     <-- VS Code Dev Container configuration
│       docker-compose.yml    <-- Docker Compose configuration for the dev container
│       README.md             <-- Documentation for dev container
│
│       .gitignore            <-- Git exclusion patterns
│       docker-compose.yml    <-- Docker configuration
│       LICENSE               <-- License information
│       README.md             <-- Project overview
```

# 2. Tutorials

The `2_Tutorials` directory contains helpful guides and tutorials to get you started with LaTeX development. These tutorials cover various aspects from basic setup to advanced usage techniques.

Current tutorials include:
- Docker Compose setup guide
- Fix for Cursor Chat Screenshot pasting in WSL
- More tutorials will be added regularly to help you make the most of this development environment

If you have specific tutorial requests, please feel free to suggest them through GitHub issues.

# 3. Journal's LaTeX Templates

The `3_Journal_Templates` directory provides ready-to-use LaTeX templates for various academic journals and publication formats. These templates follow the official formatting guidelines for each publisher, saving you time and ensuring your submissions meet all requirements.

Currently available templates include:

## 3.1 ACM Template
The Association for Computing Machinery (ACM) template follows the official ACM formatting guidelines. It includes:
- Proper font styles and sizes
- Correct citation format
- Column layout according to ACM requirements
- Section formatting that meets ACM standards

## 3.2 IEEE Template
The Institute of Electrical and Electronics Engineers (IEEE) template is designed for conference and journal submissions. Features include:
- IEEE-compliant formatting
- Bibliography style matching IEEE requirements
- Figure and table layouts optimized for IEEE publications
- Proper header and footer formatting

## 3.3 USENIX Template
The USENIX template is tailored for USENIX conference submissions. It provides:
- USENIX-approved layouts and formatting
- Proper citation styles
- Section organization following USENIX conventions
- Figure and table styles that match USENIX requirements

Additional templates will be added based on community needs. Each template is maintained to stay current with the latest publisher requirements.

# 4. Getting Started

## 4.1 Prerequisites
- VS Code
- Docker Desktop
- Git

## 4.2 Quick Start
Getting started with LaTeX Development Copilot is simple:

1. **Prerequisites**: Install [VS Code](https://code.visualstudio.com/), [Docker Desktop](https://www.docker.com/products/docker-desktop/), and [Git](https://git-scm.com/downloads)

2. **Setup Project**:
   ```bash
   # Clone this repository 
   git clone https://github.com/yourusername/LaTeX-dev-copilot.git
   cd LaTeX-dev-copilot
   ```

3. **Start Environment**:
   - Open the project in VS Code: `code .`
   - When prompted, click "Reopen in Container" to start the dev container
   - Choose a template and start writing!

4. **That's it!** The containerized environment includes all LaTeX dependencies, extensions, and tools you need.

For detailed instructions, see the tutorials in the `2_Tutorials` directory.

## 4.3 VS Code Extensions
Recommended extensions will be automatically installed in the dev container:
- LaTeX Workshop
- GitHub Copilot
- Code Spell Checker
- GitLens
- Docker

# 5. Features

## 5.1 Development Environment
- Containerized LaTeX environment
- Live preview
- AI assistance with Copilot
- Automatic formatting
- Spell checking
- Error detection

## 5.2 Build System
- Automated builds with GitHub Actions
- Continuous Integration
- Quality checks
- PDF generation
- PDF/A for archival

## 5.3 Quality Tools
- LaTeX linting
- Style checking
- Grammar checking
- Reference validation
- Health reports

## 5.4 Advantages Over Overleaf

### Developer-First Experience
- **Local Development**: Work offline with full functionality
- **Modern Editor**: Full VS Code/Cursor experience (snippets, multi-cursor editing, integrated terminal)
- **AI Assistance**: Native GitHub Copilot integration for intelligent writing assistance
- **Git Workflow**: Proper version control with branching, PR reviews, and CI/CD
- **Extensions**: Access to your favorite editor extensions and customizations

### Enhanced Performance and Control
- **Speed**: Faster compilation with local processing power
- **No Subscription**: One-time setup, no recurring fees
- **Privacy**: Keep sensitive documents on your system
- **Package Freedom**: Install any LaTeX package without limitations
- **Customization**: Full control over LaTeX installation and configurations
- **Docker Integration**: Consistent environment across any machine

# 6. Acknowledgments

- FlexiTeX template adapted from GTkernel-PaperFactory
- Scientific Paper template adapted from JDLanctot
- Dissertate template adapted from suchow
- Research Paper template adapted from aalekhpatel07

# 7. Contact Information

For questions not addressed in the resources above, please connect with [Mostafa Rezaee](https://www.linkedin.com/in/mostafa-rezaee/) on LinkedIn for personalized assistance.