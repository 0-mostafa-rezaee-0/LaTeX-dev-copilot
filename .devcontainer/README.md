<h1 align="center">LaTeX Development Container</h1>

This directory contains the configuration for the LaTeX development container used in this project.

# 1. Setup Instructions

1. Install [Docker Desktop](https://www.docker.com/products/docker-desktop/)
2. Install [Cursor](https://cursor.sh/) IDE or Visual Studio Code
3. Install the [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension

# 2. Important: LaTeX Workshop Extension

The container configuration is set to automatically install certain extensions, including LaTeX Workshop. However, in some cases, the automatic installation may fail.

## 2.1 If LaTeX Workshop is not installed automatically:

1. Open the Extensions view in Cursor or VS Code (press `Ctrl+Shift+X` or `Cmd+Shift+X`)
2. Search for "LaTeX Workshop"
3. Click "Install" on the extension by James Yu

After installation, you may need to reload the window (`Ctrl+Shift+P` or `Cmd+Shift+P` → "Developer: Reload Window").

# 3. Using the LaTeX Environment

Once the container is running and LaTeX Workshop is installed:

1. Edit `.tex` files directly in the editor
2. Save to trigger automatic compilation (configured in LaTeX Workshop)
3. View the compiled PDF in the built-in tab viewer
4. Use Cursor AI (`Ctrl+K` or `Cmd+K`) for LaTeX assistance

# 4. Troubleshooting

If you encounter issues with PDF compilation:

1. Check that LaTeX Workshop is properly installed
2. Try manual compilation using the LaTeX Workshop sidebar (click the build icon)
3. Check for syntax errors in your .tex files
4. Ensure the build directory exists (`mkdir -p build` in terminal if needed)

# 5. Directory Structure

```
Folder PATH listing
        devcontainer.json     <-- VS Code Dev Container configuration
        docker-compose.yml    <-- Docker Compose configuration for the dev container
        README.md             <-- Dev Container documentation
``` 