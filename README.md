#AVXNO-GAMMING / AVHIRAL 2024 

Version : 1.0 - CODE : DAVID PILATO
AVXNO-GAMMING est un programme permettant d'exécuter des jeux ou des logiciels nécessitant des instructions AVX (Advanced Vector Extensions) sur des processeurs ne supportant pas ces instructions. Il utilise l'outil Intel SDE (Software Development Emulator) pour émuler les instructions manquantes tout en optimisant les performances pour garantir une fluidité maximale lors de l'exécution.
________________________________________
Fonctionnalités principales
•	Emulation AVX : Support des jeux nécessitant AVX, AVX2 ou AVX-512 via Intel SDE.
•	Optimisation CPU/GPU : Priorité haute attribuée aux processus pour une utilisation maximale des ressources matérielles.
•	Surveillance des processus : Vérification en direct de l'état du jeu chargé en mémoire.
________________________________________
Utilisation
1.	Sélectionnez le fichier sde.exe :
o	Cliquez sur Parcourir dans la première section.
o	Naviguez vers le dossier contenant sde.exe (Intel SDE décompressé) et sélectionnez-le.
2.	Sélectionnez le fichier .exe du jeu ou du logiciel :
o	Cliquez sur Parcourir dans la deuxième section.
o	Naviguez vers le fichier exécutable du jeu (ex : jeu.exe) et sélectionnez-le.
3.	Cliquez sur le bouton START NO AVX pour démarrer.
o	Le bouton passe à l'état Lancement Please Wait.... Pendant le démarrage.
o	Les logs en temps réel affichent :
	La commande exécutée.
	L'état de chargement en mémoire du jeu.
	Tout message d'erreur éventuel.
4.	Une fois le processus terminé ou en cas d'arrêt, le bouton revient à l'état START NO AVX.
________________________________________
Commandes SDE utilisées
•	-hsw : Active l'émulation AVX et AVX2 (Haswell).
•	-no-shared-libs : Empêche le chargement inutile de bibliothèques partagées.
•	-- : Permet de séparer les arguments SDE de ceux du jeu/logiciel.
________________________________________
Bonnes pratiques
•	Lancez le programme en mode administrateur pour garantir l'application correcte des priorités du processus.
•	Assurez-vous que votre système dispose d'une puissance suffisante pour exécuter le jeu via l'émulateur.
•	Vérifiez régulièrement les logs affichés pour détecter d'éventuelles erreurs.
________________________________________
Limitations connues
1.	Performance réduite : L'émulation AVX peut être gourmande en ressources, surtout sur des processeurs plus anciens.
2.	Compatibilité Intel SDE : Certaines options avancées d'optimisation peuvent ne pas être reconnues selon la version de SDE.
3.	Latence sonore : Quelques défauts sonores peuvent persister sur certains jeux à forte charge CPU.

DOWNLOAD SDE INTEL : https://www.avhiral.com/download/sde.zip  OU: https://www.intel.com/content/www/us/en/download/684897/intel-software-development-emulator.html

DON PAYPAL : https://www.paypal.com/donate/?hosted_button_id=EZW7NMLW8YG4W
