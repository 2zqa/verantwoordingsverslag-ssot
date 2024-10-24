# Verantwoordingsverslag SSOT bronbestanden

Verantwoordingsverslag en bijlagen voor het afstuderen bij [Voys](https://www.voys.nl/) door Marijn Kok

> [!NOTE]
> For English readers: this repository contains the source files for the accountability report and its appendices for my graduation project at [Voys](https://www.voys.nl/). The report is written in Dutch.
>
> For all related projects, see this search query: [`owner:2zqa topic:ssot`](https://github.com/search?q=owner%3A2zqa+topic%3Assot&type=repositories)

## Afhankelijkheden

- latexmk
- biber
- texlive-bibtex-extra
- texlive
- texlive-lang-european
- texlive-latex-extra
- _(optioneel)_ chktex

```bash
$ sudo apt install latexmk biber texlive texlive-lang-european texlive-bibtex-extra chktex
```

## Compileren

Om een PDF-bestand te compileren, voer het volgende commando uit in de respectievelijke map (bijvoorbeeld `report`):

```bash
$ latexmk -pdf <file>.tex
```

Dit commando zal een PDF-bestand genereren met de naam `<file>.pdf`.

## Bewerken

Voor het schrijven van dit verslag zijn Tex Live, Visual Studio Code, de [LaTeX Workshop extensie](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) en Ubuntu 20.04 LTS gebruikt.

Daarnaast zijn de volgende configuraties toegepast in Visual Studio Code's `settings.json`:

```json
{
  "[latex]": {
    "editor.rulers": [80],
    "editor.wordWrap": "wordWrapColumn",
    "editor.suggest.showWords": false
  },
  "latex-workshop.latex.rootFile.useSubFile": false,
  "latex-workshop.latex.rootFile.doNotPrompt": true
}
```
