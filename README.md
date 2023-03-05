# LaTeX Preamble Templates

## Requirements

- TeX distribution ([MikTeX](https://miktex.org/download) for Windows, [TeX Live](https://tug.org/texlive/quickinstall.html) for Linux, etc.)
    - Make sure all the binaries are added to PATH!
- [Visual Studio Code](https://code.visualstudio.com/Download)
- [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension
- [LaTeX Utilities](https://marketplace.visualstudio.com/items?itemName=tecosaur.latex-utilities) extension

## Windows Notes

The GhostScript CLI is installed as `gsw64c.exe`. To ensure compatibility with the settings, rename it to `gs.exe`

Furthermore, the `final` folder must be manually created.

## Linux Notes

To make sure the LaTeX workshop and LaTeX utility extensions can find all the binaries in the path, launch `code` from the command line. For some reason, doing it any other way means code does not get access to the updated PATH variable.