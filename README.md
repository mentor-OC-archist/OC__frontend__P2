# EXERCICES/TRAINING 1: du cours "[Apprenez à créer votre site web avec HTML5 et CSS3](https://openclassrooms.com/fr/courses/1603881-apprenez-a-creer-votre-site-web-avec-html5-et-css3)"

[![vidéo d'intro](https://i.imgur.com/vKb2F1B.png)](https://player.vimeo.com/video/243808027?color=7451eb)

---

## RESSOURCES DE DÉPART:
- [URL OC de l'exercice](https://openclassrooms.com/fr/courses/1603881-apprenez-a-creer-votre-site-web-avec-html5-et-css3/4214576-pratiquez)
- [URL Codepen de l'exercice](https://codepen.io/nicolaspatschkowski/pen/yLNXQaO?editors=1100)
- Ouvrir ce dossier dans un terminal et lancer la commande suivante: "code codepen" afin de réaliser l'exercice en sur votre ordinateur (en local donc, [tag](https://github.com/achicyr/OC__frontend__P2/tree/exos.3))
 
---

Voici un nouvel exercice pour mettre en pratique vos compétences en CSS3 et HTML5. 
<br>
Ouvrez [cet éditeur CodePen en ligne](https://codepen.io/nicolaspatschkowski/pen/yLNXQaO?editors=1100). 
<br>
Vous allez effectuer la mise en page d'un site qui s'appelle 'Le blog trotter' ! Pour cela, effectuez les tâches suivantes :

1. Une balise sémantique  <nav> manque, ajoutez-la au bon endroit.
2. Retirez les puces de la liste à puces (à vous de trouver comment faire !).
3. Placez le header et le menu côte à côte.
4. Affichez les paragraphes en justifié, sur 80 % de largeur, et centrez leurs blocs sur la page.

Vous allez construire votre première page HTML. Choisissez bien les balises (vous avez le droit de revoir les chapitres précédents !), placez-les au bon endroit, et CodePen actualisera automatiquement la page pour vous montrer le résultat de votre code.

---

![i](data:image/svg+xml;base64,PHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHdpZHRoPSczMicgaGVpZ2h0PSczMicgdmlld0JveD0nMCAwIDMyIDMyJz48cGF0aCBmaWxsPScjZjM5NTM5JyBkPSdNMjYuNCAyMi4yYzEtMS45IDEuNi00IDEuNi02LjMgMC03LjYtNi4yLTEzLjgtMTMuOC0xMy44cy0xMy44IDYuMi0xMy44IDEzLjggNi4yIDEzLjggMTMuOCAxMy44YzMuNSAwIDYuNy0xLjMgOS4yLTMuNWw3LjIgMi00LjEtNS45ek0xMi43IDIyLjZjLTAuNyAwLTEuMi0wLjYtMS4yLTEuMyAwLTAuOCAwLjYtMS41IDEuNC0xLjUgMC43IDAgMS4yIDAuNiAxLjIgMS4zIDAgMC44LTAuNiAxLjQtMS40IDEuNHpNMTQuMSAxOC4xaC0xLjRsMS43LTEwLjVoMi4xbC0yLjMgMTAuNXonLz48L3N2Zz4=)
Dans cet éditeur, la feuille de style CSS est automatiquement liée au HTML par CodePen. Sur du code HTML "normal", il faudrait ajouter une balise de style dans le  &lt;head&gt; , comme ceci :   &lt;link rel="stylesheet" type="text/css" href="style.css"&gt;

![i](data:image/svg+xml;base64,PHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHdpZHRoPSczMicgaGVpZ2h0PSczMicgdmlld0JveD0nMCAwIDMyIDMyJz48cGF0aCBmaWxsPScjM2ZhNWRiJyBkPSdNMjYuNCAyMi4yYzEtMS45IDEuNi00IDEuNi02LjMgMC03LjYtNi4yLTEzLjgtMTMuOC0xMy44cy0xMy44IDYuMi0xMy44IDEzLjggNi4yIDEzLjggMTMuOCAxMy44YzMuNSAwIDYuNy0xLjMgOS4yLTMuNWw3LjIgMi00LjEtNS45ek0xMy40IDIyLjNjMC4xIDAuMSAwLjIgMC4xIDAuMyAwLjEgMC4xIDAgMC4zLTAuMSAwLjUtMC4yIDAuNS0wLjQgMS0xIDEuNi0xLjdsMC41IDAuM2MtMC42IDAuOS0xLjMgMS43LTIuMiAyLjQtMC42IDAuNS0xLjIgMC43LTEuOCAwLjctMC40IDAtMC43LTAuMS0wLjktMC4zcy0wLjQtMC41LTAuNC0wLjhjMC0wLjMgMC4xLTAuOSAwLjMtMS43bDEuOC02LjFjMC4zLTEgMS0zLjQgMS0zLjRsMi4xLTAuMy0yLjcgOS42Yy0wLjIgMC42LTAuMyAxLTAuMyAxLjIgMCAwLjEgMCAwLjMgMC4xIDAuNHpNMTcgOC4xYy0wLjMgMC4zLTAuNiAwLjQtMSAwLjRzLTAuNy0wLjEtMS0wLjRjLTAuMy0wLjMtMC40LTAuNi0wLjQtMSAwLTAuNCAwLjEtMC43IDAuNC0xIDAuMy0wLjMgMC42LTAuNCAxLTAuNHMwLjcgMC4xIDEgMC40YzAuMyAwLjMgMC40IDAuNiAwLjQgMSAwIDAuNC0wLjEgMC43LTAuNCAxeicvPjwvc3ZnPg==)
Bien sûr, ce qui est demandé dans cet exercice est le minimum, mais n'hésitez pas à **aller plus loin** ! Modifiez les couleurs, le style, ajoutez du contenu... Testez, CodePen vous le permet : vous êtes sûr de ne rien casser. 😉

---

- ### <u style="color:red">AVANT</u>:
![qlqlchose](https://raw.githubusercontent.com/achicyr/OC__frontend__P2/exos.3/1.png)
- ### **<u style="color:red">APRÈS</u>**:
![qlqlchose](https://raw.githubusercontent.com/achicyr/OC__frontend__P2/exos.3/2.png)

---

## SOLUTIONS: 
- Solution codepen: [URL Codepen de la solution de l'exercice](https://codepen.io/nicolaspatschkowski/pen/WNvOYGN?editors=1100 "solution du cours OC")
- Solution local: [URL Git repository tag "exos.3-sol"](https://github.com/achicyr/OC__frontend__P2/tree/exos.3-sol) ===>>> le fichier est à: ./codepen/mentor.html
- Solution youtube: [URL Youtube de la solution de l'exercice par le mentor](lkjlkjfds "solution mentor")

