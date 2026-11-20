# ⚜ Empire 2736

Roguelite économique **infini**, cynique et décalé, qui se joue dans le navigateur.

**An 2736.** Les mégacorporations possèdent tout, y compris la France. Vous êtes Napoléon Bonaparte-Dupont, 19e du nom, et vous voulez tout racheter : la France, l'Europe, le monde, puis les étoiles.

## Jouer

**▶ [Jouer en ligne](https://doktom.github.io/empire-2736/)** (directement dans le navigateur, sur ordinateur ou téléphone).

Ou en local, sans installation : ouvrez `index.html` dans un navigateur.

```bash
# ou, avec un petit serveur local
python -m http.server 8000
# puis http://localhost:8000
```

## Le principe

Il n'y a **pas de fin de partie**. Chaque *règne* est une partie : il commence très vite (la progression est explosive au début), puis les **échéances impériales** (un tribut de plus en plus lourd tous les 10 trimestres) finissent par vous rattraper. Quand vous tombez, ou quand vous **abdiquez**, vous gagnez de la **Légende ★** à dépenser dans l'**Héritage** : bonus permanents pour que le règne suivant aille plus loin.

## Mécaniques

- **Corporation** : jusqu'à 18 rangs d'activités, achat ×1 / ×10 / ×100 / max, paliers de revenus ×2 aux niveaux 10, 25, 50, 100…
- **Échéances impériales** : réserve à constituer, relique à choisir à chaque tribut payé.
- **Reliques** : 15 modificateurs de règne (bicorne maudit, contrat faustien, statue équestre…) choisis au départ puis à chaque échéance et chaque Sacre.
- **Territoires** : une conquête infinie (France, Europe, Monde, Système solaire, Galaxie…) avec un Sacre à chaque ère.
- **Bourse mondiale** : 6 mégacorporations fictives, dividendes, actualités (dont 1 sur 5 est fausse), rumeurs, infos d'initié. Vos gros ordres déplacent les cours (profondeur de marché).
- **Radar du Conseil** : les manœuvres douteuses l'alimentent. À 100, procès. Deux procès : exil, fin du règne.
- **Banque** : emprunt, découvert, saisie, faillite.
- **Décrets et réformes** : bonus achetés avec la Gloire, avec une réforme répétable à l'infini.
- **Héritage** : 14 améliorations permanentes (trésor de départ, revenus, automatisation, nouveaux rangs d'activités, etc.).
- **Vitesse** : ▶ Clore, ⏩ ×5, ⏭ ×25, ▶ Auto (s'arrête toujours au premier événement).
- **Débutants** : tutoriel, conseiller intégré, missions guidées, boutons explicites sur ce qu'il manque.
- **Événements aléatoires** avec choix et conséquences.

Raccourcis : `Espace` pour clore le trimestre, `A` pour l'auto, `1` à `6` pour changer d'onglet.

## Technique

Un seul fichier HTML, sans dépendance ni build : HTML, CSS et JavaScript vanilla. Le règne en cours et l'Héritage sont sauvegardés dans le `localStorage` du navigateur (sauvegarde automatique à chaque trimestre).

## Licence

MIT. Voir [LICENSE](LICENSE).
