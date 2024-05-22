---
# try also 'default' to start simple
theme: apple-basic
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides, markdown enabled
title: Welcome to Digital culture
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

# Faut -il être à la pointe des nouveaux frameworks JS et des tendances web pour être un bon développeur

Digital culture<br>
Georgina Berrezel - M1 Dev

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->


<!--
Here is another comment.
-->

---
transition: fade-out
layout: two-cols
layoutClass: gap-16
---

# Summary

Do you have to be up to date with the latest JS frameworks and web trends to be a good developer?

Dans un domaine en constante évolution comme le développement web, les nouvelles technologies et les frameworks
JavaScript émergents suscitent des questions sur l'importance d'être à jour. Les attentes croissantes des utilisateurs
en matière de performance stimulent l'innovation et la compétition entre les frameworks, tandis que l'IA rend des outils
avancés accessibles à tous les niveaux de compétence. Ces facteurs redéfinissent le paysage du développement web et le
rôle du développeur moderne.

::right::

<Toc v-click minDepth="1" maxDepth="2"></Toc>


---
transition: slide-up
level: 2
---

# 📈L’évolution des frameworks JS et la quête de performance

<img src="stateofjs-awarness.png" alt="Awarness state of javascript 2022" style="max-width: 100%; height: auto;"/>

[//]: # ()

[//]: # (## Keyboard Shortcuts)

[//]: # ()

[//]: # (|                                                     |                             |)

[//]: # (|-----------------------------------------------------|-----------------------------|)

[//]: # (| <kbd>right</kbd> / <kbd>space</kbd>                 | next animation or slide     |)

[//]: # (| <kbd>left</kbd>  / <kbd>shift</kbd><kbd>space</kbd> | previous animation or slide |)

[//]: # (| <kbd>up</kbd>                                       | previous slide              |)

[//]: # (| <kbd>down</kbd>                                     | next slide                  |)

<!-- https://sli.dev/guide/animations.html#click-animations -->
<img
v-click
class="absolute -bottom-9 -left-7 w-80 opacity-50"
src="https://sli.dev/assets/arrow-bottom-left.svg"
alt=""
/>
<p v-after class="absolute bottom-23 left-45 opacity-30 transform -rotate-10">Here!</p>


---
layout: image-right
image: ./stateofjs-ratio-overtime.png
---

# I - Demande croissante de performance

Les utilisateurs attendent des applications web rapides et réactives, ce qui pousse les développeurs à utiliser des
frameworks qui optimisent les performances.

---
transition: slide-up
level: 3
---

I - Demande croissante de performance

# A - Les attentes des utilisateurs modernes

Les utilisateurs d'aujourd'hui ont des attentes élevées en matière de performance des applications web. Plusieurs
facteurs contribuent à cette demande croissante :

`Vitesse de chargement`

<div v-click>

```html

<div v-click>Les utilisateurs s'attendent à des pages web qui se chargent en quelques secondes, essentielles pour une
    bonne expérience utilisateur et pour le référencement.
</div>
```

</div>

<br>

<v-click>

<span v-mark.red="3"><code>Réactivité</code></span>

[//]: # (also allows you to add)

[//]: # (<span v-mark.circle.orange="4">inline marks</span>)

[//]: # (, powered by [Rough Notation]&#40;https://roughnotation.com/&#41;:)

```html
<span v-mark.underline.orange>Les interactions avec le site doivent être fluides et instantanées une fois la page chargée. (par exemple, des
formulaires, des boutons, etc.).</span>
```

</v-click>

<div mt-20 v-click>

[Learn More](https://sli.dev/guide/animations#click-animations)

</div>

---

A - Les attentes des utilisateurs modernes

`Expérience utilisateur (UX)`

<div v-click>

```html

<div v-click>Une performance optimale est cruciale pour une expérience utilisateur positive, car les utilisateurs sont
    moins tolérants envers les sites lents ou non réactifs.
</div>
```

</div>


---

I - Demande croissante de performance

# B - Rôle des frameworks JavaScript

Les frameworks modernes optimisent les performances web de plusieurs manières :

`Rendu côté client vs côté serveur`

<div v-click>

```html

<div v-click>Certains permettent un rendu côté serveur (SSR) ou statique, réduisant le temps de chargement initial.
</div>
```

</div>

<br>

`Chargement paresseux (Lazy Loading)`

<div v-click>

```html

<div v-click> Techniques pour retarder le chargement de contenu non critique, améliorant le temps de chargement initial
    et la bande passante.
</div>
```

</div>

---

I - Demande croissante de performance

B - Rôle des frameworks JavaScript

`Gestion de l'état efficace`

<div v-click>

```html

<div v-click>Solutions sophistiquées minimisant les recalculs et re-rendus, assurant des interactions rapides et
    fluides.
</div>
```

</div>

<br>

`Optimisation des bundles`

<div v-click>

```html

<div v-click>Outils intégrés pour créer des bundles JavaScript optimisés, réduisant la taille des fichiers et améliorant
    les temps de chargement.
</div>
```

</div>


---

I - Demande croissante de performance

# C - Exemples de frameworks performants

`React`

<div v-click>

```html

<div v-click>Utilisé par des géants comme Facebook et Instagram, il offre des interfaces utilisateur réactives grâce à
    son DOM virtuel et ses mises à jour efficaces
</div>
```

</div>

<br>

`Vue.js`

<div v-click>

```html

<div v-click>Connu pour sa simplicité, il propose des optimisations de performance avec son DOM virtuel et sa gestion de
    composants légers.
</div>
```

</div>

---

`Svelte`

<div v-click>

```html

<div v-click>Convertit les composants en code JavaScript ultra-optimisé à la compilation, améliorant la performance sans
    nécessiter de DOM virtuel.
</div>
```

</div>

<br>

`Angular`

<div v-click>

```html

<div v-click>Framework complet avec des outils pour optimiser les performances, notamment l'injection de dépendances et
    le rendu côté serveur.
</div>
```

</div>


En conclusion
<br>
La demande croissante de performances web pousse les développeurs à adopter des frameworks modernes
offrant des outils pour répondre aux attentes des utilisateurs en matière de vitesse, de réactivité et d'expérience
utilisateur de qualité.



<!--
Notes can also sync with clicks

[click] This will be highlighted after the first click

[click] Highlighted with `count = ref(0)`

[click:3] Last click (skip two clicks)
-->

---
layout: image-left
image: ./stateofjs-ratio-overtime.png
---

# II - Innovation et compétition entre les frameworks

Différentes options de frameworks JS disponibles, de leur évolution constante pour répondre aux besoins
changeants du marché et de la compétition entre eux pour attirer les
développeurs.

---
level: 2
---

II - Innovation et compétition entre les frameworks

# A - Diversité des options disponibles

Le paysage des frameworks JavaScript est riche et diversifié, offrant de nombreuses options aux développeurs. Voici
quelques-uns des principaux frameworks et leurs caractéristiques distinctives :

`React`

<div v-click>

```html

<div v-click>Créé par Facebook, il se concentre sur les interfaces utilisateur réactives grâce à son DOM virtuel
    innovant.
</div>
```

</div>

<br>

`Angular`

<div v-click>

```html

<div v-click>Proposé par Google, il offre une architecture robuste et des outils complets pour les applications web
    complexes.
</div>
```

</div>

---

A - Diversité des options disponibles

`Vue.js`

<div v-click>

```html

<div v-click>Reconnu pour sa simplicité et sa flexibilité, il combine les meilleures fonctionnalités de React et
    Angular.
</div>
```

</div>

<br>

`Svelte`

<div v-click>

```html

<div v-click>Compile les composants en JavaScript pur lors de la construction, évitant ainsi le besoin d'un DOM virtuel
    et optimisant les performances.
</div>
```

</div>

---

II - Innovation et compétition entre les frameworks

# B - Évolution constante pour répondre aux besoins du marché

Les frameworks JavaScript évoluent constamment pour s'adapter aux besoins changeants des développeurs et du marché.
Voici quelques-unes des tendances et évolutions récentes :

`Performance`

<div v-click>

```html

<div v-click>Les frameworks se concentrent sur l'optimisation du rendu et des temps de chargement pour des expériences
    utilisateur plus fluides.
</div>
```

</div>

<br>

`Modularité et extensibilité`

<div v-click>

```html

<div v-click>Les frameworks deviennent modulaires pour permettre une personnalisation accrue et une maintenance
    simplifiée.
</div>
```

</div>

---

B - Évolution constante pour répondre aux besoins du marché

`TypeScript`

<div v-click>

```html

<div v-click>De plus en plus adopté, il améliore la qualité du code et réduit les erreurs grâce à ses types statiques.
</div>
```

</div>

<br>

`Outillage et écosystème`

<div v-click>

```html

<div v-click> L'écosystème s'enrichit avec des outils pour le routage, les tests, etc., améliorant la productivité des
    développeurs.
</div>
```

</div>

---

II - Innovation et compétition entre les frameworks

# C - Compétition entre les frameworks

La compétition entre les frameworks JavaScript est intense et se manifeste de plusieurs manières :

`Communauté et support`

<div v-click>

```html

<div v-click> Les frameworks rivalisent pour attirer des communautés actives, offrant ainsi plus de ressources et de
    support aux développeurs.
```

</div>

<br>

`Adoption par les entreprises`

<div v-click>

```html

<div v-click> La compétition se joue également sur l'adoption par les grandes entreprises, qui peut servir de validation
    de la fiabilité et de la performance d'un framework.
</div>
```

</div>

---

C - Évolution constante pour répondre aux besoins du marché

`Innovation technologique`

<div v-click>

```html

<div v-click>Chaque framework cherche à se démarquer par l'innovation, comme le DOM virtuel pour React ou la compilation
    vers JavaScript pur pour Svelte.
</div>
```

</div>

<br>

`Simplicité et courbe d'apprentissage`

<div v-click>

```html

<div v-click>Les frameworks rivalisent pour offrir la meilleure expérience développeur avec des API intuitives et une
    documentation claire, à l'image de Vue.js et sa simplicité appréciée.
</div>
```

</div>

---

II - Innovation et compétition entre les frameworks

# D - Exemples concrets de compétition

`React vs Angular`

<div v-click>

```html

<div v-click>React se concentre sur la bibliothèque pour les vues, tandis qu'Angular offre une solution complète avec
    tout intégré.
```

</div>

<br>

`Vue.js vs Svelte`

<div v-click>

```html

<div v-click>Vue.js est flexible et facile à apprendre, tandis que Svelte se distingue par son approche de compilation
    unique.
</div>
```

</div>

En conclusion<br>
L'innovation et la compétition entre les frameworks JavaScript stimulent le progrès technologique et offrent aux
développeurs une multitude d'options pour répondre à leurs besoins spécifiques. Cette dynamique concurrentielle
contribue à l'amélioration continue des outils et des pratiques de développement web.

---
transition: slide-up
level: 2
---

# 🤓 Le cliché du développeur junior vs senior

Dans le développement web, on distingue souvent entre les juniors et les seniors. Cette classification peut influencer
les rôles et les attentes, mais elle ne représente pas toujours la réalité complexe de chaque développeur.

<img src="podcast-grafikart.png" alt="Awarness state of javascript 2022" style="max-width: 100%; height: auto;"/>

---
level: 2
---

---
layout: image-left
image: ./podcast-talk.png
---

---
level: 2
---

# I - Les attentes et les réalités

Les développeurs juniors et seniors sont souvent perçus de manière stéréotypée, avec des attentes spécifiques et parfois
irréalistes qui ne reflètent pas toujours la réalité du terrain.

A - Attentes envers les développeurs juniors

`Familiarité avec les nouvelles technologies`

<div v-click>

```html

<div v-click>Il est souvent attendu que les développeurs juniors soient à jour avec les dernières tendances et
    technologies, notamment les nouveaux frameworks et bibliothèques JavaScript. Leur formation récente et leur
    immersion dans des environnements académiques ou de formation continue leur permettent souvent de connaître les
    outils les plus modernes.
</div>
```

</div>

<br>

`Adaptabilité et apprentissage rapide`

<div v-click>

```html

<div v-click>On suppose que les juniors peuvent rapidement s'adapter à de nouvelles technologies et méthodes de travail.
</div>
```

</div>


---

A - Attentes envers les développeurs juniors

`Énergie et enthousiasme`

<div v-click>

```html

<div v-click>Les employeurs attendent des juniors qu'ils apportent une énergie et un enthousiasme nouveaux à l'équipe.
```

</div>

---

I - Les attentes et les réalités

# B - Réalités pour les développeurs juniors

`Manque d'expérience pratique`

<div v-click>

```html

<div v-click>Malgré leur familiarité avec les nouvelles technologies, les juniors peuvent manquer d'expérience pratique
    pour résoudre des problèmes complexes dans des situations réelles.
</div>
```

</div>

<br>

`Besoin de mentorat`

<div v-click>

```html

<div v-click>Les juniors ont souvent besoin de mentorat pour naviguer dans des projets complexes et développer leurs
    compétences professionnelles.
</div>
```

</div>


---

B - Réalités pour les développeurs juniors

`Risque de sur-spécialisation`

<div v-click>

```html

<div v-click>Se concentrer uniquement sur les nouvelles technologies peut les priver de la compréhension des
    fondamentaux de l'informatique et du développement logiciel, limitant ainsi leur adaptabilité.
```

</div>

---

I - Les attentes et les réalités

# C - Attentes envers les développeurs seniors

`Expérience et expertise`

<div v-click>

```html

<div v-click>Les seniors sont attendus pour leur vaste expérience en développement logiciel, qui leur permet de prendre
    des décisions éclairées et de résoudre efficacement des problèmes complexes.
</div>
```

</div>

<br>

`Leadership et mentorat`

<div v-click>

```html

<div v-click>Ils doivent jouer un rôle de leader en guidant les juniors et en prenant des responsabilités pour la
    qualité du code, l'architecture des systèmes, et la gestion des projets.
</div>
```

</div>

---

C - Attentes envers les développeurs seniors

`Fiabilité et stabilité`

<div v-click>

```html

<div v-click>Les seniors sont perçus comme des piliers de l'équipe, capables de fournir des solutions robustes et de
    maintenir la stabilité du codebase sur le long terme.
```

</div>

---

I - Les attentes et les réalités

# D - Réalités pour les développeurs seniors

`Connaissance des nouvelles technologies`

<div v-click>

```html

<div v-click>Malgré leur expérience, les seniors peuvent ne pas être toujours à jour avec les toutes dernières
    technologies et tendances. Leur expertise se concentre souvent sur des outils et méthodes éprouvés qui ont fait
    leurs preuves au fil du temps.
</div>
```

</div>

<br>

`Charge de responsabilités`

<div v-click>

```html

<div v-click>Les seniors peuvent être submergés par des responsabilités de gestion de projet, de leadership d'équipe et
    de mentorat, ce qui peut limiter le temps qu'ils peuvent consacrer à l'apprentissage de nouvelles technologies.
</div>
```

</div>


---

D - Réalités pour les développeurs seniors

`Équilibre entre innovation et stabilité`

<div v-click>

```html

<div v-click>Ils doivent trouver un équilibre entre l'adoption de nouvelles technologies pour améliorer les performances
    et la stabilité des systèmes existants, sachant que l'introduction de nouvelles technologies peut introduire des
    risques et des coûts de transition.
```

</div>

Conclusion<br>
Les attentes envers les développeurs juniors et seniors reflètent une vision idéale qui ne correspond pas toujours à la
réalité. Les juniors, bien que familiers avec les nouvelles technologies, ont besoin de développer leur expérience
pratique et leurs compétences en résolution de problèmes. Les seniors, malgré leur expérience et expertise, doivent
constamment équilibrer entre innovation et stabilité, tout en assurant un mentorat efficace pour les plus jeunes. Une
équipe de développement équilibrée tire parti des forces de chaque membre, junior ou senior, pour créer des solutions
robustes et innovantes.

---
level: 2
---

# II - La valeur de l'expérience

L'expérience joue un rôle crucial dans le domaine du développement logiciel, apportant des compétences et des
perspectives qui ne peuvent être acquises qu'au fil du temps et par la pratique. Voici pourquoi l'expérience est si
précieuse

A - Résolution de problèmes complexes

`Diagnostic rapide`

<div v-click>

```html

<div v-click>Les développeurs expérimentés sont habiles à identifier rapidement les problèmes, ayant rencontré et
    surmonté maintes fois des obstacles similaires par le passé.
</div>
```

</div>

<br>

`Techniques éprouvées`

<div v-click>

```html

<div v-click>Leur arsenal de techniques éprouvées inclut une gamme variée d'approches pour résoudre des problèmes
    complexes, acquises grâce à leur expérience diversifiée.
</div>
```

</div>

---

A - Résolution de problèmes complexes

`Anticipation des problèmes`

<div v-click>

```html

<div v-click>L'expérience leur permet d'anticiper et de prévenir les problèmes potentiels, offrant ainsi une
    perspective proactive sur la résolution des défis.
```

</div>

---

II - La valeur de l'expérience

# B - Prise de décisions éclairées

`Connaissance approfondie`

<div v-click>

```html

<div v-click>L'expérience offre une connaissance approfondie des technologies et des meilleures pratiques, favorisant
    des décisions fondées sur une compréhension solide.
</div>
```

</div>

<br>

`Évaluation des compromis`

<div v-click>

```html

<div v-click> Les développeurs expérimentés sont capables d'évaluer les compromis entre différentes solutions,
    choisissant celle qui convient le mieux au contexte donné.
</div>
```

</div>

---

B - Prise de décisions éclairées

`Gestion des risques`

<div v-click>

```html

<div v-click>Leur expérience les prépare à gérer les risques, leur permettant d'anticiper et de minimiser les impacts
    négatifs grâce à des plans de contingence bien élaborés.
</div>
```

</div>

---

II - La valeur de l'expérience

# C - Conception de solutions robustes et évolutives

`Architecture solide`

<div v-click>

```html

<div v-click>Les développeurs expérimentés conçoivent des architectures logicielles robustes, basées sur des principes
    de modularité, de séparation des préoccupations et de scalabilité.
</div>
```

</div>

<br>

`Maintenance facilitée`

<div v-click>

```html

<div v-click>Leur conception initiale privilégie la facilité de maintenance et d'évolution, réduisant ainsi les coûts et
    les efforts liés aux mises à jour futures.
</div>
```

</div>

---

C - Conception de solutions robustes et évolutives

`Documentation et standards`

<div v-click>

```html

<div v-click>Ils accordent une grande importance à la documentation et aux standards de codage, favorisant la
    collaboration et assurant la pérennité et la qualité du code.
</div>
```

</div>

Conclusion<br>
L'expérience est une ressource inestimable dans le développement logiciel. Elle permet de résoudre des problèmes
complexes, de prendre des décisions éclairées et de concevoir des solutions robustes. Les développeurs expérimentés
ajoutent une valeur significative en apportant stabilité, efficacité et vision à long terme. Leur rôle est crucial pour
la réalisation de projets immédiats et la formation des développeurs moins expérimentés, contribuant ainsi à
l'amélioration continue des pratiques de développement au sein de l'équipe.

---
transition: slide-up
level: 2
---

# 👩🏽‍💻 L'IA est-elle donc destinée aux développeurs moyens ?

Les utilisateurs exigent des applications web de plus en plus
rapides et réactives, ce qui pousse les développeurs à utiliser des frameworks qui optimisent les
performances. [learn more](https://2022.stateofjs.com/en-US/libraries/front-end-frameworks/)

<img src="github-copilot.png" alt="Awarness state of javascript 2022" style="max-width: 100%; height: auto;"/>

---
layout: image-right
image: ./chatgpt-intro.jpg
---

# I - Accessibilité de l'IA pour tous les niveaux

Comment les outils et plateformes d'IA deviennent de plus en plus
accessibles aux développeurs de tous niveaux, offrant des fonctionnalités de codage assisté, de génération de code et de
compréhension du langage naturel.
---

I - Accessibilité de l'IA pour tous les niveaux

L'essor des outils et plateformes d'intelligence artificielle (IA) a considérablement transformé le paysage du
développement logiciel, rendant ces technologies accessibles non seulement aux experts mais aussi aux développeurs de
tous niveaux. Voici comment l'IA devient un atout précieux pour les développeurs, quel que soit leur niveau
d'expérience :

# A - Outils de codage assisté

`Copilot`

<div v-click>

```html

<div v-click> GitHub Copilot, un outil de codage assisté par l'IA développé par OpenAI et GitHub, est un excellent
    exemple de cette tendance. Il aide les développeurs à écrire du code plus rapidement en suggérant des lignes ou des
    blocs entiers basés sur le contexte du code en cours. Cela réduit le temps passé à chercher des solutions et permet
    aux développeurs de se concentrer davantage sur la logique et la structure de leur code.
</div>
```

</div>

<br>

`IDE intelligents`

<div v-click>

```html

<div v-click>Les environnements de développement intégrés (IDE) comme Visual Studio Code, PyCharm et IntelliJ IDEA
    intègrent de plus en plus des fonctionnalités d'IA. Celles-ci incluent la complétion automatique intelligente, la
    détection d'erreurs en temps réel et des suggestions de refactoring, rendant le processus de codage plus fluide et
    efficace pour tous les niveaux de développeurs.
</div>
```

</div>

---

I - Accessibilité de l'IA pour tous les niveaux

# B - Génération de code

`Modèles de génération de code`

<div v-click>

```html

<div v-click>Les modèles d'IA, comme GPT-4, produisent du code à partir de descriptions en langage naturel, accélérant
    ainsi le processus de développement, surtout pour les développeurs moins expérimentés. qui peuvent
    avoir des difficultés avec certaines syntaxes ou concepts complexes.
</div>
```

</div>

<br>

`Automatisation des tâches répétitives`

<div v-click>

```html

<div v-click>L'IA peut automatiser les tâches de codage fastidieuses, telles que la génération de formulaires ou
    l'écriture de tests unitaires, libérant ainsi du temps pour des tâches plus créatives.
</div>
```

</div>

---

I - Accessibilité de l'IA pour tous les niveaux

# C - Compréhension du langage naturel

`Chatbots et assistants virtuels`

<div v-click>

```html

<div v-click>Des outils tels que ChatGPT fournissent des réponses détaillées et des solutions aux problèmes de codage,
    offrant une assistance en temps réel et réduisant le besoin de consulter des forums ou des documents traditionnels.
</div>
```

</div>

<br>

`Documentation interactive`

<div v-click>

```html

<div v-click>L'IA permet la création de documentation interactive, offrant aux développeurs des réponses contextuelles
    instantanées à leurs questions, améliorant ainsi l'apprentissage et la compréhension, notamment pour les débutants.
</div>
```

</div>

---

I - Accessibilité de l'IA pour tous les niveaux

# D - Accessibilité à des plateformes d'apprentissage

`Cours et tutoriels augmentés par l'IA`

<div v-click>

```html

<div v-click>Les plateformes d'apprentissage en ligne intègrent l'IA pour personnaliser les parcours, proposer des
    exercices interactifs et fournir des feedbacks en temps réel, rendant l'apprentissage du développement plus
    accessible et adapté aux besoins individuels.
</div>
```

</div>

<br>

`Communautés de support`

<div v-click>

```html

<div v-click>L'IA alimente des communautés où les développeurs posent des questions et reçoivent des réponses rapides.
    Des forums comme Stack Overflow utilisent l'IA pour recommander les réponses les plus pertinentes, aidant ainsi les
    développeurs à résoudre leurs problèmes efficacement.
</div>
```

</div>
Conclusion<br>
L'IA révolutionne le développement logiciel en mettant à disposition des outils puissants pour tous les développeurs. Que ce soit à travers le codage assisté, la génération de code automatique ou la compréhension du langage naturel, elle permet une meilleure efficacité et favorise l'innovation en déchargeant des tâches répétitives. Cette accessibilité change la donne, facilitant l'apprentissage et améliorant la productivité de chacun.
---

layout: image-left
image: ./githubcopilot-chat.png
---

# II - Utilisation de l'IA dans le développement web

Présente des exemples concrets d'utilisation de l'IA dans le
développement web, tels que la génération de code avec Copilot, l'analyse sémantique avec ChatGPT, etc.

---

II - Utilisation de l'IA dans le développement web

L'intégration de l'intelligence artificielle (IA) dans le développement web a ouvert de nouvelles possibilités et
amélioré l'efficacité des développeurs. Voici quelques exemples concrets d'utilisation de l'IA dans ce domaine :

# A - Génération de code avec GitHub Copilot

`Assistance au codage`

<div v-click>

```html

<div v-click>GitHub Copilot, développé par GitHub et OpenAI, utilise l'IA pour suggérer des lignes de code et
    des blocs entiers en fonction du contexte dans lequel vous travaillez. En analysant les commentaires et le code
    existant, Copilot propose des complétions et des solutions, ce qui accélère considérablement le processus de
    développement.
</div>
```

</div>

<br>

`Prototypage rapide`

<div v-click>

```html

<div v-click>Avec Copilot, les développeurs peuvent créer des prototypes fonctionnels beaucoup plus rapidement.
    Par exemple, en décrivant simplement la fonctionnalité souhaitée en langage naturel, Copilot peut générer le code
    nécessaire, ce qui est particulièrement utile pour les projets où le temps est une contrainte.
</div>
```

</div>

---

II - Utilisation de l'IA dans le développement web

# B - Analyse sémantique avec ChatGPT

`Aide à la compréhension et à la correction`

<div v-click>

```html

<div v-click>ChatGPT, un modèle de langage développé par OpenAI, peut analyser des blocs
    de code et expliquer leur fonctionnement. Cela est extrêmement utile pour les développeurs qui rencontrent des
    problèmes
    complexes ou des bugs difficiles à résoudre. ChatGPT peut également suggérer des corrections et des améliorations au
    code.
</div>
```

</div>

<br>

`Rédaction de documentation`

<div v-click>

```html

<div v-click>ChatGPT peut aider à rédiger de la documentation technique en générant des descriptions
    claires et précises du code. Cela permet aux développeurs de maintenir une documentation à jour et accessible,
    facilitant ainsi la collaboration et la compréhension du code par d'autres membres de l'équipe.
</div>
```

</div>

---

II - Utilisation de l'IA dans le développement web

# C - Automatisation des tests

`Génération de tests unitaires`

<div v-click>

```html

<div v-click>L'IA peut générer des tests unitaires pour le code, ce qui permet d'identifier et de
    corriger les bugs plus tôt dans le cycle de développement. Des outils comme DeepCode utilisent l'IA pour analyser le
    code et proposer des tests qui couvrent un large éventail de scénarios.
</div>
```

</div>

<br>

`Test de performance et de charge`

<div v-click>

```html

<div v-click>Les outils d'IA peuvent également simuler des charges de trafic importantes et tester
    les performances des applications web. Cela permet aux développeurs de s'assurer que leurs applications peuvent
    gérer
    des volumes élevés de trafic sans se dégrader.
</div>
```

</div>

---

II - Utilisation de l'IA dans le développement web

# D - Personnalisation et recommandation

`Personnalisation de l'expérience utilisateur`

<div v-click>

```html

<div v-click>L'IA permet de personnaliser les expériences utilisateur en temps réel.
    Par exemple, des algorithmes de recommandation peuvent analyser le comportement des utilisateurs pour proposer des
    contenus ou des produits pertinents. Amazon et Netflix utilisent ces technologies pour offrir des expériences
    utilisateur hautement personnalisées.
</div>
```

</div>

<br>

`Chatbots et assistants virtuels`

<div v-click>

```html

<div v-click>Les chatbots alimentés par l'IA, comme ceux créés avec Dialogflow ou Microsoft Bot
    Framework, peuvent interagir avec les utilisateurs de manière naturelle et répondre à leurs questions. Ces bots sont
    utilisés pour le support client, les services de réservation et bien plus encore, offrant une assistance 24/7 sans
    intervention humaine.
</div>
```

</div>

---

II - L'Utilisation de l'IA dans le développement web

# E - Optimisation des workflows de développement

`Analyse prédictive`

<div v-click>

```html

<div v-click>Les outils d'IA peuvent analyser les flux de travail des développeurs et prédire les goulots d'
    étranglement potentiels. En utilisant ces prédictions, les équipes peuvent ajuster leurs processus pour améliorer
    l'efficacité et éviter les retards.
</div>
```

</div>

<br>

`Automatisation de la gestion des versions`

<div v-click>

```html

<div v-click>L'IA peut automatiser la gestion des versions du code, y compris le contrôle
    des versions et les déploiements continus. Cela réduit le risque d'erreurs humaines et assure une livraison plus
    fluide
    et rapide des mises à jour.
</div>
```

</div>

---

II - Utilisation de l'IA dans le développement web

Conclusion<br>

L'utilisation de l'IA dans le développement web révolutionne la manière dont les développeurs créent, testent et
déploient leurs applications. Des outils comme GitHub Copilot et ChatGPT démontrent comment l'IA peut augmenter la
productivité, améliorer la qualité du code et personnaliser l'expérience utilisateur. En automatisant des tâches
complexes et répétitives, l'IA permet aux développeurs de se concentrer sur des aspects plus créatifs et stratégiques de
leur travail, tout en rendant le développement web plus accessible et efficace pour tous les niveaux de compétence.
---

# Conclusion

En somme, la quête d'excellence en développement web intègre trois aspects essentiels :<br>
`Demande croissante de performance :`<br>
Les frameworks JavaScript comme React, Vue.js et Svelte répondent aux attentes des
utilisateurs en matière de rapidité et de réactivité, mais la performance doit être équilibrée avec d'autres
compétences.
<br>
`Innovation et compétition entre les frameworks : `<br>
La diversité des frameworks JavaScript offre de nombreuses options,
nécessitant une évaluation prudente pour choisir les outils adaptés à chaque projet et rester adaptable face aux
évolutions.
<br>
`Accessibilité de l'IA pour tous les niveaux : `<br>
Les outils comme GitHub Copilot et ChatGPT rendent le développement web
accessible à tous les niveaux en automatisant les tâches répétitives et en améliorant la compréhension du code, libérant
ainsi du temps pour l'aspect créatif et stratégique du développement.
<br>
En définitive, être un bon développeur implique la compréhension des principes fondamentaux, l'adaptation aux nouvelles
technologies et l'utilisation judicieuse des outils pour améliorer la productivité et la qualité du code. L'expérience
et l'innovation doivent être équilibrées pour répondre aux besoins variés et évolutifs du marché et des utilisateurs.


[//]: # (---)

[//]: # (class: px-20)

[//]: # (---)

[//]: # ()
[//]: # (# Themes)

[//]: # ()
[//]: # (Slidev comes with powerful theming support. Themes can provide styles, layouts, components, or even configurations for)

[//]: # (tools. Switching between themes by just **one edit** in your frontmatter:)

[//]: # ()
[//]: # (<div grid="~ cols-2 gap-2" m="t-2">)

[//]: # ()
[//]: # (```yaml)

[//]: # (---)

[//]: # (theme: default)

[//]: # (---)

[//]: # (```)

[//]: # ()
[//]: # (```yaml)

[//]: # (---)

[//]: # (theme: seriph)

[//]: # (---)

[//]: # (```)

[//]: # ()
[//]: # (<img border="rounded" src="https://github.com/slidevjs/themes/blob/main/screenshots/theme-default/01.png?raw=true" alt="">)

[//]: # ()
[//]: # (<img border="rounded" src="https://github.com/slidevjs/themes/blob/main/screenshots/theme-seriph/01.png?raw=true" alt="">)

[//]: # ()
[//]: # (</div>)

[//]: # ()
[//]: # (Read more about [How to use a theme]&#40;https://sli.dev/themes/use.html&#41; and)

[//]: # (check out the [Awesome Themes Gallery]&#40;https://sli.dev/themes/gallery.html&#41;.)

---
layout: center
class: text-center
---

# Merci pour votre écoute

[//]: # ([Documentations]&#40;https://sli.dev&#41; · [GitHub]&#40;https://github.com/slidevjs/slidev&#41; · [Showcases]&#40;https://sli.dev/showcases.html&#41;)
