# Custom Jupyter-Book CSS
Recently came across [jupyter-book](https://jupyterbook.org/intro.html) and thought it would great for having my notes output in a consistent, book-like, format; which I can then also upload as a static site, effortlessly. Special thing about jupyter-book is that it can be used for other things, among notes, as it integrates Jupyter Notebooks.

This repo contains my custom CSS for the jupyter-books that I create, as the default theme, while great, was lacking a few styling tweaks for me, personally. I've also created a small script; when executed, replaces the required CSS files (with the custom ones) in the desired jp-book directory.

Styling inspired by [HonKit](https://honkit.netlify.app/).

## Preview
Tbc

## Requirements
- Font stack from [Nerd-Fonts](https://github.com/ryanoasis/nerd-fonts); haven't tested how it would be without nerd-fonts.

## JP-Book Style Guide
Personal style guide when writing jupyter-books:
- Avoid `code blocks` in headings.
- Avoid more than 1 nested list.
- Separate single line of code (in fenced code blocks) if it's too long/exceeds width.
- Do not start a section with a list. Doesn't look good.

## TODO
- Pre-package the fonts in use and define font-face
