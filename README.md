a LaTeX template for final year project report specialized for Department of
Physics, Faculty of Science, Universiti Malaya.

- ensure LaTeX is installed. Either:
    - online: register on `www.overleaf.com` and copy these files to a new project.
    - windows: `winget install miktex.miktex strawberryperl.strawberryperl` and launch `MikTeX Console` to update packages.
    - ubuntu: `sudo apt install texlive-basic`.
- run `latexmk` to compile, or `lualatex -pvc` to continuously compile.

Make sure to customize the following:

1. `main.tex:49` Date (should be the day of signature in original work declaration),
1. `main.tex:50` Title and `main.tex:52` TitleMS (malay title),
1. `main.tex:52` Author,
1. `main.tex:53` Matric No,
1. `main.tex:54` IC No,
1. `main.tex:95` Symbols and Abbreviations,
1. `frontmatter/original.tex:24` Field of Study,
1. `frontmatter/acknowledgements.tex` Acknowledgements,
1. `content/` Everything in content folder.
