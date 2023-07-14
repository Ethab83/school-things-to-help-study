# school-things-to-help-study

Some school things I made that anyone can use

I wrote these using pandoc's markdown with some extra options. I used the following command to convert them to pdf:

```bash
/usr/local/bin/pandoc "$filename".md -o "$filename".pdf -t pdf \
    -f markdown+implicit_figures \
    --pdf-engine=/Library/TeX/texbin/xelatex
```

Short Pandoc Installation Guide (MacOS):

1. Install [Homebrew](https://brew.sh/).
2. Install pandoc using Homebrew: `brew install pandoc`
3. Install LaTeX using Homebrew: `brew cask install basictex`

Useful resources for pandoc:

| Resource                                                                                                             | Description                                                          |
|----------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|
| [Pandoc User's Guide](https://pandoc.org/MANUAL.html)                                                                | The official user's guide for pandoc.                                |
| [Pandoc Markdown](https://pandoc.org/MANUAL.html#pandocs-markdown)                                                   | The official documentation for pandoc's markdown.                    |
| [Generic Preprocessor](https://pandoc.org/filters.html#generic-preprocessor)                                         | The official documentation for pandoc's generic preprocessor.        |
| [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)                | A VSCode extension that adds some useful features to markdown files. |
| [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) | A VSCode extension that adds some useful features to markdown files. |
