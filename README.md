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

## Accueil guidé — 3 novembre 2026

Le chat recueille l’activité, le besoin et le délai, puis propose la réservation existante, le Hub ou un e-mail prérempli. Son fonctionnement reste automatique et local à l’onglet ; aucun envoi n’est effectué par le chat. Le thème reprend le lapin et les couleurs Root’s.

Le ZIP de référence est conservé. Le workflow applique ensuite les fichiers de welcome-update et vérifie leurs empreintes avant publication. Le reste du JavaScript et les autres médias sont inchangés. Pour revenir à l’accueil précédent, annuler ce commit (workflow et overlay ensemble), puis republier. Une modification future du ZIP doit prendre en compte cet overlay.

La source du composant est versionnée dans roots-hub. La preuve de préservation et les empreintes sont dans welcome-update/build-proof.json et welcome-update.sha256. Les formats ordinateur, portrait et paysage sont contrôlés dans le navigateur, sans prétendre à un essai sur téléphone physique.
