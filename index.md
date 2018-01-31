# latextemplates

This organization is a collection of various templates and related projects.
The curent focus is on computer science, but other templates or links to other templates are welcome

All templates are open source an can be found at <https://github.com/latextemplates/>.

## Templates hosted under this organization

### Research templates
 * [IEEE] - a quick start template for IEEE publications
 * [LNCS] - a quick start template for the Springer LNCS series

### Thesis templates
 * [scientific-thesis-template] - a template for Bachelor and Master theses
 * [uni-stuttgart-dissertation-template] - a template for dissertations at University of Stuttgart
 * [SAGP] - a template for "[Soziale Arbeit, Gesundheit und Pflege](http://www.hs-esslingen.de/de/hochschule/fakultaeten/soziale-arbeit-gesundheit-und-pflege.html)" of Hochschule Esslingen

### Comparison

| template                              | microtype | hyperref | hypcap   | cleveref | listings | minted | latexindent config | cmap | pdfcomment |
| ------------------------------------- | --------- | -------- | -------- | -------- | -------- | ------ | ------------------ | ---- | ---------- |
| [IEEE]                                | x         | x        | x        | x        | x        | p      | x                  | x    | x          |
| [LNI]                                 | x         | x        | x        | x        | x        | -      | -                  | x    | x          |
| [LNCS]                                | x         | x        | x        | x        | x        | p      | x                  | x    | x          |
| [scientific-thesis-template]          | x         | x        | x        | x        | x        | p      | x                  | x    | x          |
| [uni-stuttgart-dissertation-template] | x         | x        | x        | x        | x        | p      | -                  | -    | x          |

#### Legend

- [microtype] - Better look of the papers. See <http://www.khirevich.com/latex/microtype/> for a longer explanation of microtype's features.
- [hyperref] - Support of hyperlinked references without extra color.
- [hypcap] - Hyperlinks to figures jump to the beginning of the figure and not just to the caption.
- [cleveref] - The most advanced cross-referencing packae. Just type `\cref{xy}` instead of `Fig.~\ref{xy}`. See <https://tex.stackexchange.com/a/36312/9075> for a complete comparison to other referencing packages.
- [listings] - Typeset listings directly in latex.
- [minted] - Source code highlighting like a pro.
  In contrast to listings, it uses [pygments](http://pygments.org/) to highlight code.
  That provides better results.
- [latexindent] config - Ready-to-go configuration to reindent *.tex files
- [cmap] - Generated PDF allows for copy and paste of text without getting words with ligatures such as "workflow" destroyed.
- [pdfcomment] - This is one of those TODO packges. Comments are included in the PDF as separate layer.

| key | meaning |
| --- | ------- |
| x   | included |
| p   | prepared, but not included in default template |
| -   | not included |


## Templates by others
 * <https://github.com/uniba-dsg/dsg-templates> templates for seminars, theses, presentation of the [Distributed Systems Group, Bamberg, Germany](https://www.uni-bamberg.de/pi).
 * See also the templates listed at <https://github.com/latextemplates/scientific-thesis-template/issues/25>.

## Lists of templates
 * <http://www.latextemplates.com/>


## Lists of lists of templates
 * <http://tex.stackexchange.com/questions/1362/latex-template-gallery>
 * the one above

## Other resources hosted at latextemplates

### Introductions to LaTeX
 * German: <https://github.com/latextemplates/latex-tutorium> is a German Latex tutorial abandoned 2005 and resurrected in 2015
 * German: <https://github.com/latextemplates/diplomarbeit-mit-latex> is a German Latex tutorial geared towards diploma thesis

## Other resources
 * [Showcase of beautiful typography done in TeX & friends](http://tex.stackexchange.com/questions/1319/showcase-of-beautiful-typography-done-in-tex-friends)
 * [The TeX showcase](http://www.tug.org/texshowcase/)
 * <http://wiki.flupp.de/latex>

  [IEEE]: https://latextemplates.github.io/IEEE/
  [LNI]: https://github.com/gi-ev/LNI/
  [LNCS]: https://latextemplates.github.io/LNCS/
  [scientific-thesis-template]: https://latextemplates.github.io/scientific-thesis-template/
  [uni-stuttgart-dissertation-template]: https://github.com/latextemplates/uni-stuttgart-dissertation-template
  [SAGP]: https://github.com/latextemplates/SAGP

  [booktabs]: https://www.ctan.org/pkg/booktabs
  [cleveref]: https://ctan.org/pkg/cleveref
  [cmap]: https://www.ctan.org/pkg/cmap
  [csquotes]: https://www.ctan.org/pkg/csquotes
  [hypcap]: https://www.ctan.org/pkg/hypcap
  [hyperref]: https://ctan.org/pkg/hyperref
  [latexindent]: https://ctan.org/pkg/latexindent
  [listings]: https://ctan.org/pkg/listings
  [microtype]: https://ctan.org/pkg/microtype
  [minted]: https://ctan.org/pkg/minted
  [newtx]: https://ctan.org/pkg/newtx
  [paralist]: https://www.ctan.org/pkg/paralist
  [pdfcomment]: https://www.ctan.org/pkg/pdfcomment
  [upquote]: https://www.ctan.org/pkg/upquote
