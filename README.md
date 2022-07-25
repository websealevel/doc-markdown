# Markdown, Markdown everywhere

- [Markdown, Markdown everywhere](#markdown-markdown-everywhere)
  - [Tout écrire en Markdown](#tout-écrire-en-markdown)
  - [*Content first !*](#content-first-)
  - [User friendly](#user-friendly)
  - [Hyperliens](#hyperliens)
    - [Références à une section dans le même document](#références-à-une-section-dans-le-même-document)
    - [Relier tous vos fichiers entre eux](#relier-tous-vos-fichiers-entre-eux)
  - [Éditeurs markdown](#éditeurs-markdown)
  - [Ressources](#ressources)
    - [Documentation Markdown](#documentation-markdown)
    - [Extensions et usages](#extensions-et-usages)
    - [Export](#export)

## Tout écrire en Markdown

Trouver le bon moyen de documenter tout un tas de choses n'est pas chose aisée au premier abord. Quand on découvre les langages à balises sémantiques, comme [Latex](https://www.latex-project.org/), on ne peut plus revenir en arrière car on sent qu'on touche du doigt *une forme de vérité*: la nécessaire séparation du contenu et de la forme.

Mais Latex est orienté édition papier, ce qu'il fait à merveille. Pour le web, ou pour de la documentation, il y a d'autres outils. [Markdown](https://daringfireball.net/projects/markdown/) en est le maître incontesté, loin devant le HTML.

Markdown peut etre converti vers

- HTML bien sûr
- PDF
- Impression papier à partir du PDF ou HTML
- JSON
- XML
- Latex
- odt
- docx
- etc...

## *Content first !*

>"Easy to write, easy to read", la philosophie de Markdown

Dans la tradition du web 1.0, Markdown est *content first*, c'est à dire que le but d'un fichier Markdown est de transmettre de l'information avant tout *via du texte*. Et que cette information soit clairement structurée et présentée, et facilement maintenable.

La mise en forme et le contenu sont deux choses différentes. Markdown propose, comme le HTML ou LaTeX, une description sémantique du contenu. C'est à dire qu'il permet de dire avec simplicité et élégance *ce qu'est le contenu* et non *comment afficher ce contenu*. 

Si l'on veut appliquer des styles au contenu on peut le faire, mais pas de manière native à Markdown car ce n'est pas dans son cachier des charges. C'est comme pour le HTML et le CSS, ou le XML et le XLST.

Cela ne vous aura pas échappé, ce document est lui même écrit en Markdown. Comme tous les `README` sur tous les dépôts. Et c'est bien utile car tout de suite ces fichiers nous semblent familiers, car ils ont tous les mêmes règles, la même sémantique, le même style par défaut. Ce qui fait qu'on identifie rapidement les sections, le code, les liens, les listes. Il n'y a pas de ticket d'entrée à payer, comme sur un site web que l'on découvre. 

Ainsi, on va directement à ce qui nous intéresse, le contenu. Et avant toute chose, si l'on va sur le web c'est pour accéder à du contenu de qualité.

## User friendly

- Facile à lire même dans sa source, contrairement à l'HTML ou le XML
- Sa syntaxe est intuitive et on peut l'apprendre en moins de 10 minutes
- Facilement convertible vers tout un tas de format
- Fait avant tout pour le web
- Utilisation dans beaucoup de contextes : les fichiers README sur les dépots ou dans les packages, wiki, publications webs, documentation etc...
- facile à maintenir
- si simple, si puissant

## Hyperliens

### Références à une section dans le même document

### Relier tous vos fichiers entre eux

## Éditeurs markdown

Une liste non exhaustive d'éditeurs markdown ou d'extensions pour éditeur

- [ReText](https://github.com/retext-project/retext)
- [ghostwriter](https://wereturtle.github.io/ghostwriter/)
- [Extension vscode Markdown all in one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

## Ressources

### Documentation Markdown

- [Site officiel du projet Markdown](https://daringfireball.net/projects/markdown/)
- [Toute la documentation sur Markdown](https://www.markdownguide.org)
- [Apprendre la syntaxe](https://www.markdownguide.org/basic-syntax)
- [Aller plus loin, syntaxe étendue](https://www.markdownguide.org/extended-syntax/)
- [Antisèche, toute la syntaxte en un clin d'oeil et sur la même page](https://www.markdownguide.org/cheat-sheet/)

### Extensions et usages

- [Diagrammes en Markdown avec mermaid](https://mermaid-js.github.io/mermaid/#/)
- [Markdown slides collection tools](https://gist.github.com/johnloy/27dd124ad40e210e91c70dd1c24ac8c8), une collection de programmes pour convertir vos fichiers Markdown en slides pour une présentation (nécessite souvent un environnement JS *un peu heavy*)
- [Marp écosystème](https://marp.app/), écosystème Markdown pour produire des slides à partir de fichiers Markdown
- [Marpit framework](https://marpit.marp.app/), le programme (le *core*) sur lequel est basé Marp
- [Marpit API](https://marpit-api.marp.app/index.html), l'API de marpit
- [Poc Marp](https://github.com/websealevel/poc-marp), un *proof of concept* de Marp. Le dépôt propose une synthese des possibilités offertes par l'outil via un exemple pratique et pointe vers de la documentation utile
- [With Vimwiki you can](https://vimwiki.github.io/), créez vos wikis directement depuis vim, en utilisant des fichiers Markdown

### Export

- [Pandoc: extension pour l'export vers l'HTML](https://pandoc.org/MANUAL.html#extensions)