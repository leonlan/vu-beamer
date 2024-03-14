# VU Beamer slides
$\LaTeX$ Beamer template using the corporate identity (_huisstijl_) of Vrije Universiteit Amsterdam. 

## How to use
### As a new project in Overleaf
[Download](https://github.com/leonlan/vu-beamer/archive/refs/heads/main.zip) this repository as a zip file and upload it to Overleaf. 
See `main.pdf` for an example.

### Use theme in existing project
If you want to only use `vu-beamer` as theme on your existing project, then download the `vu-beamer` folder and add it to your project with `\usepackage{vu-beamer/vu-beamer}`.

Here is a minimal example that should work:

``` tex
\documentclass{beamer}
\usepackage{vu-beamer/vu-beamer}

\begin{document}

\begin{frame}{First frame}
...
\end{frame}

\end{document}
```



## Other
- See Chapter 5 of [Beamer user guide](https://tug.ctan.org/macros/latex/contrib/beamer/doc/beameruserguide.pdf) for very helpful tips about presenting.
- See [VU Brandportal](https://brandportal.vu.nl/modules/product/DigitalStyleGuide/default/grouplist.aspx?ItemId=6739&iflc=en&ifcltr=en)
for more information on VU's branding.

