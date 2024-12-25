# Administration-du-systeme : <br>
Voici une collection de scripts batch utiles pour la gestion et la surveillance des systèmes Linux : <br>

1- [DirectorySize.sh](https://github.com/naimiatef/Administration-du-systeme/blob/main/DirectorySize.sh) : affiche la taille d'un répertoire spécifié <br>
2- [Test-File.sh](https://github.com/naimiatef/Administration-du-systeme/blob/main/test-file.sh) : évaluer l'état d'un fichier/répertoire <br>
3- [Server-Health.sh](https://github.com/naimiatef/Administration-du-systeme/blob/main/server-health.sh) : rapport d'informations relatives au serveur <br>
4- [CPU.sh](https://github.com/naimiatef/Administration-du-systeme/blob/main/cpu.sh) : signale si l'utilisation du processeur dépasse le seuil <br>
5- [Disk-Space.sh](https://github.com/naimiatef/Administration-du-systeme/blob/main/disk-space.sh) : vérifie si l'espace disque dépasse la limite<br>
6- [CollectNetworkInfo.sh](https://github.com/naimiatef/Administration-du-systeme/blob/main/collectnetworkinfo.sh) : collecte des informations relatives au serveur<br>
7- [RemoteBackup.sh](https://github.com/naimiatef/Administration-du-systeme/blob/main/remotebackup.sh) : sauvegarde d'un fichier local sur un serveur distant<br>
8- [HardwareInfo.sh](https://github.com/naimiatef/Administration-du-systeme/blob/main/hardware_machine.sh) : affiche les informations matérielles pour les systèmes Linux<br>
9- [Get-Temperature.sh](https://github.com/naimiatef/Administration-du-systeme/blob/main/get-temperature.sh) : affiche la température du processeur<br>
-------------------------------------------------------------------------------
Un script Bash est un fichier texte contenant une série de commandes écrites pour être exécutées dans un interpréteur de commande Bash (Bourne Again Shell), qui est l'un des interpréteurs de commande les plus couramment utilisés sous Linux et autres systèmes UNIX.

Exemple simple de script Bash
Voici un exemple basique de script Bash :

bash
Copier le code
#!/bin/bash
# Ce script affiche un message de bienvenue et la date actuelle

echo "Bonjour, bienvenue dans le monde des scripts Bash !"
echo "Nous sommes le : $(date)"

# Afficher le répertoire courant
echo "Vous êtes dans le répertoire : $(pwd)"

# Lister les fichiers dans le répertoire courant
echo "Voici les fichiers et dossiers ici :"
ls
Explications
#!/bin/bash : Indique au système que le fichier doit être exécuté avec l'interpréteur Bash.
echo : Utilisé pour afficher du texte dans le terminal.
$(commande) : Permet d'exécuter une commande et d'insérer son résultat dans le script.
ls : Affiche le contenu du répertoire courant.
Comment exécuter un script Bash
Créez un fichier texte (par exemple, script.sh).
Ajoutez les commandes Bash dans le fichier.
Rendez le fichier exécutable avec la commande :
bash
Copier le code
chmod +x script.sh
Exécutez le script avec :
bash
Copier le code
./script.sh
Utilisations courantes
Automatisation des tâches système.
Surveillance des ressources.
Gestion des fichiers et des répertoires.
Déploiement et gestion des applications.
Un script Bash peut être aussi simple ou complexe que nécessaire, et il est souvent utilisé par les administrateurs système et les développeurs pour optimiser leurs workflows.
