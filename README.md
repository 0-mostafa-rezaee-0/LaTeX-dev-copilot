<h1 align="center">LaTeX Development Templates with VS Code & Docker</h1>

<div align="center">
A collection of modern LaTeX templates optimized for developers and tech professionals who prefer working with VS Code, Docker, and modern development tools.
</div>

# 1. Overview

This repository contains carefully curated LaTeX templates designed specifically for tech-savvy users who:
- Are comfortable with VS Code and modern IDEs
- Prefer Docker-based development environments
- Use version control (Git) effectively
- Want GitHub Copilot integration
- Need automated builds and quality checks

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

# 8. Project Structure

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
