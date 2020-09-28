#### vscode hands-on

---

#### Setup

```
    git config --global user.name "Vardas Pavardė"
    git config --global user.email "pašto_adresas"
```

---

#### Self signed ssl errors

```
    fatal: unable to access .....   SSL certificate problem:
    self signed certificate in certificate chain

    git config --global http.sslVerify false
```

---

#### Setup Install extensions

1. [excel converter to markdown-table](https://github.com/csholmq/vscode-excel-to-markdown-table)
2. Table of content - [TOC](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
3. [pdf viewer](https://github.com/tomoki1207/vscode-pdfviewer)
4. [.md converter to .pdf, .docx, .html](https://github.com/dfinke/vscode-pandoc)

---

##### Setup Pandoc

```
    git config --global diff.docx.textconv pandoc --to=rst
    git config --global diff.odt.textconv pandoc --to=rst
```

Kiekvienoje `git` repositorijos šakniniame kataloge  
sukuriame **.attributes** failą su unix `EOL`

```
    echo "*.docx diff=docx" >> ./.attributes
    echo "*.odt diff=odt" >> ./.attributes
```

---

#### pandoc test

```

    modifikuoti repositorijoje esantį *.docx failą.
    git diff --color-words
    rezultatas: raudonai-žalias

```

---

#### test full devops cycle

1. start from pull - @color[red](allways)
2. create feature branch
3. make changes
4. commit
5. push to remote (gitlab)
6. open Merge request (draft)
7. discuss and review
8. improve your work
9. repeat steps 2-8
10. get "approve"
11. merge - delete branch
12. sync with remote - pull
13. delete local branch

---

#### resources

<https://www.katacoda.com/courses/vscode/playground>

---

## @color[blue](Q) / @color[green](A) ?

---

References
<https://git-scm.com/downloads/guis>
