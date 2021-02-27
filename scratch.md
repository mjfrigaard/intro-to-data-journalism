scratch file
=============

## Change book output to `bs4_book`

Old output

```yml
bookdown::gitbook:
  css: style.css
  config:
    toc:
      before: |
        <li><a href="./">A Minimal Book Example</a></li>
      after: |
        <li><a href="https://github.com/rstudio/bookdown" target="blank">Published with bookdown</a></li>
    edit: https://github.com/rstudio/bookdown-demo/edit/master/%s
    download: ["pdf", "epub"]
```

New output 

source: https://stackoverflow.com/questions/64778429/how-can-i-use-the-new-bs4-theme-in-bookdown

```yml
bookdown::bs4_book:
  theme:
    primary: "#CD2626"
```
