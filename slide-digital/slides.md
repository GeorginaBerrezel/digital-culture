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
<div style="align-items: center; margin-top: 10px;">
<div style="text-align: center; color: #FF6B6B;" v-click="3">
<img src="https://img.icons8.com/ios/50/line-chart.png" alt="Line Chart" style="width:20px; height:20px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em;"> I . Performance et Évolution des Frameworks JS</span>
</div>
  <div style="margin-top:20px; text-align: center; color: #1A535C;" v-click="4">
    <img src="https://img.icons8.com/ios/50/innovation.png" alt="Innovation" style="width:20px; height:20px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em;">II . Innovation et Compétition entre Frameworks</span>
  </div>

  <div style="margin-top:20px; text-align: center; color: #4ECDC4;" v-click="5">
<img src="https://img.icons8.com/ios/50/teamwork.png" alt="Dualité Junior vs Senior" style="width:20px; height:20px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em;">III . La Dualité Junior vs Senior</span>
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
    <img src="https://img.icons8.com/ios/50/refresh.png" alt="Évolution constante" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.4em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Évolution constante</strong></span>
    <p style="font-size: 1em; margin-top: 10px; margin-bottom: 0;">Nouvelles technologies et frameworks.</p>
  </div>

  <div style="line-height: 1.4;" v-click="3">
    <img src="https://img.icons8.com/ios/50/paint-bucket.png" alt="Conception" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.5em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Conception</strong></span>
    <p style="font-size: 1.1em; margin-top: 10px; margin-bottom: 0;">Design et UX/UI.</p>
  </div>

  <div style="line-height: 1.4;" v-click="4">
    <img src="https://img.icons8.com/ios/50/source-code.png" alt="Codage" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.5em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Codage</strong></span>
    <p style="font-size: 1.1em; margin-top: 10px; margin-bottom: 0;">Implémentation du code.</p>
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
  <span style="color: #51344D; font-size: 1.5em;">Importance des Frameworks JS</span>
</div>

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px; text-align: center; margin-top: 20px;">

  <div v-click="2">
    <img src="https://img.icons8.com/ios/50/toolbox.png" alt="Outils puissants" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.1em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Outils puissants</strong></span>
    <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Simplifient le développement.</p>
  </div>

  <div v-click="3">
    <img src="https://img.icons8.com/ios/50/speed.png" alt="Code plus rapide" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.1em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Code plus rapide</strong></span>
    <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Optimisation du processus de développement.</p>
  </div>

  <div v-click="4">
    <img src="https://img.icons8.com/ios/50/maintenance.png" alt="Maintenable" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.1em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Maintenable</strong></span>
    <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Facilité de maintenance.</p>
  </div>

  <div v-click="5">
    <img src="https://img.icons8.com/ios/50/reuse.png" alt="Réutilisable" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.1em; font-weight: bold; padding: 8px; border-radius: 5px;"><strong>Réutilisable</strong></span>
    <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Composants réutilisables.</p>
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
    <span style="font-size: 1.1em; color: #51344D;"><strong>Vue.js :</strong></span>
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

# I - Performance et Évolution des Frameworks JS

<div style="text-align: center;" v-click="1">
  <span style="background-color: #FF6B6B; font-weight: bold; padding: 8px; border-radius: 5px; color: #FFF; font-size: 1.5em;">Cas d'étude</span>
</div>

<div style="margin-top: 20px; text-align: center;">
  <!-- Section Demande Croissante de Performance -->
  <div style="margin-bottom: 20px;" v-click="2">
    <div style="display: flex; justify-content: space-around; margin-top: 10px;">
    <div style="text-align: center;" v-click="3">
      <img src="https://img.icons8.com/?size=100&id=103424&format=png&color=000000" alt="Airbnb (Gestion d'état)" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
      <span style="font-size: 1em;">Airbnb</span>
    </div>
    </div>
  </div>

  <!-- Section Exemples -->
  <div style="display: flex; justify-content: space-around; margin-top: 20px;">
   <div style="text-align: center; margin: 10px;" v-click="4">
        <img src="https://img.icons8.com/?size=100&id=123603&format=png&color=000000" alt="Maîtrise des technologies" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="color: #FF6B6B; font-weight: bold; font-size: 1em;">React</span>
        <p style="font-size: 0.9em; line-height: 0.2;">migration en 2014</p>
        <p style="font-size: 0.8em; line-height: 1; color: #999;">Trop gestion manuelle des vues et états.<br>Passe de Backnone.js à React pour sa gestion simplifiée des composants. </p>
    </div>
    <div style="text-align: center; margin: 10px;" v-click="5">
        <img src="https://img.icons8.com/ios/50/server.png" alt="SSR" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="color: #FF6B6B; font-weight: bold; font-size: 1em;">SSR</span>
        <p style="font-size: 0.9em; line-height: 0.2;">Server-Side Rendering</p>
        <p style="font-size: 0.8em; line-height: 1; color: #999;">Technique permettant de rendre les pages côté serveur avant de les envoyer au client, améliorant les performances.</p>
    </div>
    <div style="text-align: center; margin: 10px;" v-click="6">
        <img src="https://img.icons8.com/?size=100&id=9991&format=png&color=000000" alt="Lazy loading" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="color: #FF6B6B; font-weight: bold; font-size: 1em;">Lazy Loading</span>
        <p style="font-size: 0.9em; line-height: 0.2;">Chargement différé des composants</p>
        <p style="font-size: 0.8em; line-height: 1; color: #999;">Technique optimisant le temps de chargement en ne chargeant les ressources qu'au moment de leur besoin.</p>
      </div>
  </div>
</div>

<!-- Bas de page -->
<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
    <span><i>Je veux être un bon développeur ! Dois-je être à la pointe des nouveaux frameworks JS et des tendances web ?</i></span>
<br>
  <span>I - Performance et Évolution des Frameworks JS</span> | 
  <span>a - Demande Croissante de Performance</span> | 
  <span><strong>Page :</strong> 5</span>
</div>

---

# I - Performance et Évolution des Frameworks JS

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
      </div>
      <div style="text-align: center; margin: 10px;" v-click="4">
        <img src="https://img.icons8.com/?size=100&id=l9a5tcSnBwcf&format=png&color=000000" alt="Angular" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em; line-height: 1.2;">Angular</span>
        <p style="font-size: 0.9em; line-height: 0.2;">Écosystème robuste et outillage complet</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click="5">
        <img src="https://img.icons8.com/?size=100&id=BUnExfsRs3CW&format=png&color=000000" alt="Vue.js" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em; line-height: 1.2;">Vue.js</span>
        <p style="font-size: 0.9em; line-height: 0.2;">Léger et facile à apprendre</p>
      </div>
    </div>
  </div>
  <div style="margin-bottom: 20px;" v-click="2">
    <div style="display: flex; justify-content: space-around; flex-wrap: wrap; margin-top: 10px;">
      <div style="text-align: center; margin: 10px;" v-click="6">
        <img src="https://img.icons8.com/?size=100&id=Mm35TzLKahiF&format=png&color=000000" alt="Svelte" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em; line-height: 1.2;">Svelte</span>
        <p style="font-size: 0.9em; line-height: 0.2;">Performances, Simplicité</p>
        <p style="font-size: 0.8em; line-height: 0.2; color: #999;">Moins utilisé, communauté plus petite</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click="7">
        <img src="https://img.icons8.com/?size=100&id=RrpsObb9IBGY&format=png&color=000000" alt="Ember.js" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em; line-height: 1.2;">Ember.js</span>
        <p style="font-size: 0.9em; line-height: 0.2;">Convention, Productivité</p>
        <p style="font-size: 0.8em; line-height: 0.2; color: #999;">Moins populaire, adoption limitée</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click="8">
        <img src="https://img.icons8.com/?size=100&id=2778&format=png&color=000000" alt="Alpine.js" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em; line-height: 1.2;">Alpine.js</span>
        <p style="font-size: 0.9em; line-height: 0.2;">Léger, Minimaliste</p>
        <p style="font-size: 0.8em; line-height: 0.2; color: #999;">Adoption limitée, fonctionnalités réduites</p>
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

# II - Innovation et Compétition entre Frameworks

<div style="text-align: center;" v-click="1">
  <span style="background-color: #1A535C; font-weight: bold; padding: 8px; border-radius: 5px; color: #FFF; font-size: 1.5em; line-height: 1.2;">SCREEN</span>
</div>

<div style="margin-top: 20px; text-align: center;">
  <!-- Section Pour -->
  <div style="margin-bottom: 20px;" v-click="2">
    <span style="color: #1A535C; font-size: 1.2em; font-weight: bold; line-height: 1.2;">Positif</span>
    <div style="display: flex; justify-content: space-around; flex-wrap: wrap; margin-top: 10px;">
      <div style="text-align: center; margin: 10px;" v-click="3">
        <span style="font-size: 1em; line-height: 1.2;">Composants modulaires</span>
        <p style="font-size: 0.9em; line-height: 0.2;"><span style="background-color: rgba(26,83,92,0.4); padding: 4px; border-radius: 4px;">React</span>, structure flexible</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click="4">
        <span style="font-size: 1em; line-height: 1.2;">Écosystème robuste</span>
        <p style="font-size: 0.9em; line-height: 0.2;"><span style="background-color: rgba(26,83,92,0.4); padding: 4px; border-radius: 4px;">Angular</span>, outillage complet</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click="5">
        <span style="font-size: 1em; line-height: 1.2;">Performances</span>
        <p style="font-size: 0.9em; line-height: 0.2;"><span style="background-color: rgba(26,83,92,0.4); padding: 4px; border-radius: 4px;">Angular</span>, rendu optimisé</p>
      </div>
    </div>
  </div>

  <!-- Section Nuances -->
  <div style="margin-top: 20px;" v-click="6">
    <span style="color: #1A535C; font-size: 1.2em; font-weight: bold; line-height: 1.2;">Nuances</span>
    <div style="display: flex; justify-content: space-around; flex-wrap: wrap; margin-top: 10px;">
      <div style="text-align: center; margin: 10px;" v-click="7">
        <img src="https://img.icons8.com/?size=100&id=55349&format=png&color=000000" alt="Besoins spécifiques" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em; line-height: 1.2;">Besoins spécifiques</span>
        <p style="font-size: 0.9em; line-height: 0.2;">React ou Angular selon projet</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click="8">
        <img src="https://img.icons8.com/?size=100&id=TLl9GOp-fqJ3&format=png&color=000000" alt="Complexité d'implémentation" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em; line-height: 1.2;">Complexité d'implémentation</span>
        <p style="font-size: 0.9em; line-height: 0.2;">Angular, plus de configuration</p>
      </div>
    </div>
  </div>
</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span><i>Je veux être un bon développeur ! Dois-je être à la pointe des nouveaux frameworks JS et des tendances web ?</i></span>
  <br>
  <span>II - Innovation et Compétition entre Frameworks</span> | 
  <span><strong>Titre :</strong> a - Diversité des Options Disponibles</span> | 
  <span><strong>Page :</strong> 7</span>
</div>

---

# II - Innovation et Compétition entre Frameworks

<div style="text-align: center;" v-click="1">
  <span style="background-color: #1A535C; font-weight: bold; padding: 8px; border-radius: 5px; color: #FFF; font-size: 1.5em; line-height: 1.2;">Screen angular</span>
</div>

<div style="margin-top: 20px; text-align: center;" v-click="2">
  <!-- Section Avantages centrée -->
  <div style="margin-bottom: 20px;">
    <p style="font-size: 1em; margin-top: 10px;">Évolution pour rester compétitif</p>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; justify-content: space-between; margin-top: 20px;">
  <!-- Angular -->
  <div style="flex: 1; margin: 10px; text-align: center;" v-click="3">
    <img src="https://img.icons8.com/?size=100&id=71257&format=png&color=000000" alt="Angular" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1em; font-weight: bold; color: #1A535C;">Angular</span>
  </div>
</div>

<div style="display: flex; justify-content: space-between; margin-top: 20px;">
  <!-- Ligne des points clés -->
  <div style="flex: 1; text-align: center; margin: 10px;" v-click="4">
    <span style="font-size: 1em; font-weight: bold;">Mise à jour</span>
    <p style="font-size: 0.8em; line-height: 1; color: #999;">Évolution vers Angular 2+</p>
  </div>
  <div style="flex: 1; text-align: center; margin: 10px;" v-click="5"> 
    <span style="font-size: 1em; font-weight: bold;">Objectif</span>
    <p style="font-size: 0.8em; line-height: 1; color: #999;">Intégrer des fonctionnalités modernes</p>
  </div>
  <div style="flex: 1; text-align: center; margin: 10px; "v-click="6">
    <span style="font-size: 1em; font-weight: bold;">Concurrence</span>
    <p style="font-size: 0.8em; line-height: 1; color: #999;">Réaction à React et Vue.js</p>
  </div>
  <div style="flex: 1; text-align: center; margin: 10px;" v-click="7">
    <span style="font-size: 1em; font-weight: bold;">Avantages</span>
    <p style="font-size: 0.8em; line-height: 1; color: #999;">Architecture modulaire, performances améliorées</p>
  </div>
</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span><i>Je veux être un bon développeur ! Dois-je être à la pointe des nouveaux frameworks JS et des tendances web ?</i></span>
  <br>
  <span>II - Innovation et Compétition entre Frameworks</span> | 
  <span><strong>Titre :</strong> b - Évolution Continue et Compétition</span> | 
  <span><strong>Page :</strong> 8</span>
</div>


---

# III - Etre un bon développeur c'est quoi ? 

<div style="text-align: center;" v-click="1">
  <span style="background-color: #4ECDC4; font-weight: bold; padding: 8px; border-radius: 5px; color: #FFF; font-size: 1.5em; line-height: 1.2;">Qualités et Contextes des Développeurs</span>
</div>

<div style="margin-top: 20px; text-align: center;" v-click="2">
  <!-- Section Qualités et Passions centrée -->
  <div style="margin-bottom: 20px;">
    <p style="font-size: 1em; margin-top: 10px;">Développeurs : Passion et Épanouissement</p>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; justify-content: space-between; margin-top: 20px;">
  <!-- Section Développeurs Juniors -->
  <div style="flex: 1; margin: 10px; text-align: center;" v-click="3">
    <span style="font-size: 1.2em; font-weight: bold; color:#4ECDC4;">Junior</span>
    <div style="margin-top: 10px;">
      <div style="text-align: center; margin: 10px;">
        <span style="font-size: 1em;">Souvent métier passion</span>
        <p style="font-size: 0.8em; line-height: 1; color: #999;">Continue à apprendre et expérimenter.</p>
      </div>
      <div style="text-align: center; margin: 50px;">
        <span style="font-size: 1em;">Contexte Entreprise</span>
        <p style="font-size: 0.8em; line-height: 1; color: #999;">Souvent en phase d'apprentissage, recherche de mentorat.</p>
      </div>
    </div>
  </div>

  <!-- Section Développeurs Seniors -->
  <div style="flex: 1; margin: 10px; text-align: center;" v-click="4">
    <span style="font-size: 1.2em; font-weight: bold; color:#4ECDC4;">Senior</span>
    <div style="margin-top: 10px;">
      <div style="text-align: center; margin: 10px;">
        <span style="font-size: 1em;">Souvent mentor</span>
        <p style="font-size: 0.8em; line-height: 1; color: #999;">Guide les équipes, partage son expertise.</p>
      </div>
      <div style="text-align: center; margin: 50px;">
        <span style="font-size: 1em;">Contexte Entreprise</span>
        <p style="font-size: 0.8em; line-height: O.4; color: #999;">Expérience approfondie, gestion de projets et leadership.</p>
      </div>
    </div>
  </div>
</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span><i>Les développeurs apportent des qualités uniques qui enrichissent leurs rôles dans les entreprises.</i></span>
  <br>
  <span>III - La Dualité Développeur Junior vs Senior</span> | 
  <span><strong>Titre :</strong> Qualités et Contextes</span> | 
  <span><strong>Page :</strong> 9</span>
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
        <img src="https://img.icons8.com/?size=100&id=118557&format=png&color=000000" alt="github copilot" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1.2em; font-weight: bold;">GitHub Copilot</span>
    <p style="font-size: 1em;">Gains de productivité</p>
      </div>
      <div style="text-align: center; margin: 10px;">
        <img src="https://img.icons8.com/?size=100&id=Nts60kQIvGqe&format=png&color=000000" alt="chatgpt" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
    <span style="font-size: 1.2em; font-weight: bold;">ChatGPT</span>
    <p style="font-size: 1em;">Automatisation des tâches répétitives simplifiées</p>
      </div>
    </div>
  </div>
</div>
<div style="display: block; justify-content: space-between; margin-top: 20px;">

  <!-- Section Défis -->
  <div style="display: flex; margin: 10px; text-align: center;" v-click:4>
    <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; align-items: center; margin-top: 10px;">
      <div style="text-align: center; margin: 10px;">
        <img src="https://img.icons8.com/?size=100&id=0CSLuQjkskRL&format=png&color=000000" alt="Dépendance" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em;">Dépendance : Risque de perte de compétences fondamentales</span>
      </div>
      <div style="text-align: center; margin: 10px;">
        <img src="https://img.icons8.com/?size=100&id=G7aTGVA0qqPg&format=png&color=000000" alt="Qualité du code" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em;">Qualité du code : Importance de l'expertise humaine</span>
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
  <span style="background-color: #FBAF00; font-weight: bold; padding: 8px; border-radius: 5px; color: #FFF; font-size: 1.5em; line-height: 1.2;">Impact sur la Compétition entre les Frameworks</span>
</div>

<div style="margin-top: 20px; text-align: center;" v-click:2>
  <!-- Section IA centrée -->
  <div style="margin-bottom: 20px;">
    <p style="font-size: 1em; margin-top: 10px;">Facile d'être à jour<br>sur les Frameworks</p>
  </div>
</div>

<div style="display: flex; justify-content: space-between; margin-top: 20px;">
  <!-- Section Facilitation -->
  <div style="flex: 1; margin: 10px; text-align: center;">
    <span style="font-size: 1.2em; font-weight: bold;" v-click:3>Facilitation</span>
    <div style="margin-top: 10px;" v-click:4>
      <div style="text-align: center; margin: 10px;">
        <img src="https://img.icons8.com/?size=100&id=50898&format=png&color=000000" alt="Adoption des technologies" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em;">Adoption des nouvelles technologies<br>Réduction des frictions</span>
      </div>
      <div style="text-align: center; margin: 10px;" v-click:5>
        <img src="https://img.icons8.com/?size=100&id=24888&format=png&color=000000" alt="Passage entre frameworks" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em;">Passage plus facile entre frameworks</span>
      </div>
    </div>
  </div>

  <!-- Section Défis -->
  <div style="flex: 1; margin: 10px; text-align: center;">
    <span style="font-size: 1.2em; font-weight: bold;" v-click:6>Défis</span>
    <div style="margin-top: 10px;">
      <div style="text-align: center; margin: 10px;" v-click:7>
        <img src="https://img.icons8.com/?size=100&id=u1STh6KhRMdj&format=png&color=000000" alt="Fragmentation" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em;">Fragmentation<br>Risque d'adoption superficielle</span>
      </div>
      <div style="text-align: center; margin: 10px;" v-click:8>
        <img src="https://img.icons8.com/?size=100&id=VDdxpgm_aTTx&format=png&color=000000" alt="Complexité" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="font-size: 1em;">Complexité : Difficulté à maintenir des projets</span>
      </div>
    </div>
  </div>
</div>

<div style="position: absolute; bottom: 10px; left: 0; right: 0; text-align: center; font-size: 0.8em; color: #666; background-color: #eee;">
  <span><i>Je veux être un bon développeur ! Dois-je être à la pointe des nouveaux frameworks JS et des tendances web ?</i></span>
  <br>
  <span>IV. L'IA : Un Atout pour Tous les Développeurs ?</span> | 
  <span><strong>Titre :</strong> b - Impact sur la Compétition entre les Frameworks</span> | 
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
<div style="display: flex">
      <div style="text-align: center; margin: 10px;" v-click:3>
        <img src="https://img.icons8.com/ios/50/balance.png" alt="Innovation vs Fondamentaux" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Demande moderne</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click:3>
        <img src="https://img.icons8.com/ios/50/balance.png" alt="Innovation vs Fondamentaux" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Compétition</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click:3>
        <img src="https://img.icons8.com/ios/50/balance.png" alt="Innovation vs Fondamentaux" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Choix réfléchi</p>
      </div>
      <div style="text-align: center; margin: 10px;" v-click:4>
        <img src="https://img.icons8.com/?size=100&id=4aUvAATdDLe5&format=png&color=000000" alt="Rôle de l'IA" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Rester maître des situations</p>
      </div>
</div>

<div style="display: flex; justify-content: space-between; margin-top: 20px;">
  <!-- Section Synthèse -->

[//]: # (  <div style="flex: 1; margin: 10px; text-align: center;">)

[//]: # (    <div style="margin-top: 10px;">)

[//]: # (      <div style="text-align: center; margin: 10px;" v-click:3>)

[//]: # (        <img src="https://img.icons8.com/ios/50/balance.png" alt="Innovation vs Fondamentaux" style="width:40px; height:40px; display: block; margin: 0 auto;"/>)

[//]: # (        <span style="background-color: rgba&#40;81, 52, 77, 0.2&#41;; color: #51344D; font-size: 1.1em; font-weight: bold; padding: 8px; border-radius: 5px;">Demande moderne</span>)

[//]: # (        <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Compétition</p>)

[//]: # (      </div>)

[//]: # (      <div style="text-align: center; margin: 10px;" v-click:4>)

[//]: # (        <img src="https://img.icons8.com/?size=100&id=4aUvAATdDLe5&format=png&color=000000" alt="Rôle de l'IA" style="width:40px; height:40px; display: block; margin: 0 auto;"/>)

[//]: # (        <span style="background-color: rgba&#40;81, 52, 77, 0.2&#41;; color: #51344D; font-size: 1.1em; font-weight: bold; padding: 8px; border-radius: 5px;">Choix réfléchi</span>)

[//]: # (        <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Outil complémentaire, non substitut</p>)

[//]: # (      </div>)

[//]: # (    </div>)

[//]: # (  </div>)

  <!-- Section Réponse à la Question Centrale -->
  <div style="flex: 1; margin: 10px; text-align: center;">
    <div style="margin-top: 10px;">
      <div style="text-align: center; margin: 10px;" v-click:6>
        <img src="https://img.icons8.com/?size=100&id=Cc5U1vG2huUW&format=png&color=000000" alt="Bon Développeur" style="width:40px; height:40px; display: block; margin: 0 auto;"/>
        <span style="background-color: rgba(81, 52, 77, 0.2); color: #51344D; font-size: 1.1em; font-weight: bold; padding: 8px; border-radius: 5px;">Bon Développeur</span>
        <p style="font-size: 0.9em; margin-top: 2px; margin-bottom: 5px;">Adaptabilité</p>
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
