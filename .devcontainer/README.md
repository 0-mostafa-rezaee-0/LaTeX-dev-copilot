<h1 align="center">LaTeX Development Container</h1>

This directory contains the configuration for the LaTeX development container used in this project.

---

***Table of Contents***

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#1-directory-structure"><i><b>1. Directory Structure</b></i></a>
</div>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#2-directory-structure"><i><b>2. Directory Structure</b></i></a>
</div>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#3-setup-instructions"><i><b>3. Setup Instructions</b></i></a>
</div>
&nbsp;

<details>
  <summary><a href="#4-important-latex-workshop-extension"><i><b>4. Important: LaTeX Workshop Extension</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#41-if-latex-workshop-is-not-installed-automatically">4.1 If LaTeX Workshop is not installed automatically:</a><br>
  </div>
</details>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#5-troubleshooting"><i><b>5. Troubleshooting</b></i></a>
</div>
&nbsp;

---

# 1. Directory Structure

```
Folder PATH listing
+---1_README_images           <-- Images used in README documentation
│       README.md             <-- Documentation for README images
│       banner.png            <-- Banner image for documentation
│
        DDPM_Laryngeal_Springer_2025-04-29.zip <-- Archived Laryngeal paper for Springer
        DDPM_X-Ray_ArXiv_2025-04-29.zip <-- Archived X-Ray paper for ArXiv
        README.md             <-- Archive directory documentation
```

# 2. Directory Structure

```
Folder PATH listing
        devcontainer.json     <-- VS Code Dev Container configuration
        docker-compose.yml    <-- Docker Compose configuration for the dev container
        README.md             <-- Dev Container documentation
```

# 3. Setup Instructions

1. Install [Docker Desktop](https://www.docker.com/products/docker-desktop/)
2. Install [Cursor](https://cursor.sh/) IDE or Visual Studio Code
3. Install the [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension

# 4. Important: LaTeX Workshop Extension

The container configuration is set to automatically install certain extensions, including LaTeX Workshop. However, in some cases, the automatic installation may fail.

## 4.1 If LaTeX Workshop is not installed automatically:

1. Open the Extensions view in Cursor or VS Code (press `Ctrl+Shift+X` or `Cmd+Shift+X`)
2. Search for "LaTeX Workshop"
3. Click "Install" on the extension by James Yu

After installation, you may need to reload the window (`Ctrl+Shift+P` or `Cmd+Shift+P` → "Developer: Reload Window").

# 5. Troubleshooting

If you encounter issues with PDF compilation:

1. Check that LaTeX Workshop is properly installed
2. Try manual compilation using the LaTeX Workshop sidebar (click the build icon)
3. Check for syntax errors in your .tex files
4. Ensure the build directory exists (`mkdir -p build` in terminal if needed) 