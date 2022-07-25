# Markdown, Markdown everywhere

- [Markdown, Markdown everywhere](#markdown-markdown-everywhere)
  - [Tout écrire en Markdown](#tout-écrire-en-markdown)
  - [*Content first !*](#content-first-)
  - [Les bienfaits du Markdown](#les-bienfaits-du-markdown)
  - [Quelques éléments de syntaxe](#quelques-éléments-de-syntaxe)
    - [Hyperliens](#hyperliens)
    - [Références à une section dans le même document](#références-à-une-section-dans-le-même-document)
    - [Relier tous vos fichiers entre eux](#relier-tous-vos-fichiers-entre-eux)
  - [Éditeurs Markdown](#éditeurs-markdown)
  - [Ressources](#ressources)
    - [Documentation Markdown](#documentation-markdown)
    - [Ecosystème : extensions et usages](#ecosystème--extensions-et-usages)

## Tout écrire en Markdown

>" Easy to write, easy to read ", la philosophie de Markdown

[Markdown](https://daringfireball.net/projects/markdown) est tout simplement le meilleur outil pour créer de la documentation sur tout ce que vous faites sur votre machine. C'est un langage à balises léger. Il s'agit d'un simple fichier texte que l'on peut ouvrir avec n'importe quel éditeur. Facile à lire, facile à écrire. Il a été pensé originellement pour écrire pour le web.

Il est également facile à apprendre, et permet d'exporter votre document vers tout un tas de formats *markup* (HTML, PDF, LaTeX, XML, docx, odt, etc.). Et c'est là où réside tout son intérêt: on écrit **une fois le contenu** et on le **publie plusieurs fois** (vers le web, le papier, une présentation, etc.)

Lorsque l'on découvre les langages à balises sémantiques, on ne peut plus revenir en arrière, car on sent qu'on touche du doigt *une forme de vérité*: la *nécessaire séparation* du *contenu* et de la *forme*.

## *Content first !*

Dans la tradition du web 1.0, Markdown est *content first*, c'est à dire que le but d'un fichier Markdown est de transmettre de l'information avant tout *via du texte*. Et que cette information soit clairement structurée et présentée, et facilement maintenable.

La mise en forme et le contenu sont deux choses différentes. Markdown propose, comme le HTML ou LaTeX, une description sémantique du contenu. C'est à dire qu'il permet de dire avec simplicité et élégance *ce qu'est le contenu* et non *comment afficher ce contenu*. 

Si l'on veut appliquer des styles au contenu on peut le faire, mais pas de manière native à Markdown car ce n'est pas dans son cachier des charges. C'est comme pour le HTML et le CSS, ou le XML et le XLST.

Cela ne vous aura pas échappé, ce document est lui même écrit en Markdown. Comme tous les `README` sur tous les dépôts. Et c'est bien utile car tout de suite ces fichiers nous semblent familiers, car ils ont tous les mêmes règles, la même sémantique, le même style par défaut. Ce qui fait qu'on identifie rapidement les sections, le code, les liens, les listes. Il n'y a pas de ticket d'entrée à payer, comme sur un site web que l'on découvre. 

Ainsi, on va directement à ce qui nous intéresse, le contenu. Et avant toute chose, si l'on va sur le web c'est pour accéder à du contenu de qualité.

## Les bienfaits du Markdown

- de simples fichiers textes que l'on peut ouvrir avec n'importe quel éditeur (même dans 50 ans sur du matériel encore inconnu)
- facile à lire même dans sa source, contrairement à l'HTML ou le XML
- s'adresse à des personnes techniques ou non. Sa syntaxe est tellement simple et intuitive que l'on peut l'apprendre en moins de 10 minutes
- facilement convertible vers tout un tas de format. Écrivez une fois, publiez plusieurs fois
- fait avant tout pour le web
- facile à maintenir, à versionner
- facile de collaborer dessus
- si simple, si puissant
- extensile. Markdown vient avec tout un écosystème d'outils pour créer des environnement de travail utiles et efficaces

## Quelques éléments de syntaxe

### Hyperliens

### Références à une section dans le même document

### Relier tous vos fichiers entre eux


## Éditeurs Markdown

Nous l'avons dit, les fichiers Markdown sont de simples fichiers textes, et donc éditables avec n'importe quel éditeur texte. Cela dit, quelques éditeurs se sont spécialisés dans le Markdown et offrent des fonctionnalités intéressantes (comme la prévisualisation *à chaud* en HTML de notre document).

Une liste non exhaustive d'éditeurs Markdown ou d'extensions pour éditeur

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

### Ecosystème : extensions et usages

- [Diagrammes en Markdown avec mermaid](https://mermaid-js.github.io/mermaid/#/)
- [Markdown slides collection tools](https://gist.github.com/johnloy/27dd124ad40e210e91c70dd1c24ac8c8), une collection de programmes pour convertir vos fichiers Markdown en slides pour une présentation (nécessite souvent un environnement JS *un peu heavy*)
- [Marp écosystème](https://marp.app/), écosystème Markdown pour produire des slides à partir de fichiers Markdown
- [Marpit framework](https://marpit.marp.app/), le programme (le *core*) sur lequel est basé Marp
- [Marpit API](https://marpit-api.marp.app/index.html), l'API de marpit
- [Poc Marp](https://github.com/websealevel/poc-marp), un *proof of concept* de Marp. Le dépôt propose une synthese des possibilités offertes par l'outil via un exemple pratique et pointe vers de la documentation utile
- [With Vimwiki you can](https://vimwiki.github.io/), créez vos wikis directement depuis vim, en utilisant des fichiers Markdown
- [Pandoc: extension pour l'export vers l'HTML](https://pandoc.org/MANUAL.html#extensions)
- [Pandoc: YAML metadata block](https://pandoc.org/MANUAL.html#extension-yaml_metadata_block), extension Pandoc pour ajouter des metadonnées au document (par exemple pour un export HTML)