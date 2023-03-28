# HashPursuit: A Password Cracking Adventure with CUPP and Hashcat

This script automates the process of generating a dictionary using CUPP, identifying a given hash using hash-identifier, and cracking the hash using hashcat. It is open-source and can be used and modified freely.

## English

### Description

The script performs the following steps:

1. Asks the user if they want to install CUPP and/or hashcat (if not already installed).
2. Asks the user for the path to their CUPP configuration file.
3. Runs CUPP to generate a dictionary based on the provided configuration file.
4. Asks the user for the hash they want to crack.
5. Identifies the hash using hash-identifier.
6. Searches for the hash type code in the hashcat manual.
7. If the hash type code cannot be found, asks the user to search for it on the hashcat website and enter it manually.
8. Attempts to crack the hash using hashcat and the generated dictionary.
9. Displays the result if the hash is cracked, or an error message if the dictionary was insufficient.

### Usage

1. Clone the repository or copy the script to your local machine.
2. Make sure you have Python installed.
3. Run the script: `python script.py`
4. Follow the prompts to install CUPP and/or hashcat, provide the necessary paths and input, and attempt to crack the hash.

## Français

### Description

Le script effectue les étapes suivantes :

1. Demande à l'utilisateur s'il souhaite installer CUPP et/ou hashcat (s'ils ne sont pas déjà installés).
2. Demande à l'utilisateur le chemin vers leur fichier de configuration CUPP.
3. Exécute CUPP pour générer un dictionnaire basé sur le fichier de configuration fourni.
4. Demande à l'utilisateur le hachage qu'il souhaite casser.
5. Identifie le hachage en utilisant hash-identifier.
6. Recherche le code de type de hachage dans le manuel de hashcat.
7. Si le code de type de hachage ne peut pas être trouvé, demande à l'utilisateur de le rechercher sur le site Web de hashcat et de le saisir manuellement.
8. Tente de casser le hachage en utilisant hashcat et le dictionnaire généré.
9. Affiche le résultat si le hachage est cassé, ou un message d'erreur si le dictionnaire était insuffisant.

### Utilisation

1. Clonez le dépôt ou copiez le script sur votre machine locale.
2. Assurez-vous d'avoir Python installé.
3. Exécutez le script: `python script.py`
4. Suivez les invites pour installer CUPP et/ou hashcat, fournir les chemins et entrées nécessaires, et tenter de casser le hachage.
