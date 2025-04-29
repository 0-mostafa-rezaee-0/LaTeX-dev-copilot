<h1 align="center">Custom Fonts Collection</h1>

<!-- TOC -->
***Table of Contents***


<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#1-1-available-fonts"><i><b>1. 1. Available Fonts</b></i></a>
</div>
&nbsp;

<details>
  <summary><a href="#2-2-usage-guidelines"><i><b>2. 2. Usage Guidelines</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#21-21-font-installation">2.1. 2.1 Font Installation</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#22-22-implementation">2.2. 2.2 Implementation</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#23-23-best-practices">2.3. 2.3 Best Practices</a><br>
  </div>
</details>
&nbsp;

<details>
  <summary><a href="#3-3-font-information"><i><b>3. 3. Font Information</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#31-31-inter">3.1. 3.1 Inter</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#32-32-montserrat">3.2. 3.2 Montserrat</a><br>
  </div>
</details>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#4-4-contributing-fonts"><i><b>4. 4. Contributing Fonts</b></i></a>
</div>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#5-5-directory-structure"><i><b>5. 5. Directory Structure</b></i></a>
</div>
&nbsp;

<!-- /TOC -->


This directory contains a curated collection of high-quality fonts that can be used in LaTeX documents. These fonts are specifically selected for academic and professional writing, offering alternatives to standard LaTeX fonts.

# 1. Available Fonts

- **Inter**: A highly readable font designed for screens
- **Montserrat**: A modern, geometric font with excellent readability

# 2. Usage Guidelines

## 2.1 Font Installation
   - Copy the desired font files to your article's directory
   - Place them in a `fonts` subdirectory
   - Update your LaTeX document to use the new fonts

## 2.2 Implementation
   ```latex
   % Example for using Inter font
   \usepackage{fontspec}
   \setmainfont{Inter}[
       Path=./fonts/,
       Extension=.ttf,
       UprightFont=*-Regular,
       ItalicFont=*-Italic,
       BoldFont=*-Bold
   ]
   ```

## 2.3 Best Practices
   - Always check font licenses before use
   - Test font rendering in your target output format
   - Consider font size and spacing adjustments
   - Document font usage in your project

# 3. Font Information

## 3.1 Inter
- Type: Sans-serif
- Style: Modern, clean
- Best for: Digital documents, presentations
- License: Open Font License

## 3.2 Montserrat
- Type: Sans-serif
- Style: Geometric, professional
- Best for: Headings, titles
- License: Open Font License

# 4. Contributing Fonts

If you'd like to contribute a font:
1. Ensure the font has an appropriate license for distribution
2. Include all necessary font files and variations
3. Add font documentation and usage examples
4. Submit a pull request with your contribution

# 5. Directory Structure

```
Folder PATH listing
        Inter.zip                             <-- Inter font package
        Inter-VariableFont_opsz,wght.ttf      <-- Inter variable font (regular)
        Inter-Italic-VariableFont_opsz,wght.ttf <-- Inter variable font (italic)
        Inter,Montserrat.zip                  <-- Combined font package
        Montserrat-VariableFont_wght.ttf      <-- Montserrat variable font (regular)
        Montserrat-Italic-VariableFont_wght.ttf <-- Montserrat variable font (italic)
        README.md                             <-- Font collection documentation
```
