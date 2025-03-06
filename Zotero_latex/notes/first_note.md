---
title: éditeur vs traitement de texte
bibliography: biblio/biblio.bib
---


notes de Marcello Vitali-Rosati (@aksoyWhatEpidemicsTell2020)

```shell
echo @note_path
```

```shell
mkdir -p pdf
file=${@note_path}
pandoc --from markdown "$file" --citeproc --pdf-engine=xelatex -o "pdf/$(basename "${file%.*}").pdf"
```
