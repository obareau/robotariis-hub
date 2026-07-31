# Robotariis Hub — Roadmap

> Brouillon factuel du 2026-08-01. Chaque ligne est adossée à un fait
> constatable, avec sa preuve — rien n'est déduit du README ni proposé par un
> modèle. À corriger et à élaguer.

## État constaté

- Page statique unique, sans dépendance, déployée sur GitHub Pages —
  `https://obareau.github.io/robotariis-hub/` répond **200**.
- **15 cartes**, 5 langues (fr, en, de, es, ja).
- **Les 13 liens sortants répondent tous 200** (vérifié le 2026-08-01), y
  compris `terra-incognita`, que la doc du homelab croyait morte — elle a été
  restaurée le 2026-07-21.
- Dernier apport de contenu : Subwave et la carte Machines, le 2026-07-21.

## À faire

### Un projet public absent du portail

- [ ] **Ajouter Quidam.** Sa démo `https://obareau.github.io/quidam/` répond
      200 et n'est citée nulle part dans le hub. C'est le seul projet à avoir
      une page publique vivante sans y figurer — alors que six projets sans
      démo y sont présents par simple lien GitHub. Un portail qui oublie une
      vitrine manque son objet.

### Décider ce que le hub montre

Neuf dépôts de `~/DEV` ont un dépôt GitHub et ne sont pas dans le hub :
Cerbère, Héphaïstos, Iris, Mnémosyne, Nemesis, Quidam, robotariis-livrejeu,
robotariis-radio, et le hub lui-même.

- [ ] Trancher le critère d'inclusion. Aujourd'hui il est implicite et le
      résultat est incohérent : `aza-sessions`, `bang`, `dim`, `mono`,
      `terminal-synth` et `calendrier-de-la-rectitude-v1` sont présents par
      lien GitHub nu, sans démo — donc « avoir un dépôt public » n'est pas le
      critère, mais rien d'autre ne l'explique.
      Un critère défendable : *tout ce qui a une page publique vivante*, plus
      les dépôts dont le code est lisible par un visiteur curieux. À écrire
      dans le README pour que la question ne se repose pas.

### Dette de publication

- [ ] Écrire les entrées de CHANGELOG manquantes — 14 commits depuis la seule
      entrée (`0.1.0`, gabarit posé par Argus le 2026-07-08). Ne sont datés
      nulle part : le multilingue 5 langues, les interventions pirates, la
      bannière et l'identité ambre, l'ajout de Subwave et de la carte Machines.

### Interventions pirates

- [ ] `pirate.js` est annoncé réutilisable (`installPirates()`) dans le README,
      mais aucun autre projet ne l'utilise. Soit c'est une intention à
      concrétiser (Recta ou Terra-Incognita seraient les hôtes naturels), soit
      la promesse de réutilisabilité est à retirer du README.

## Demandes externes (Argus)

<!-- argus:begin -->
- [ ] ⚑ Interface utilisateur améliorée
      _pourquoi : Améliorer l'expérience utilisateur pour faciliter la navigation et l'utilisation de l'outil._
- [ ] ⚑ Intégration automatique de sessions en canon
      _pourquoi : Automatiser la validation et l'intégration des sessions pour réduire le temps de travail manuel._
- [ ] ⇐ Mono : Intégrer MONO° dans le hub Robotariis pour offrir un accès centralisé à tous les outils créatifs utilisés dans la création du lore.
      _pourquoi : Cela permettrait une utilisation cohérente et coordonnée des ressources parmi toutes les équipes travaillant sur le lore._
<!-- argus:end -->

---

*Dernière mise à jour : 2026-08-01*
