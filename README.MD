Vous trouverez ici :

-	le dossier "schema-libretto-RNG" accueille un schéma à associer à vos dossiers
-	le fichier "Libretto-Python.ipynb", en jupyter notebook, où tu trouveras le code recherché. Il ouvre un fichier .txt situé dans un dossier "data" voisin et renvoie un fichier .txt en TEI. Cependant, des erreurs nécessitent de continuer de lire et corriger la TEI sortie.
-	"Libretto-Wagner-Paul" est mon libretto encodé et TEI valide. Il n'est cependant pas passé par le filtre de la XSL...
-	"ODD-libretto" est l'ODD associé à mon encodage.
-	"Wagner.txt" est la source non encodée et non traitée, servant de modèle pour préparer le passage par Python.
-	"WagnerTEI.txt" est la sortie brut après Python, TEI valide mais contenant quelques erreurs.
-	"XSL-Wagner.xsl" est la XSL pouvant servir comme modèle d'unification commune de la TEI.


Ce travail sert de travail préparatoire au travail de groupe.

Le Python peut/doit être enrichi par le travail de chacun, pour permettre d'encoder automatiquement chaque chose. N'hésitez pas à faire des pull requests.
