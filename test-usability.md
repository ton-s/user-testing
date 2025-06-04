# Test d'utilisabilité

## Plan
1. Introduction
2. Entretien Pré-Test
3. Scénario
4. Questionnaire : [UEQ](https://forms.gle/hPe9bXhZwvbx4Rqp9)
5. Entretien Post-Test

## Introduction

Vous allez utiliser l'extension VSCode appelée **FlowTabs** qui permet d'améliorer la synchronisation et la gestion de vos onglets de votre navigateur web ainsi que vos fenêtres d'applications sur votre bureau directement depuis votre IDE. Cet outil vous permet de naviguer rapidement entre les ressources et votre environnement de travail sans encombrement. Donc, on ne va pas tester vos compétences en programmation mais l’outil en question.


## Prérequis

- **VSCode**
- **Google Chrome** (navigateur web par défaut)
- **Windows**


## Installation de l'outil

1. Si tout s'est bien passé, vous avez cloné le dépôt GitHub et vous devriez voir un dossier pour l'extension Chrome ainsi qu’un dossier pour l'extension VSCode.
2. Installez le fichier `.vsix` dans VSCode :
    - Ouvrez la section des extensions
    - Cliquez sur les trois petits points en haut à droite
    - Sélectionnez **"Install from VSIX..."** et chargez le fichier
3. Installez l'extension Chrome :
    - Activez le mode développeur dans [chrome://extensions](chrome://extensions) dans Chrome
    - Cliquez sur **"Load unpacked"** et sélectionnez le dossier de l'extension chrome
4. Félicitations ! L’extension est prête à l'emploi et apparaît dans la barre latérale gauche de VSCode.


## Scénario

### Contexte fictif

"Tu es développeur(se) sur une application encore en phase de développement. Ton quotidien consiste à jongler entre plusieurs ressources : la documentation technique, l'application en cours d'exécution, des sites de référence liés à la technologie utilisée, et bien sûr ton environnement de développement sous VSCode. Pour t'aider à gagner en productivité et à éviter de te disperser, un collègue te suggère d'utiliser l'extension FlowTabs, qui te permet de centraliser tous ces outils directement dans ton éditeur.  
Ce même collègue, qui travaillait auparavant sur un projet web, t’a désormais passé le relais. Il t’a transmis une liste de tâches à poursuivre pour assurer la continuité du développement, ainsi que des ressources que tu dois impérativement consulter."


### Tâches à accomplir

1. **Découverte du projet**  
Tu remarqueras qu’un fichier `index.html` est présent dans le projet. Ce fichier contient une série de tâches à compléter.
Commence par ouvrir un terminal externe dans le dossier du projet (celui contenant ce fichier HTML).
Une fois cela fait, tu peux désormais voir ce terminal directement depuis l’extension **Flowtabs**.

---

2. **Début de la navigation via l’extension**  
Retourne dans l’onglet du terminal en cliquant dessus via l’interface de l’extension.
Ensuite, exécute la commande suivante dans le terminal pour lancer ton projet web : `start index.html`  
Cela ouvrira la page web dans ton navigateur par défaut, et elle sera automatiquement ajoutée à la liste des ressources visibles dans l’extension **Flowtabs**.

---

3. **Première tâche `TODO [1]`**  
Après cette première prise en main de **Flowtabs**, on passe aux choses sérieuses.  
En observant le fichier HTML, tu remarqueras un premier commentaire noté "TODO [1]". Ton collègue te demande ici de compléter le champ email et numéro de téléphone du permanent pour sa carte de profil.
Ces informations se trouvent sur la page suivante :  
👉 https://application.age-namur.be/contacts  
Vas-y chercher les données nécessaires, puis insère-les dans les emplacements prévus dans le code (n'oublie pas de rafraîchir la page de ton site pour voir tes modifications).

---

4. **Ajout en favori**  
Une fois cette ressource consultée, pense à l’ajouter aux favoris via l’extension **Flowtabs**. Survolez la ressource concernée et cliquez sur l'étoile pour l'ajouter à vos favoris (comme onglet pertinent).  
Elle te servira à nouveau plus tard dans les prochaines étapes.

---

5. **Deuxième tâche `TODO [2]`**   
L'utilisateur souhaite pouvoir changer le thème de la carte de profil (mode clair / mode sombre) via un bouton déjà présent dans l'interface. Cependant, la fonctionnalité n’a pas encore été implémentée. Ton collègue t’a laissé quelques ressources importantes pour t’aider à activer cette fonctionnalité facilement :

👉 [Comment récupérer un élément HTML par son ID](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById)  
👉 [Basculer entre les modes clair et sombre (dark mode)](https://www.w3schools.com/howto/howto_js_toggle_dark_mode.asp)

---

6. **Troisième tâche `TODO [3]`**  
Ton collègue avait commencé à intégrer une horloge, mais n’a pas pu finaliser la logique JavaScript pour l’affichage dynamique de l’heure. Peux-tu compléter son code afin d’afficher l’heure actuelle en temps réel ? Voici les ressources que tu dois impérativement consulter.

👉 [Obtenir l’heure actuelle en JavaScript](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/Date/toLocaleTimeString)  
💡 D’autres ressources pourraient être encore utiles : n’hésite pas à les retrouver via l'extension Flowtabs.

---

7. **Quatrième tâche `TODO [4]`**

Cette fois, ton collègue ne t’a pas fourni de ressources, mais il te demande d’ajouter une petite amélioration à sa fonction d’affichage de la carte. Il souhaite que la carte s’affiche automatiquement 2 secondes après le chargement de la page.
Puisqu’il ne t’a rien partagé, tu vas devoir faire ta propre recherche. Pour cela, utilise la fonctionnalité de recherche web rapide de Flowtabs.
Rends-toi dans la section `All Tabs`, puis clique sur l’icône en forme de loupe, ou utilise le raccourci clavier `Ctrl + Shift + S`.  
Une barre de recherche s'affiche, tape : `setTimeout javascript MDN Docs`.  
Une page de résultats Google s’ouvrira automatiquement : consulte le premier lien pour trouver les informations nécessaires et accomplir la tâche.

---

8. **Dernière tâche `TODO [last]`**  
Pour terminer, on peut voir que la "description" du profil n'est pas terminée, il est noté **"Si tu as des questions sur ..."**. La phrase complète se trouve dans la source que je t'ai demandé de mettre en favori. Rends-toi là-bas pour achever le projet.

<br>

**Félicitations**, le projet est terminé !


