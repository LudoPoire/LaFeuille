# 🏀 LaFeuille

**La feuille de stats de basket, en direct, dans votre poche.**

<p>Saisissez les stats de vos matchs depuis votre téléphone, tablette ou PC, et laissez parents, joueurs et supporters les suivre en temps réel.</p>
<p>Sans compte et sans installation.</p>

👉 **[Essayer LaFeuille](https://ludopoire.github.io/LaFeuille/)**

<p align="center">
  <img src="docs/img/01-accueil.png" alt="Écran d'accueil de LaFeuille" width="280">
  <img src="docs/img/02-saisie.png" alt="Écran de saisie d'un match" width="280">
  <img src="docs/img/03-scoreboard.png" alt="Scoreboard pour projection" width="280">
</p>

---

## ✨ Ce que fait LaFeuille

### Pour le statisticien : la saisie
- **Saisie en direct** : points, rebonds, passes, interceptions, balles perdues, fautes… en un clic par action.
- **Effectif prêt à l'emploi** : import de l'effectif depuis un fichier Excel, joueurs triées par numéro, affichage « initiale du prénom + nom » (ex. V. Wembanyama).
- **Présents, titulaires, absents** : avant le coup d'envoi, chaque joueur est marqué présent, titulaire ou absent. Les absents n'apparaissent pas dans les stats.
- **Fautes lisibles** : les fautes d'équipe s'affichent en 5 petits carrés (le dernier en rouge).
- **Tableau de stats avec évaluation (EVAL)**, sans fioritures inutiles.
- **Clôture et réouverture** d'un match, avec sauvegarde.

<p align="center">
  <img src="docs/img/04-stats.png" alt="Tableau de stats d'un match" width="300">
</p>

### Pour les spectateurs : le suivi sans compte
- **Un simple code de match** : score, chrono, toutes les stats et historique action par action (play-by-play).
- **Scoreboard plein écran** pour projeter le score dans la salle.
- Pas de compte, pas d'application à télécharger.

<p align="center">
  <img src="docs/img/05-suivi-direct.png" alt="Suivi d'un match en direct sans compte" width="300">
</p>

### Pour les clubs : saisons et groupes
- **Fiches joueurs et saisons** : moyennes, progression au fil des matchs.
- **Espaces par groupe ou catégorie** (U11, U13, U15, U18…) : chaque coach ne voit et ne modifie que ses groupes.
- **Comptes à rôles** : administrateur, statisticien, lecteur.

<p align="center">
  <img src="docs/img/06-fiche-joueur.png" alt="Fiche joueur et saison" width="300">
</p>

### Facile d'utilisation
LaFeuille s'installe comme une vraie application sur l'écran d'accueil (PWA), sur Android comme sur iPhone.

L'outil est aussi utilisable directement sur votre navigateur Internet préféré !

---

## 🚀 Comment l'utiliser

1. **Spectateur ?** Ouvrez le site, cliquez sur *« Suivre un match en direct »* et entrez le code du match donné par le statisticien.
2. **Curieux ?** Cliquez sur *« Tester par vous-même ! »* pour explorer l'appli en mode démo.
3. **Coach ou club ?** Demandez la création de votre compte et de vos catégories depuis la page d'accueil. Votre espace est préparé et activé dès validation.
4. **Statisticien ?** Connectez-vous, choisissez votre groupe, créez le match, sélectionnez les présents et les titulaires, puis saisissez action après action. Partagez le code ou le lien du match pour que tout le monde suive en direct.

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

