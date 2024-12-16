a LaTeX template for final year project report specialized for Department of
Physics, Faculty of Science, Universiti Malaya.

- ensure LaTeX is installed. Either:
    - online: register on `www.overleaf.com` and copy these files to a new project.
    - windows: `winget install miktex.miktex` and launch `MikTeX Console`.
    - ubuntu: `sudo apt install texlive-basic`.
- run `latexmk --lualatex`

Make sure to customize the following:

1. `main.tex:50` Date (should be the day of signature in original work declaration),
1. `main.tex:51` Title and `main.tex:52` TitleMS (malay title),
1. `main.tex:53` Author,
1. `main.tex:54` Matric No,
1. `main.tex:55` IC No,
1. `frontmatter/original.tex:24` Field of Study,
1. `frontmatter/acknowledgements.tex` Acknowledgements,
1. `content/` Everything in content folder.
