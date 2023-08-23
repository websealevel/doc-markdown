# Markdown, Markdown everywhere

- [Markdown, Markdown everywhere](#markdown-markdown-everywhere)
  - [Tout écrire en Markdown](#tout-écrire-en-markdown)
  - [*Content first !*](#content-first-)
  - [Les bienfaits du Markdown](#les-bienfaits-du-markdown)
  - [Éditeurs Markdown](#éditeurs-markdown)
  - [Ressources](#ressources)
  - [Apprendre](#apprendre)
    - [Outils, extensions, workflows](#outils-extensions-workflows)

## Tout écrire en Markdown

>" Easy to write, easy to read ", la philosophie de Markdown

[Markdown](https://daringfireball.net/projects/markdown) est tout simplement le meilleur outil pour créer de la documentation sur tout ce que vous faites sur votre machine (journal, base de données personnelles, prise de notes, documents, wiki, etc.). C'est *un langage à balises léger*. Markown est un langage à balise comme le HTML ou le XML, mais il est beaucoup plus simple afin de rendre la source lisible facilement. Il s'agit d'un simple fichier texte que l'on peut ouvrir avec n'importe quel éditeur. Facile à lire, facile à écrire. Il a été pensé originellement pour écrire *pour le web*.

Il est également facile à apprendre, et permet d'exporter votre document vers tout un tas de formats *markup* (HTML, PDF, LaTeX, XML, docx, odt, etc.). Et c'est là où réside tout son intérêt: on écrit **une fois le contenu** et on le **publie plusieurs fois** (vers le web, le papier, une présentation, etc.)

Lorsque l'on découvre les langages à balises sémantiques, on ne peut plus revenir en arrière, car on sent qu'on touche du doigt *une forme de vérité*: la *nécessaire séparation* du *contenu* et de la *forme*.

## *Content first !*

Dans la tradition du web 1.0, Markdown est *content first*, c'est à dire que le but d'un fichier Markdown est de transmettre de l'information avant tout *via du texte*. Et que cette information soit clairement structurée et présentée, et facilement maintenable.

La mise en forme et le contenu sont deux choses différentes. Markdown propose, comme le HTML ou LaTeX, une description sémantique du contenu. C'est à dire qu'il permet de dire avec simplicité et élégance *ce qu'est le contenu* et non *comment afficher ce contenu*. 

Si l'on veut appliquer des styles au contenu on peut le faire, mais pas de manière native à Markdown car ce n'est pas dans son cachier des charges. C'est comme pour le HTML et le CSS, ou le XML et le XLST.

Cela ne vous aura pas échappé, ce document est lui même écrit en Markdown. Comme tous les `README` sur tous les dépôts. Et c'est bien utile car tout de suite ces fichiers nous semblent familiers, car ils ont tous les mêmes règles, la même sémantique, le même style par défaut. Ce qui fait qu'on identifie rapidement les sections, le code, les liens, les listes. Il n'y a pas de ticket d'entrée à payer, comme sur un site web que l'on découvre. 

Ainsi, on va directement à ce qui nous intéresse, le contenu. Et avant toute chose, si l'on va sur le web c'est pour accéder à du contenu de qualité.

## Les bienfaits du Markdown

- De simples fichiers textes que l'on peut ouvrir avec n'importe quel éditeur (même dans 50 ans sur du matériel encore inconnu)
- Facile à lire même dans sa source, contrairement à l'HTML ou le XML
- S'adresse à des personnes techniques ou non. Sa syntaxe est tellement simple et intuitive que l'on peut l'apprendre en moins de 10 minutes
- Facilement convertible vers tout un tas de format. Écrivez une fois, publiez plusieurs fois
- Fait avant tout pour le web
- Facile à maintenir, à versionner
- Facile de collaborer dessus
- Si simple, si puissant
- Extensile. Markdown vient avec tout un écosystème d'outils pour créer des environnement de travail utiles et efficaces


## Éditeurs Markdown

Nous l'avons dit, les fichiers Markdown sont de simples fichiers textes, et donc éditables avec *n'importe quel éditeur texte*. Cela dit, quelques éditeurs se sont spécialisés dans le Markdown et offrent des fonctionnalités intéressantes (comme la prévisualisation *à chaud* en HTML de notre document).

Une liste non exhaustive d'éditeurs Markdown ou d'extensions pour éditeur :

- [ReText](https://github.com/retext-project/retext)
- [Ghostwriter](https://wereturtle.github.io/ghostwriter/)
- [Extension vscode Markdown all in one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

## Ressources

## Apprendre

- [CommonMark](https://commonmark.org/), [une spécification Markdown](https://spec.commonmark.org/) créée en 2004 par John Gruber et Aaron Swartz, implémentée dans de nombreux langages de programmation, l'implémentation markdown sûre
- [Apprendre CommonMark en quelques minutes](https://commonmark.org/help/)
- [Site officiel du projet Markdown](https://daringfireball.net/projects/markdown/)
- [Toute la documentation sur Markdown](https://www.markdownguide.org)
- [Apprendre la syntaxe](https://www.markdownguide.org/basic-syntax)
- [Aller plus loin, syntaxe étendue](https://www.markdownguide.org/extended-syntax/)
- [Antisèche, toute la syntaxe sur une page](https://www.markdownguide.org/cheat-sheet/)

### Outils, extensions, workflows

- [marpit](https://marpit.marp.app/), framework minimal pour créer des présentations en Markdown.
- [Mark Doc](https://markdoc.io/), superset et framework Markdown, open-source, orienté publication de contenu. L'outil a été développé par Stripe, pour développer et maintenir sa documentation structurée, complexe et de qualité.
- [Babel Mark 3](https://babelmark.github.io/), la spécification originale de Markdown ([proposée par John Gruber](https://daringfireball.net/projects/markdown/syntax)) n'étant pas complète, de nombreuses implémentations de Markdown existent avec leurs spécificités. [Babel Mark 3](https://babelmark.github.io/) vous permet de comparer le résultat (HTML) de nombreuses implémentations de Markdown  
- [Marp](https://marp.app/), créer ses diapos dans un écosystème full Markdown. Réutiliser ainsi facilement le contenu structuré de vos présentations pour les publier en PDF ou HTML, ou inversement. Basé sur [Marpit](https://marpit.marp.app/), 
- [Poc Marp](https://github.com/websealevel/poc-marp), un dépôt simple qui sert de référence sur l'usage de marp
- [Revealjs](https://revealjs.com/), un autre outil, plus lourd mais permettant de faire des présentations plus complexes, basé sur javascript. Creer des présentations pour le web mais pas que. Et surtout générer des présentations directement à partir de vos notes en Markdown.
- [Slides](https://slides.com/), si vous êtes plutôt éditeur graphique/GUI slides vous permet de créer vos présentations à la main grâce à un éditeur de qualité, et vous les heberge en ligne.
- [Diagrammes en Markdown avec mermaid](https://mermaid-js.github.io/mermaid/#/)
- [Markdown slides collection tools](https://gist.github.com/johnloy/27dd124ad40e210e91c70dd1c24ac8c8), une collection de programmes pour convertir vos fichiers Markdown en slides pour une présentation (nécessite souvent un environnement JS *un peu heavy*)