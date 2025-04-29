<h1 align="center">Custom Fonts Collection</h1>

This directory contains a curated collection of high-quality fonts that can be used in LaTeX documents. These fonts are specifically selected for academic and professional writing, offering alternatives to standard LaTeX fonts.

## Available Fonts

- **Inter**: A highly readable font designed for screens
- **Montserrat**: A modern, geometric font with excellent readability

## Usage Guidelines

1. **Font Installation**
   - Copy the desired font files to your article's directory
   - Place them in a `fonts` subdirectory
   - Update your LaTeX document to use the new fonts

2. **Implementation**
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

3. **Best Practices**
   - Always check font licenses before use
   - Test font rendering in your target output format
   - Consider font size and spacing adjustments
   - Document font usage in your project

## Font Information

### Inter
- Type: Sans-serif
- Style: Modern, clean
- Best for: Digital documents, presentations
- License: Open Font License

### Montserrat
- Type: Sans-serif
- Style: Geometric, professional
- Best for: Headings, titles
- License: Open Font License

## Contributing Fonts

If you'd like to contribute a font:
1. Ensure the font has an appropriate license for distribution
2. Include all necessary font files and variations
3. Add font documentation and usage examples
4. Submit a pull request with your contribution
