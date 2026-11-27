# Claudets.fr

L'IA au service des PME françaises.

## État au 27 novembre 2026

- Dépôt concerné : artru-consulting/IA-PME-ALIMENTAIRE-FRANCE-
- URL de test : https://artru-consulting.github.io/IA-PME-ALIMENTAIRE-FRANCE-/
- GitHub Pages : branche main, dossier racine.
- Site en test : meta robots noindex, nofollow et robots.txt Disallow: / conservés.
- PDF Qualiopi conservé : assets/certificat_qualiopi_25FOR01091.2.pdf.
- Aucun fichier CNAME ajouté.
- La version préparée le 26 novembre a été déposée sur GitHub par Pierre le 27 novembre. La page publiée a été consultée dans le navigateur.
- Les trois ajouts et le témoignage de Laurent Lelimouzin ont été relus. Pierre a validé leur publication le 27 novembre.

## Version publiée

- Négociations annuelles en première question et premier onglet, actif par défaut.
- Photos inversées et chargées depuis assets, avec leurs dimensions réelles.
- Diagnostic par équipe : deux personnes représentatives, plafond de 1 750 € HT par service.
- Encadré Mission en cours, sans nom de client ni résultat annoncé.
- Expertises simplifiées et présentation de l'équipe sans répétition du pilotage.
- FAQ remplacée par les sept questions demandées.
- Rendez-vous de découverte de 30 minutes. L'adresse Calendly est centralisée dans le lien #rendez-vous-decouverte. Les autres boutons la reprennent en JavaScript ; sans JavaScript, ils mènent à la section contact.
- Chiffres sans zéro barré : Aileron est auto-hébergée et limitée aux caractères U+0030-0039. Les lettres restent en Atkinson. Licence et origine dans assets/fonts/LICENSE-Aileron.txt.

## Ajouts du 27 novembre

- Sous le rendez-vous du haut de page : préciser qu'un réglage ou un logiciel peut suffire, sans recourir à l'IA.
- FAQ : essais à côté du fonctionnement habituel, validation de la mise en service et retour au fonctionnement précédent ; comptes et accès maîtrisés par le client, documentation et éléments remis pour permettre la reprise. Les vérifications sur les données mentionnent aussi l'entraînement des modèles.
- Méthode : date du premier essai et étapes de mise en service fixées après le diagnostic. Aucun délai de démarrage imposé à tous les projets.
- Les deux nouvelles questions complètent les sept existantes. L'accordéon reste natif, sans changement de script ni de style.
- Deux blocs de témoignages, citations en italique et cinq étoiles jaunes chacun. Le texte complet de Laurent Lelimouzin est repris depuis la capture fournie par Pierre, avec son attribution et le lien vers https://artruconsulting.com/. Le témoignage de Richard Lerosey, directeur général d'Héritage, est repris mot pour mot du texte fourni par Pierre. Aucun résultat chiffré ajouté.
- Aucune nouvelle garantie chiffrée. Prix et engagements existants conservés.

## Vérifications avant validation

Contrôles du code et des fichiers passés : liens locaux et ancres, dimensions des images, FAQ, texte, intégrité de robots.txt et du PDF, absence de CNAME. Le titre du haut de page, les tarifs et le script restent identiques à la version précédente. Le script réel avait aussi été exécuté avec une simulation du DOM pour vérifier les onglets, le clavier, le menu et les liens de rendez-vous.

Vérifications dans l'aperçu local le 27 novembre : captures pleine page à 1440 px et 390 px, lisibilité du haut de page, du témoignage et des tarifs, photos chargées, absence de débordement horizontal sur mobile, onglets au clic et au clavier, menu mobile et ouverture des nouvelles questions au clic et au clavier. Les zéros des prix et du téléphone sont normaux. Aucun message d'erreur ou d'avertissement dans la console de l'aperçu du navigateur intégré.

La mise en forme des deux témoignages a aussi été vérifiée à 1440 px et 390 px : deux colonnes sur ordinateur, une colonne sur mobile, citations en italique, cinq étoiles jaunes par bloc et noms lisibles. Aucun débordement horizontal ni erreur de console observés dans l'aperçu.

Le lien Calendly a été ouvert : la page affiche bien « Claudets · Échange découverte IA · 30 min ». Les adresses tel: et mailto: ont été vérifiées sans déclencher d'appel ni de message. Captures, diff et compte rendu sont conservés dans le dossier de revue du 27 novembre, à côté de la copie du dépôt.

La comparaison avec main distant a été faite le 27 novembre : index.html et README.md étaient identiques aux fichiers de base de la revue. Cette retouche modifie uniquement ces deux fichiers.

Message de commit de la version préparée le 26 novembre :

Négociations en premier, photos inversées, diagnostic par équipe, expertises simplifiées, zéros corrigés
