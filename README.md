A template to create JupyterBooks hosted on GitHub
JupyterBook is hosted on the GitHub Pages of the repo

## Contents
Contains: 
- jupyter-book within `new_book\`
- GitHub Actions workflow within `.github\workflows\main.yml


## Packages necessary:
- jupyter-book

[JupyterBook](https://jupyterbook.org/en/stable/intro.html): "Build beautiful, publication-quality books and documents from computational content." 


Steps to use:
- create GitHub repo
- enable GitHub Pages (`Settings` -> `Pages`, set `Source` to `GitHub Actions`)
- `git push` files to your repo
- install packages
- edit for your needs

This template book is hosted at [link](https://jewels2001.github.io/jupyter-book-clean/)




### *comments*
Uses virtual environment `jupyter-book-env`
- Windows: `jupyter-book-env\Scripts\activate`
- MacOS/Linux: `source jupyter-book-env/bin/activate`