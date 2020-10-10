# vscode-devcontainer-latex

This devcontainer runs TexLive for creating LaTeX documents and contains a way to turn your LaTeX files in PDF files which are uploaded as asset of your release.

## Examples

### article.tex

### book.tex

### presentation.tex

## Tweaks

### BibTex for RFCs


```shell
$ curl --silent -k -o rfc.bib https://tm.uka.de/~bless/rfc.bib
$ ls -l rfc.bib
-rw-r--r--. 1 vscode vscode 8431188 Aug 23 11:06 rfc.bib
```
