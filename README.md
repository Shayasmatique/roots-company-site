# roots-company-site
Site vitrine public de Root’s Company (fichiers compilés uniquement).

## Publication du 30 octobre 2026

Le chat d’accueil indique son fonctionnement automatique et propose un lien direct
vers Root’s Hub. Ses commandes restent accessibles sur petit écran, y compris en
paysage. Échap ferme le chat et replace le focus sur son bouton d’ouverture.

Le paquet conserve les fichiers publics existants. Seul le point d’entrée HTML
change, avec un nouveau fichier JavaScript et une feuille de style limitée au chat.
Les autres composants du JavaScript publié sont conservés à l’identique.
Aucun code serveur, donnée client ou secret n’est inclus dans cette livraison.

Contrôles réalisés : rendu et envoi d’un message sur ordinateur (1280 × 720),
portrait (390 × 844), paysage (667 × 375), accès au Hub, fermeture clavier,
absence d’erreur JavaScript, comparaison des fichiers avec le paquet précédent.
Les formats mobiles ont été contrôlés dans le navigateur, pas sur un téléphone physique.

La publication GitHub Pages est déclenchée par la mise à jour de
`roots-company-site.zip` sur `main`. Pour revenir à la version précédente,
restaurer ce fichier depuis le commit précédent et republier.
