Module : python

Le script main.py permet de:

-lister les fichiers d'un conteneur Azure Blob Storage,
-envoyer un fichier dans un container Azure Blob Storage
-télécharger un fichier contenu dans un container Azure Blob Storage

Pour utiliser ce programme, vous devez avoir créé un compte Azure, et remplir un fichier config.ini contenant:

-Le chemin fichier pour telecharger l'objet blob (restoredir)
-le nom de votre compte Azure (account)
-le nom du contener de votre compte Azure (container)
-la clé du contener (key)

Pour lancer le programme:

-vous devez appeler la commande python main.py, suivi de l'argument de votre choix: "list", "upload" + le chemin du fichier
à envoyer dans le container, "download" + le nom du fichier à télécharger sur le container.

Les librairies utilisées dans ce script font par défaut partie de python. Seulement les librairies liées à Azure ont besoin d'être installées. 
Vous pouvez le faire:

-dans le terminal avec la commande pip install azure-storage-blob
-si vous travaillez en environnement virtuel, vous pouvez utiliser le fichier requirements.txt
