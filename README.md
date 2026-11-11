# 🏀 LaFeuille

**La feuille de stats de basket, en direct, dans votre poche.**

<p>Saisissez les stats de vos matchs depuis votre téléphone, tablette ou PC, et laissez parents, joueurs et supporters les suivre en temps réel.</p>
<p>Sans compte et sans installation.</p>
<p align="center">
  <a href="https://ludopoire.github.io/LaFeuille/">
    <img src="docs/img/readme_button.png" alt="Essayer LaFeuille" width="240">
  </a>
</p>



## ✨ Ce que fait LaFeuille

### Pour le statisticien : la saisie
- **Saisie en direct** : points, rebonds, passes, interceptions, balles perdues, fautes… en un clic par action.
- 
- **Effectif prêt à l'emploi** : import de l'effectif depuis un fichier Excel, joueurs triées par numéro, affichage « initiale du prénom + nom » (ex. V. Wembanyama).
- **Présents, titulaires, absents** : avant le coup d'envoi, chaque joueur est marqué présent, titulaire ou absent. Les absents n'apparaissent pas dans les stats.
- **Fautes lisibles** : les fautes d'équipe s'affichent en 5 petits carrés (le dernier en rouge).
- **Tableau de stats avec évaluation (EVAL)**, sans fioritures inutiles.
- **Clôture et réouverture** d'un match, avec sauvegarde.

<p align="center">
    <img src="docs/img/page_accueil.png" alt="Page d'accueil" height="400">
    <img src="docs/img/saisie.png" alt="Ecran de saisie d'un match" height="400">
    <img src="docs/img/suivi_a_deux.png" alt="Suivi à deux" height="400">
    <img src="docs/img/stats_2.png" alt="Tableau de stats d'un match" height="400">
</p>

<p align="center">
Page d'accueil, écran de saisie (possible à deux) et export de statistiques.
</p>


### Pour les spectateurs : le suivi sans compte
- **Un simple code de match** : score, chrono, toutes les stats et historique action par action (play-by-play).
- **Scoreboard plein écran** pour projeter le score dans la salle.
- Pas de compte, pas d'application à télécharger.

<p align="center">
    <img src="docs/img/qr_share.png" alt="Partage d'un match" height="400">
    <img src="docs/img/suivi-direct.png" alt="Stats en direct" height="400">
    <img src="docs/img/play_by_play.png" alt="Play-by-play" height="400">
</p>

<p align="center">
Partage par code ou QR, suivi des stats en direct et play-by-play
</p>

### Pour les clubs : saisons et groupes
- **Fiches joueurs et saisons** : moyennes, progression au fil des matchs.
- **Espaces par groupe ou catégorie** (U11, U13, U15, U18…) : chaque coach ne voit et ne modifie que ses groupes.
- **Comptes à rôles** : administrateur, statisticien, lecteur.

<p align="center">
    <img src="docs/img/joueurs_et_saisons.png" alt="Joueurs et saisons" height="400">
    <img src="docs/img/fiche-joueur.png" alt="Fiche joueur" height="400">
    <img src="docs/img/gestion_effectifs.png" alt="Gestion des effectifs" height="400">
</p>

<p align="center">
Stats par saison, fiches joueurs et gestion des effectifs. 
</p>

### Facile d'utilisation
LaFeuille s'installe comme une vraie application sur l'écran d'accueil (PWA), sur Android comme sur iPhone.

L'outil est aussi utilisable directement sur votre navigateur Internet préféré !



---



## 🚀 Comment l'utiliser

1. **Spectateur ?** Ouvrez le site, cliquez sur *« Suivre un match en direct »* et entrez le code du match donné par le statisticien.
2. **Statisticien ?** Connectez-vous, choisissez votre groupe, créez le match, sélectionnez les présents et les titulaires, puis saisissez action après action. Partagez le code ou le lien du match pour que tout le monde suive en direct.
3. **Coach ou club ?** Demandez la création de votre compte et de vos catégories depuis la page d'accueil. Votre espace est préparé et activé dès validation.

---

## 📱 L'interface

**Curieux ?** Cliquez sur *« Tester par vous-même ! »* pour explorer l'appli en mode démo.

<p align="center">
  <img src="docs/img/login.png" alt="Écran de connexion" width="280">
</p>

---

## 🛠️ Sous le capot

Pour les curieux qui voudraient ré-utiliser cet outil ou le personnaliser à leur guise, voici son architecture !

| Outil | Rôle |
|---|---|
| Un seul fichier `index.html` | L'application complète (HTML, CSS, JavaScript) |
| [GitHub Pages](https://pages.github.com/) | Hébergement du site |
| [Supabase](https://supabase.com/) | Base de données, comptes et synchronisation en direct |

Aucune étape de compilation : modifier `index.html`, publier, c'est en ligne.



---


## 📬 Contact

Une question, une idée, une demande de compte ? Utilisez le formulaire de la page d'accueil ou ouvrez une [issue](../../issues).

---

<p align="center"><i>Fait avec ❤️ pour ceux qui passent leurs week-ends sur ou à côté des terrains.</i></p>
<p align="center"><i>Ludo Poiré. 2026</i></p>

