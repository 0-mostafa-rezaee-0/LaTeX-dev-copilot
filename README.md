## 🧰 How to Use This Template    
Click the green **"Use this template"** button at the top of the page, then choose **"Create a new repository"**.   
This will create your own copy of this project, which you can modify freely — no need to fork!   

---

<div align="center">
    <img src="1_Archive/1_README_images/banner.png" alt="banner" width="50%">
</div>

<h1 align="center">LaTeX Development Copilot</h1>

<div align="center">
A collection of modern LaTeX templates optimized for developers and tech professionals who prefer working with VS Code, Docker, and modern development tools.
</div>

# 1. About This Repository

This repository provides a comprehensive development environment for LaTeX document creation tailored specifically for software developers and tech professionals. It bridges the gap between traditional academic document preparation and modern development workflows by integrating containerized environments, version control, and AI assistance.

Our goal is to eliminate the typical pain points of LaTeX setup (package management, environment configuration, and cross-platform compatibility) while providing a familiar development experience with the tools tech professionals already use daily.

## 1.1. Who Is This For?

This repository is designed for:

- **Software developers** who need to write technical documentation or academic papers
- **Technical researchers** who want a more developer-friendly LaTeX workflow
- **Academic writers** with programming experience who want to leverage modern tools
- **Data scientists** publishing results who prefer working in containerized environments
- **Students** in technical fields comfortable with command-line tools and version control

The templates and tools are particularly valuable for professionals working at the intersection of software development and academic/technical writing.

## 1.2. What Will You Learn?

By using this repository, you will:

- Set up a reproducible LaTeX environment using Docker containers
- Integrate AI assistance (GitHub Copilot) into your writing workflow
- Implement automated quality checks and builds through CI/CD pipelines
- Organize complex documents with modern project structures
- Apply software development best practices to document creation
- Create professional publications using journal-specific templates
- Customize document appearance with modern typography and fonts

## 1.3. Prerequisites

### For LaTeX and Docker Experts
- Jump directly to the templates and customize as needed
- Explore the CI/CD pipelines to implement in your own projects
- Extend the containers with additional packages or tools

### For Developers New to LaTeX
- Review the tutorials in the `2_Tutorials` directory to understand LaTeX basics
- Start with the simplified Research Paper template before moving to more complex templates
- Follow the Quick Start guide to get a working environment immediately

### For LaTeX Users New to Development Tools
- Begin with the Docker Compose tutorial to understand containerization
- Use the VS Code integration guides to set up your editor properly
- Reference the project structure documentation to understand the organization

## 1.4. Project Structure

```
Folder PATH listing
+---1_Archive                 <-- Archived materials and resources
│   +---1_README_images       <-- Images used in README documentation
│   │       README.md         <-- Documentation for README images
│   │       banner.png        <-- Banner image for documentation
│   │       banner.png:Zone.Identifier <-- Windows metadata file
│   │
│       DDPM_Laryngeal_Springer_2025-04-29.zip <-- Archived Laryngeal paper for Springer
│       DDPM_X-Ray_ArXiv_2025-04-29.zip <-- Archived X-Ray paper for ArXiv
│       README.md             <-- Documentation for archived materials
│
+---2_Tutorials               <-- LaTeX tutorials and learning resources
│       docker-compose-tutorial.md <-- Tutorial for Docker Compose setup
│       Fix_Cursor_Chat_Screenshot_Pasting_in_WSL.md <-- Guide for fixing screenshot pasting in WSL
│       README.md             <-- Documentation for tutorials
│
+---3_Journal_Templates       <-- Templates for various academic journals
│   +---acm                   <-- ACM journal template
│   │       acmart-primary.zip <-- ACM official template package
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
│       Inter-VariableFont_opsz,wght.ttf <-- Inter variable font (regular)
│       Inter-Italic-VariableFont_opsz,wght.ttf <-- Inter variable font (italic)
│       Inter,Montserrat.zip  <-- Combined font package
│       Montserrat-VariableFont_wght.ttf <-- Montserrat variable font (regular)
│       Montserrat-Italic-VariableFont_wght.ttf <-- Montserrat variable font (italic)
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

# 2. Templates

## 2.1 FlexiTeX Template
Modern template with full development tooling:
- Docker container with all dependencies
- GitHub Copilot support
- GitHub Actions for CI/CD
- Automatic formatting and linting
- Multiple style support (IEEE, ACM, USENIX)
- VS Code integration

## 2.2 Scientific Paper Template
Web-like project structure for better organization:
- Modular file organization
- Separate figures directory
- Bibliography management
- Modern styling options
- Enhanced table support

## 2.3 Dissertate Template
Beautiful typography for long-form technical writing:
- Clean, modern design
- Multiple institution support
- Chapter organization
- Perfect for technical documentation
- Professional typography

## 2.4 Research Paper Template
Minimalist template for quick technical writeups:
- Fast setup
- Cloud-ready (Overleaf support)
- Conference paper format
- Technical report layout

# 3. Getting Started

## 3.1 Prerequisites
- VS Code
- Docker Desktop
- Git

## 3.2 Quick Start
1. Clone this repository:
```bash
git clone https://github.com/yourusername/LaTeX-dev-copilot.git
cd LaTeX-dev-copilot
```

2. Open in VS Code:
```bash
code .
```

3. When prompted, click "Reopen in Container" to start the dev container

4. Choose a template and start writing!

## 3.3 VS Code Extensions
Recommended extensions will be automatically installed in the dev container:
- LaTeX Workshop
- GitHub Copilot
- Code Spell Checker
- GitLens
- Docker

# 4. Features

## 4.1 Development Environment
- Containerized LaTeX environment
- Live preview
- AI assistance with Copilot
- Automatic formatting
- Spell checking
- Error detection

## 4.2 Build System
- Automated builds with GitHub Actions
- Continuous Integration
- Quality checks
- PDF generation
- PDF/A for archival

## 4.3 Quality Tools
- LaTeX linting
- Style checking
- Grammar checking
- Reference validation
- Health reports

# 5. Contributing

Contributions are welcome! Please read our contributing guidelines before submitting pull requests.

# 6. License

This project is licensed under the MIT License - see the LICENSE file for details.

# 7. Acknowledgments

- FlexiTeX template adapted from GTkernel-PaperFactory
- Scientific Paper template adapted from JDLanctot
- Dissertate template adapted from suchow
- Research Paper template adapted from aalekhpatel07
