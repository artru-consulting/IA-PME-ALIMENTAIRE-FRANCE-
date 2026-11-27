# Claudets.fr

L'IA au service des PME françaises.

## État au 26 novembre 2026

- Dépôt concerné : artru-consulting/IA-PME-ALIMENTAIRE-FRANCE-
- URL de test : https://artru-consulting.github.io/IA-PME-ALIMENTAIRE-FRANCE-/
- GitHub Pages : branche main, dossier racine.
- Site en test : meta robots noindex, nofollow et robots.txt Disallow: / conservés.
- PDF Qualiopi conservé : assets/certificat_qualiopi_25FOR01091.2.pdf.
- Aucun fichier CNAME ajouté.
- Modifications locales à relire. Aucun commit ni push sans l'accord de Pierre.

## Modifications préparées

- Négociations annuelles en première question et premier onglet, actif par défaut.
- Photos inversées et chargées depuis assets, avec leurs dimensions réelles.
- Diagnostic par équipe : deux personnes représentatives, plafond de 1 750 € HT par service.
- Encadré Mission en cours, sans nom de client ni résultat annoncé.
- Expertises simplifiées et présentation de l'équipe sans répétition du pilotage.
- FAQ remplacée par les sept questions demandées.
- Rendez-vous de découverte de 30 minutes. L'adresse Calendly est centralisée dans le lien #rendez-vous-decouverte. Les autres boutons la reprennent en JavaScript ; sans JavaScript, ils mènent à la section contact.
- Chiffres sans zéro barré : Aileron est auto-hébergée et limitée aux caractères U+0030-0039. Les lettres restent en Atkinson. Licence et origine dans assets/fonts/LICENSE-Aileron.txt.

## Vérifications avant validation

Contrôles du code et des fichiers passés : liens locaux et ancres, dimensions des images, FAQ, texte, intégrité de robots.txt et du PDF, absence de CNAME. Le script réel a été exécuté avec une simulation du DOM pour vérifier les onglets, le clavier, le menu et les liens de rendez-vous. Le spécimen Aileron montre des zéros non barrés.

Restent à vérifier dans un navigateur : captures pleine page 1440 px et 390 px, affichage complet des chiffres et des tarifs, recadrage des photos, console et ouverture effective du nouveau lien Calendly. Ces contrôles ne sont pas présentés comme réalisés.

L'accès distant à GitHub et le navigateur de contrôle ne sont pas disponibles dans cette session. La copie locale du dépôt sert de base au diff ; la comparaison avec main distant reste à faire.

Message de commit demandé après validation :

Négociations en premier, photos inversées, diagnostic par équipe, expertises simplifiées, zéros corrigés
