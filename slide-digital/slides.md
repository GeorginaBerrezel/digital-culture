---
# Configuration de la Présentation
theme: apple-basic
background: https://cover.sli.dev
title: "Être un bon développeur front-end : Faut-il suivre les dernières tendances ?"
info: |
  ## Présentation par Georgina Berrezel - M1 Dev
  Découvrez si suivre les dernières tendances est essentiel pour être un bon développeur front-end.
class: text-center
highlighter: shiki
drawings:
  persist: false
transition: slide-left
mdc: true

---

# Out Of School

<span style="
font-size: 2em;
font-weight: bold;
text-align: center;
display: block;
margin-top: 50px;
line-height: 1.3;
background-color: #51344D; /* violet */
color: #fff; /* Couleur du texte */
padding: 10px; /* Espace autour du texte */
border-radius: 5px; /* Coins arrondis */
box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.1); /* Ombre portée plus douce */
" v-click="1">
Être un bon développeur front-end :<br> Faut-il suivre les dernières tendances ?
</span>

<div style="display: flex; flex-direction: column; align-items: center;" v-click="2">
  <img src="https://img.icons8.com/ios/50/goal.png" alt="Objectif" style="width:24px; height:24px; margin-top: 8px;"/>
  <span style="background-color: rgba(81, 52, 77, 0.2); font-weight: 900; font-size: 1.2em;">Objectif</span>
  <span style="font-size: 1.2em; text-align: center;">Découvrir si être à la pointe des technologies est essentiel.</span>  
</div>

<br>

<div style="display: flex; flex-direction: column; align-items: center;" v-click="3">
  <img src="https://img.icons8.com/ios/50/question.png" alt="Question centrale" style="width:24px; height:24px; margin-top: 8px;"/>
  <span style="background-color: rgba(81, 52, 77, 0.2); font-weight: bold; font-size: 1.2em;">Question centrale</span>  
  <span style="font-size: 1.2em; text-align: center;">Innover ou maîtriser les fondamentaux ?</span>  
</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span><strong>Introduction:</strong> Être un bon développeur front-end</span> | <span>Page 1</span>
</div>

---

# Sommaire

<div style="text-align: center;" v-click:1>
  <span style="color: #000; font-weight: bold; font-size: 1.5em; text-align: center; display: block; margin-top: 10px;">De quoi allons-nous parler ?</span>
</div>

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; align-items: center; margin-top: 10px;">
  <div style="text-align: center; color: #51344D;" v-click="2">
    <img src="https://img.icons8.com/ios/50/visible.png" alt="Contexte" style="width:20px; height:20px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em;">Définition Développement Front-End</span>
  </div>

  <div style="text-align: center; color: #51344D;" v-click="2">
    <img src="https://img.icons8.com/ios/50/code.png" alt="Frameworks" style="width:20px; height:20px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em;">Définition Frameworks JS</span>
  </div>
</div>

  <div style="margin-top:10px; text-align: center; color: #4ECDC4;" v-click="3">
<img src="https://img.icons8.com/ios/50/teamwork.png" alt="Dualité Junior vs Senior" style="width:20px; height:20px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em;">I . Être un bon développeur c'est quoi ?</span>
  </div>

<div style="align-items: center; margin-top: 20px;">
<div style="text-align: center; color: #FF6B6B;" v-click="4">
<img src="https://img.icons8.com/ios/50/line-chart.png" alt="Line Chart" style="width:20px; height:20px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em;"> II . Performance et Évolution des Frameworks JS</span>
</div>

  <div style="margin-top:20px; text-align: center; color: #1A535C;" v-click="5">
    <img src="https://img.icons8.com/ios/50/innovation.png" alt="Innovation" style="width:20px; height:20px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em;">III . Innovation et Compétition entre Frameworks</span>
  </div>



  <div style="margin-top:20px; text-align: center; color: #FBAF00;" v-click="6">
    <img src="https://img.icons8.com/ios/50/artificial-intelligence.png" alt="IA" style="width:20px; height:20px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em;">IV . L'IA : Un Atout pour Tous les Développeurs ?</span>
  </div>


  <div style="text-align: center; color: #51344D;" v-click="7">
<img src="https://img.icons8.com/ios/50/checkmark.png" alt="Conclusion" style="width:20px; height:20px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em;">Conclusion</span>
  </div>
</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
<span><i>Je veux être un bon développeur ! Dois-je être à la pointe des nouveaux frameworks JS et des tendances web ?</i></span>
<br>   
<span><strong>Sommaire</strong></span> | <span>Page 2</span>
</div>

---

# Définition

<div style="text-align: center;" v-click="1">
  <span style="color: #51344D; font-size: 1.5em; font-weight: bold; padding: 10px; border-radius: 5px;">Qu'est-ce qu'un développeur Front-End ?</span>
</div>

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 20px; text-align: center; margin-top: 30px;">

  <div style="line-height: 1.4;" v-click="2">
    <img src="https://img.icons8.com/ios/50/source-code.png" alt="Codage" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.5em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Codage</strong></span>
    <p style="font-size: 1.1em; margin-top: 10px; margin-bottom: 0;">Implémentation du code.</p>
  </div>

<div style="line-height: 1.4;" v-click="3">
    <img src="https://img.icons8.com/ios/50/refresh.png" alt="Évolution constante" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.4em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Évolution constante</strong></span>
    <p style="font-size: 1em; margin-top: 10px; margin-bottom: 0;">Nouvelles technologies et frameworks.</p>
  </div>

  <div style="line-height: 1.4;" v-click="4">
    <img src="https://img.icons8.com/ios/50/paint-bucket.png" alt="Conception" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.5em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Conception</strong></span>
    <p style="font-size: 1.1em; margin-top: 10px; margin-bottom: 0;">Design et UX/UI.</p>
  </div>

  <div style="line-height: 1.4;" v-click="5">
    <img src="https://img.icons8.com/ios/50/maintenance.png" alt="Maintenance" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.5em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Maintenance</strong></span>
    <p style="font-size: 1.1em; margin-top: 10px; margin-bottom: 0;">Soutien des interfaces utilisateurs.</p>
  </div>

  <div style="line-height: 1.4;" v-click="6">
    <img src="https://img.icons8.com/ios/50/target.png" alt="Objectif" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.5em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Objectif</strong></span>
    <p style="font-size: 1.1em; margin-top: 10px; margin-bottom: 0;">Efficacité et adaptabilité.</p>
  </div>
</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
<span><i>Je veux être un bon développeur ! Dois-je être à la pointe des nouveaux frameworks JS et des tendances web ?</i></span>
<br>   
<span>Définition developpeur web</span> | 
  <span><strong>Page :</strong> 3</span>
</div>

---

# Définition

<div style="text-align: center;" v-click="1">
  <span style="color: #51344D; font-size: 1.5em;">Qu'est-ce qu'un Framework JS ?</span>
</div>

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px; text-align: center; margin-top: 20px;">

  <div v-click="2">
    <img src="https://img.icons8.com/ios/50/toolbox.png" alt="Outils puissants" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.1em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Outils Intégrés</strong></span>
    <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Bibliothèques et outils prêts à l'emploi.</p>
  </div>

  <div v-click="3">
    <img src="https://img.icons8.com/ios/50/speed.png" alt="Code plus rapide" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.1em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Code plus rapide</strong></span>
    <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Optimisation du processus de développement.</p>
  </div>

  <div v-click="4">
    <img src="https://img.icons8.com/ios/50/maintenance.png" alt="Maintenable" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.1em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Maintenance facile</strong></span>
    <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Code structuré et évolutif.</p>
  </div>

  <div v-click="5">
    <img src="https://img.icons8.com/?size=100&id=fU5cXapwJUEs&format=png&color=000000" alt="Component" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.1em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Composants</strong></span>
    <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Composant réutilisable qui encapsule la logique et l'UI.</p>
  </div>
</div>

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; text-align: center; margin-top: 20px;">

  <div v-click="6">
    <img src="https://img.icons8.com/?size=100&id=bzf0DqjXFHIW&format=png&color=000000" alt="React" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1.1em; color: #51344D;"><strong>React</strong></span>
    <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Framework JS populaire.</p>
  </div>

  <div v-click="6">
    <img src="https://img.icons8.com/?size=100&id=tbleCw0ch6QC&format=png&color=000000" alt="Vue.js" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1.1em; color: #51344D;"><strong>Vue.js</strong></span>
    <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Framework léger et performant.</p>
  </div>

  <div v-click="6">
    <img src="https://img.icons8.com/?size=100&id=71257&format=png&color=000000" alt="Angular" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1.1em; color: #51344D;"><strong>Angular</strong></span>
    <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Framework robuste et complet.</p>
  </div>

</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span><i>Je veux être un bon développeur ! Dois-je être à la pointe des nouveaux frameworks JS et des tendances web ?</i></span>
  <br>   
  <span>Définition framework JS</span> | 
  <span><strong>Page :</strong> 4</span>
</div>

---

# I - Être un bon développeur c'est quoi ?

<div style="text-align: center;" v-click="1">
  <span style="background-color: #4ECDC4; font-weight: bold; padding: 8px; border-radius: 5px; color: #FFF; font-size: 1.5em; line-height: 1.2;">Compétences et attitudes</span>
</div>
  <div style="flex: 1; margin: 30px; text-align: center;" v-click="1">
    <img src="https://img.icons8.com/?size=100&id=20906&format=png&color=000000" alt="git" style="width:60px; height:60px; display: block; margin: 0 auto;"/>
  </div>
<div style="display: flex; flex-wrap: wrap; justify-content: space-between; margin-top: 20px;">
  <!-- Communication et Collaboration -->
  <div style="flex: 1; margin: 10px; text-align: center;" v-click="2">
    <img src="https://img.icons8.com/?size=100&id=122809&format=png&color=000000" alt="Communication" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em; font-weight: bold; color:#4ECDC4;">Communication</span>
    <p style="font-size: 1em; margin-top: 10px;">Collaborer</p>
    <p style="font-size: 0.8em; line-height: 1; color: #999;">Junior et Senior échangent pour apprendre et progresser.</p>
  </div>

  <!-- Recherche et Apprentissage -->
  <div style="flex: 1; margin: 10px; text-align: center;" v-click="3">
    <img src="https://img.icons8.com/?size=100&id=aOTXjQvUhALw&format=png&color=000000" alt="Recherche" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em; font-weight: bold; color:#4ECDC4;">Recherche</span>
    <p style="font-size: 1em; margin-top: 10px;">Se Former</p>
    <p style="font-size: 0.8em; line-height: 1; color: #999;">Se tenir au courant des nouvelles technologies pour répondre aux besoins.</p>
  </div>

  <!-- Résolution de Problèmes -->
  <div style="flex: 1; margin: 10px; text-align: center;" v-click="4">
    <img src="https://img.icons8.com/?size=100&id=6d6M8Jjdz7k9&format=png&color=000000" alt="Résolution de Problèmes" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em; font-weight: bold; color:#4ECDC4;">Résolution de Problèmes</span>
    <p style="font-size: 1em; margin-top: 10px;">Innover et s'adapter</p>
    <p style="font-size: 0.8em; line-height: 1; color: #999;">Trouver des solutions efficaces aux défis techniques.</p>
  </div>
</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span><i>Un bon développeur reste curieux, apprend constamment et collabore efficacement.</i></span>
  <br>
  <span>I - Être un bon développeur</span> | 
  <span><strong>Titre :</strong> Compétences et Attitudes</span> | 
  <span><strong>Page :</strong> 9</span>
</div>

---

# II - Performance et Évolution des Frameworks JS

<div style="text-align: center;" v-click="1">
  <span style="background-color: #FF6B6B; font-weight: bold; padding: 8px; border-radius: 5px; color: #FFF; font-size: 1.5em;">Cas d'étude</span>
</div>

<div style="margin-top: 20px; text-align: center;">
  <!-- Section Demande Croissante de Performance -->
  <div style="margin-bottom: 20px;" v-click="2">
    <div style="display: flex; justify-content: space-around; margin-top: 10px;">
      <div style="text-align: center;" v-click="3">
        <img src="https://img.icons8.com/?size=100&id=103424&format=png&color=000000" alt="Airbnb" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em;">Airbnb</span>
      </div>
    </div>
  </div>

  <!-- Section Exemples -->
  <div style="display: flex; justify-content: space-around; margin-top: 20px;">
    <div style="text-align: center; margin: 10px;" v-click="4">
      <img src="https://img.icons8.com/?size=100&id=123603&format=png&color=000000" alt="React" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
      <span style="color: #FF6B6B; font-weight: bold; font-size: 1em;">React</span>
      <p style="font-size: 0.9em; line-height: 0.2;">Migration en 2014</p>
      <p style="font-size: 0.8em; line-height: 1; color: #999;">Passage de Backbone.js à React pour sa gestion simplifiée des composants. Révolution dans la manière de créer des interfaces.</p>
    </div>
    <div style="text-align: center; margin: 10px;" v-click="5">
      <img src="https://img.icons8.com/?size=100&id=9267&format=png&color=000000" alt="SSR et Lazy Loading" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
      <span style="color: #FF6B6B; font-weight: bold; font-size: 1em;">Performance</span>
      <p style="font-size: 0.9em; line-height: 0.2;">SSR & Lazy Loading</p>
      <p style="font-size: 0.8em; line-height: 1; color: #999;">Techniques pour améliorer les performances : rendu côté serveur (SSR) et chargement différé (Lazy Loading).</p>
    </div>
    <div style="text-align: center; margin: 10px;" v-click="6">
      <img src="https://img.icons8.com/?size=100&id=9492&format=png&color=000000" alt="Écosystème" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
      <span style="color: #FF6B6B; font-weight: bold; font-size: 1em;">Écosystème</span>
      <p style="font-size: 0.9em; line-height: 0.2;">Outils et Bibliothèques</p>
      <p style="font-size: 0.8em; line-height: 1; color: #999;">Richesse des outils pour le routage (React Router), gestion d'état (Redux, Context API), et plus encore.</p>
    </div>
  </div>
</div>

<!-- Bas de page -->
<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span><i>Je veux être un bon développeur ! Dois-je être à la pointe des nouveaux frameworks JS et des tendances web ?</i></span>
  <br>
  <span>I - Performance et Évolution des Frameworks JS</span> | 
  <span>a - Cas d'étude Airbnb</span> | 
  <span><strong>Page :</strong> 5</span>
</div>

---

# II - Performance et Évolution des Frameworks JS

<div style="text-align: center;" v-click="1">
  <span style="background-color: #FF6B6B; font-weight: bold; padding: 8px; border-radius: 5px; color: #FFF; font-size: 1.5em; line-height: 1.2;">Frameworks JS</span>
</div>

<div style="margin-top: 20px; text-align: center;">
  <!-- Section Pour -->
  <div style="margin-bottom: 20px;" v-click="2">
    <div style="display: flex; justify-content: space-around; flex-wrap: wrap; margin-top: 10px;">
      <div style="text-align: center; margin: 10px;" v-click="3">
        <img src="https://img.icons8.com/?size=100&id=123603&format=png&color=000000" alt="React" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em; line-height: 1.2;">React</span>
        <p style="font-size: 0.9em; line-height: 0.2;">Composants modulaires et structure flexible</p>
        <p style="font-size: 0.8em; line-height: 0.2; color: #999;">Créé en 2013 par Facebook</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click="4">
        <img src="https://img.icons8.com/?size=100&id=l9a5tcSnBwcf&format=png&color=000000" alt="Angular" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em; line-height: 1.2;">Angular</span>
        <p style="font-size: 0.9em; line-height: 0.2;">Écosystème robuste et outillage complet</p>
        <p style="font-size: 0.8em; line-height: 0.2; color: #999;">AngularJS créé en 2010 par Google</p>
        <p style="font-size: 0.8em; line-height: 0.2; color: #999;">Angular (nouvelle version) en 2016</p>
</div>
      <div style="text-align: center; margin: 10px;" v-click="5">
        <img src="https://img.icons8.com/?size=100&id=BUnExfsRs3CW&format=png&color=000000" alt="Vue.js" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em; line-height: 1.2;">Vue.js</span>
        <p style="font-size: 0.9em; line-height: 0.2;">Léger et facile à apprendre</p>
        <p style="font-size: 0.8em; line-height: 0.2; color: #999;">Créé en 2014 par Evan You</p>
      </div>
    </div>
  </div>
  <div style="margin-bottom: 20px;" v-click="2">
    <div style="display: flex; justify-content: space-around; flex-wrap: wrap; margin-top: 10px;">
      <div style="text-align: center; margin: 10px;" v-click="6">
        <img src="https://img.icons8.com/?size=100&id=Mm35TzLKahiF&format=png&color=000000" alt="Svelte" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em; line-height: 1.2;">Svelte</span>
        <p style="font-size: 0.9em; line-height: 0.2;">Performances, Simplicité</p>
        <p style="font-size: 0.8em; line-height: 0.2; color: #999;">Créé en 2016 par Rich Harris</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click="7">
        <img src="https://img.icons8.com/?size=100&id=RrpsObb9IBGY&format=png&color=000000" alt="Ember.js" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em; line-height: 1.2;">Ember.js</span>
        <p style="font-size: 0.9em; line-height: 0.2;">Convention, Productivité</p>
        <p style="font-size: 0.8em; line-height: 0.2; color: #999;">Créé en 2011 par Yehuda Katz</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click="8">
        <img src="https://img.icons8.com/?size=100&id=2778&format=png&color=000000" alt="Alpine.js" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em; line-height: 1.2;">Alpine.js</span>
        <p style="font-size: 0.9em; line-height: 0.2;">Léger, Minimaliste</p>
        <p style="font-size: 0.8em; line-height: 0.2; color: #999;">Créé en 2019 par Caleb Porzio</p>
      </div>
    </div>
  </div>
</div>

<!-- Bas de page -->
<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span><i>Je veux être un bon développeur ! Dois-je être à la pointe des nouveaux frameworks JS et des tendances web ?</i></span>
  <br>
  <span>I - Performance et Évolution des Frameworks JS</span> | 
  <span><strong>Titre :</strong>b - Critères de Choix d'un Framework JS</span> | 
  <span><strong>Page :</strong> 6</span>
</div>


---

# III - Innovation et Compétition entre Frameworks

<div style="margin-top: 20px; text-align: right;">
    <span style="font-size: 0.6em; font-weight: bold; color: #1A535C;"><i>source : https://2023.stateofjs.com/en-US/libraries/front-end-frameworks/</i></span>
  <img src="assets/state-of-js-all-frameworks.png" alt="Description de l'image" style="width:100%; height:auto;"/>
</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span><i>Je veux être un bon développeur ! Dois-je être à la pointe des nouveaux frameworks JS et des tendances web ?</i></span>
  <br>
  <span>II - Innovation et Compétition entre Frameworks</span> | 
  <span><strong>Titre :</strong> a - Diversité des Options Disponibles</span> | 
  <span><strong>Page :</strong> 7</span>
</div>

---

# III - Innovation et Compétition entre Frameworks

<div style="display: flex; flex-wrap: wrap; justify-content: space-between; margin-top: 20px;">
  <!-- Angular -->
  <div style="flex: 1; margin: 10px; text-align: center;" v-click="1">
    <img src="https://img.icons8.com/?size=100&id=71257&format=png&color=000000" alt="Angular" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em; font-weight: bold; color: #1A535C;">Angular</span>
  </div>
</div>

<div style="display: flex; justify-content: space-between; margin-top: 20px;">
  <!-- Ligne des points clés -->
  <div style="flex: 1; text-align: center; margin: 10px;" v-click="2">
    <span style="font-size: 1em; font-weight: bold;">Angular 2+</span>
    <p style="font-size: 0.8em; line-height: 1; color: #999;"><b>Mise à jour Mai 2014</b><br>Modularité, TypeScript, Performance</p>
  </div>
  <div style="flex: 1; text-align: center; margin: 10px;" v-click="3"> 
    <span style="font-size: 1em; font-weight: bold;">Angular v18</span>
    <p style="font-size: 0.8em; line-height: 1; color: #999;"><b>Mise à jour mai 2024</b><br>Optimisation, Modernisation, Sécurité</p>
  </div>
  <div style="flex: 1; text-align: center; margin: 10px;" v-click="4">
    <span style="font-size: 1em; font-weight: bold;">Objectif</span>
    <p style="font-size: 0.8em; line-height: 1; color: #999;">Répondre aux besoins modernes</p>
  </div>
  <div style="flex: 1; text-align: center; margin: 10px;" v-click="5">
    <span style="font-size: 1em; font-weight: bold;">Concurrence</span>
    <p style="font-size: 0.8em; line-height: 1; color: #999;">Réagir à React et Vue.js</p>
  </div>
  <div style="flex: 1; text-align: center; margin: 10px;" v-click="6">
    <span style="font-size: 1em; font-weight: bold;">Avantages</span>
    <p style="font-size: 0.8em; line-height: 1; color: #999;">Performance, Sécurité, Flexibilité</p>
  </div>
</div>

<div style="margin-top: 20px; text-align: right;" v-click="6">
  <img src="assets/state-of-js-awarness-frameworks.png" alt="Description de l'image" style="width:100%; height:auto;"/>
    <span style="font-size: 0.6em; font-weight: bold; color: #1A535C;"><i>source : https://2023.stateofjs.com/en-US/libraries/front-end-frameworks/</i></span>
</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span><i>Je veux être un bon développeur ! Dois-je être à la pointe des nouveaux frameworks JS et des tendances web ?</i></span>
  <br>
  <span>II - Innovation et Compétition entre Frameworks</span> | 
  <span><strong>Titre :</strong> b - Évolution Continue et Compétition</span> | 
  <span><strong>Page :</strong> 8</span>
</div>

---

# IV. L'IA : Un Atout pour Tous les Développeurs ?

<div style="text-align: center;" v-click:1>
  <span style="background-color: #FBAF00; font-weight: bold; padding: 8px; border-radius: 5px; color: #FFF; font-size: 1.5em; line-height: 1.2;">Accessibilité de l'IA pour Tous les Niveaux</span>
</div>

<div style="margin-top: 20px; text-align: center;" v-click:2>
  <!-- Section IA centrée -->
  <div style="margin-bottom: 20px;">
    <p style="font-size: 1em; margin-top: 10px;">L'IA aide dans le quotidien</p>
  </div>
</div>

<div style="display: block; margin-top: 20px;">
  <!-- Section Avantages -->
  <div style="margin: 10px; text-align: center;" v-click:3>
    <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; align-items: center; margin-top: 10px;">
      <div style="text-align: center; margin: 10px;">
        <img src="https://img.icons8.com/?size=100&id=Nts60kQIvGqe&format=png&color=000000" alt="chatgpt" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1.2em; font-weight: bold;">ChatGPT (2020)</span>
        <p style="font-size: 0.8em; line-height: 1; color: #999;">En ligne (interface web et API)</p>
      </div>
      <div style="text-align: center; margin: 10px;">
        <img src="https://img.icons8.com/?size=100&id=AZOZNnY73haj&format=png&color=000000" alt="github copilot" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1.2em; font-weight: bold;">GitHub Copilot (2021)</span>
        <p style="font-size: 0.8em; line-height: 1; color: #999;">Intégré à un IDE (Visual Studio Code, JetBrains)</p>
      </div>
    </div>
</div>
  <div style="margin: 10px; text-align: center;" v-click:3>
    <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; align-items: center; margin-top: 10px;">
      <div style="text-align: center; margin: 10px;">
        <span style="font-size: 1.2em; font-weight: bold;">Google Gemini (2023)</span>
        <p style="font-size: 0.8em; line-height: 1; color: #999;">En ligne (interface web)</p>
      </div>
      <div style="text-align: center; margin: 10px;">
        <span style="font-size: 1.2em; font-weight: bold;">Tabnine (2019)</span>
        <p style="font-size: 0.8em; line-height: 1; color: #999;">Intégré à un IDE (Visual Studio Code, PyCharm, etc.)</p>
      </div>
      <div style="text-align: center; margin: 10px;">
        <span style="font-size: 1.2em; font-weight: bold;">DeepCode (2016)</span>
        <p style="font-size: 0.8em; line-height: 1; color: #999;">Intégré à un IDE (Acquis par Snyk)</p>
      </div>
    </div>
  </div>
</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span><i>Je veux être un bon développeur ! Dois-je être à la pointe des nouveaux frameworks JS et des tendances web ?</i></span>
  <br>
  <span>IV. L'IA : Un Atout pour Tous les Développeurs ?</span> | 
  <span><strong>Titre :</strong> a - Accessibilité de l'IA pour Tous les Niveaux</span> | 
  <span><strong>Page :</strong> 10</span>
</div>

---

# IV. L'IA : Un Atout pour Tous les Développeurs ?

<div style="text-align: center;" v-click:1>
  <span style="background-color: #FBAF00; font-weight: bold; padding: 8px; border-radius: 5px; color: #FFF; font-size: 1.5em; line-height: 1.2;">Frameworks & Équipes</span>
</div>


<!-- Section Avantages en haut -->
<div style="display: flex; justify-content: space-between; margin-top: 20px; align-items: center;">
  <div style="flex: 1; text-align: center;">
    <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; align-items: center; margin-top: 10px;">
      <div style="margin: 10px;"v-click:1>
        <img src="https://img.icons8.com/?size=100&id=50898&format=png&color=000000" alt="Compréhension collective" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em;">Meilleure compréhension collective<br>des frameworks utilisés</span>
      </div>
      <div style="margin: 10px;" v-click:2>
        <img src="https://img.icons8.com/?size=100&id=24888&format=png&color=000000" alt="Support IA" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em;">Support IA pour les tâches répétitives<br>et gain de temps pour l'équipe</span>
      </div>
    </div>
  </div>
</div>

<!-- Section Défis en bas -->
<div style="display: flex; justify-content: space-between; margin-top: 20px; align-items: center;">
  <div style="flex: 1; text-align: center;">
    <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; align-items: center; margin-top: 10px;">
      <div style="margin: 10px;" v-click:3>
        <img src="https://img.icons8.com/?size=100&id=u1STh6KhRMdj&format=png&color=000000" alt="Qualité du code IA" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em;">Qualité du code généré par l'IA<br>Peut ne pas respecter les standards de l'équipe</span>
      </div>
      <div style="margin: 10px;" v-click:4>
        <img src="https://img.icons8.com/?size=100&id=VDdxpgm_aTTx&format=png&color=000000" alt="Vérification humaine" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em;">Importance de la vérification humaine<br>Pour assurer la cohérence et l'exactitude</span>
      </div>
    </div>
  </div>
</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span><i>Je veux être un bon développeur ! Dois-je être à la pointe des nouveaux frameworks JS et des tendances web ?</i></span>
  <br>
  <span>IV. L'IA : Un Atout pour Tous les Développeurs ?</span> | 
  <span><strong>Titre :</strong> b - Impact de l'IA sur les Frameworks et les Équipes</span> | 
  <span><strong>Page :</strong> 11</span>
</div>


---

# Conclusion

<div style="margin-top: 20px; text-align: center;" v-click:1>
  <!-- Section Synthèse centrée -->
  <div style="margin-bottom: 20px;">
    <p style="background-color: #51344D; font-weight: bold; padding: 8px; border-radius: 5px; color: #FFF; font-size: 1.5em; line-height: 1.2;">Je veux être un bon développeur ! Dois-je être à la pointe des nouveaux frameworks JS et des tendances web ?</p>
  </div>
</div>
<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px; align-items: center; margin-top: 10px;">
      <div style="text-align: center; margin: 10px;" v-click:3>
        <img src="https://img.icons8.com/?size=100&id=42283&format=png&color=000000" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">S'adapter aux besoins</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click:3>
        <img src="https://img.icons8.com/?size=100&id=43352&format=png&color=000000" alt="Innovation vs Fondamentaux" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Demande moderne</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click:3>
        <img src="https://img.icons8.com/?size=100&id=0Da6k7SMq0hs&format=png&color=000000" alt="Compétition" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Connaître les tendances</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click:4>
        <img src="https://img.icons8.com/?size=100&id=43331&format=png&color=000000" alt="Réflexion stratégique" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Réflexion stratégique</p>
      </div>
</div>

<div style="display: flex; justify-content: space-between; margin-top: 10px;">
  <!-- Section Réponse à la Question Centrale -->
  <div style="flex: 1; margin: 10px; text-align: center;">
    <div style="margin-top: 10px;">
      <div style="text-align: center; margin: 10px;" v-click:6>
        <img src="https://img.icons8.com/?size=100&id=Cc5U1vG2huUW&format=png&color=000000" alt="Bon Développeur" style="width:60px; height:60px; display: block; margin: 0 auto;"/>
        <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.1em; font-weight: bold; padding: 8px; border-radius: 5px;">Oui, mais...</span>
        <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Être informé des tendances, <br>mais surtout savoir s'adapter et réfléchir</p>
      </div>
    </div>
  </div>
</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span>Conclusion</span> | 
  <span><strong>Titre :</strong> Synthèse et Réponse à la Question Centrale</span> | 
  <span><strong>Page :</strong> 12</span>
</div>

---

# Remerciements

<div style="display: flex; justify-content: center; align-items: center; height: 60vh; text-align: center; flex-direction: column;">
  <div>
    <span style="font-size: 2em; color: #51344D;">Merci pour votre écoute</span>
    <p style="font-size: 1.5em; margin-top: 20px;">Out Of School</p>
        <img src="https://img.icons8.com/?size=100&id=Cc5U1vG2huUW&format=png&color=000000" alt="Bon Développeur" style="width:100px; height:100px; display: block; margin: 0 auto;"/>
  </div>
</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span><strong>Partie du Sommaire :</strong> Remerciements</span> | 
  <span><strong>Elève :</strong> Georgina Berrezel</span> | 
  <span><strong>Classe :</strong> Mastère 1 Developpement Web</span> |
  <span><strong>Page :</strong> 13</span></div>
