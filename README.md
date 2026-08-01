# s/v Pacific Loon — documents

Equipment manuals and reference documents for the sailing vessel Pacific Loon.

**The boat's documentation lives in [the wiki](https://github.com/hishma/svpacificloon/wiki).** This repo holds only the source documents the wiki links to — vendor PDFs and screenshots, which a GitHub wiki cannot render or store usefully.

## Linking to a document

Link the **blob** URL, not the raw one. GitHub renders PDFs in its own viewer at the blob URL, so the manual opens in the browser:

```
https://github.com/hishma/svpacificloon/blob/main/manuals/Simrad%20AP16%20Manual.pdf
```

`raw.githubusercontent.com` serves PDFs as `text/plain`, so raw links garble or download them. Spaces in filenames must be `%20`.

## Layout

```
manuals/
  <vendor manuals, loose>
  Orca/
  Zeus2/            software addenda by version
  Vesper AIS settings (old)/   configuration screenshots, 2021
```

## History

This repo previously held a Jekyll site for svpacificloon.com. That site now runs on Bear Blog; the Jekyll source remains in git history up to commit `4e9165b`.
