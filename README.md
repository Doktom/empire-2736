# ⚜ Empire 2736

Jeu de gestion économique, cynique et décalé, qui se joue dans le navigateur.

**An 2736.** Les mégacorporations possèdent tout, y compris la France. Vous êtes Napoléon Bonaparte-Dupont, 19e du nom, et vous voulez la racheter, province par province.

## Jouer

Aucune installation : ouvrez `index.html` dans un navigateur.

```bash
# ou, avec un petit serveur local
python -m http.server 8000
# puis http://localhost:8000
```

## But du jeu

Racheter les **8 provinces** de France en **40 trimestres** pour obtenir le **Sacre**. Sinon, finir avec le plus gros patrimoine possible, sans faire faillite ni finir en exil sur une station orbitale.

## Mécaniques

- **Corporation** : 6 activités à améliorer (mines de lithium, cafés synthétiques, drones, nano-brume…), une politique sociale et un niveau de sécurité industrielle.
- **Bourse mondiale** : 6 mégacorporations fictives, dividendes, actualités (dont 1 sur 5 est fausse), rumeurs, calomnies et infos d'initié.
- **Radar du Conseil** : les manœuvres douteuses l'alimentent. À 100, procès. Au deuxième procès, exil : fin de partie.
- **Banque** : emprunt avec intérêts, découvert, faillite possible.
- **Reconquête** : 8 provinces, chacune avec un revenu fixe et un coût en suspicion.
- **Décrets impériaux** : bonus permanents achetés avec la Gloire.
- **Missions** et **conseiller** intégré pour guider les débutants.
- **Événements aléatoires** avec choix et conséquences.
- **3 niveaux de difficulté**, sauvegarde automatique à chaque trimestre.

Raccourcis : `Espace` pour clore le trimestre, `1` à `6` pour changer d'onglet.

## Technique

Un seul fichier HTML, sans dépendance ni build : HTML, CSS et JavaScript vanilla. La partie est sauvegardée dans le `localStorage` du navigateur.

## Licence

MIT. Voir [LICENSE](LICENSE).
