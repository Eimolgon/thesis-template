Thesis template
===============

This is a modular thesis template for LaTeX.


Top line colors
---------------

- `\chaptercolor{RoyalBlue}`
- `\chaptercolor{blue!70!black}`
- ```
\definecolor{delftblue}{RGB}{0,82,147}
\chaptercolor{delftblue}
```


Glossary
--------

```
\newglossaryentry{bicycle}{
    name={bicycle},
    description={A human-powered vehicle with two wheels}
}
```

or 

`\newacronym{gps}{GPS}{Global Positioning System}`

and to use it

`\gls{bicycle}`

