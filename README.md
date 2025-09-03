# p5-ascii-webcam
A simple real-time ASCII webcam using p5.js. Converts live video feed into ASCII art.

📷 p5-ascii-webcam

Une webcam ASCII en temps réel réalisée avec p5.js.
Le flux vidéo de la webcam est converti en art ASCII en mappant la luminosité des pixels sur des caractères typographiques.

⚙️ Installation
-Telecharger et extraire le fichier ZIP du projet 
-Ouvrir et installer sur Visual Studio code l'extension p5.vscode
-Ouvir le command palette (CTRL+SHIFT+P) et entrer "create p5.js project"
-Importer le fichier et excuter le code "sketch.js"


🛠️ Fonctionnement

-Capture la webcam avec createCapture(VIDEO)

-Réduit la taille de la vidéo pour de meilleures performances "(video.size(64, 48))"

-Calcule la valeur en niveaux de gris "(r + g + b) / 3" pour chaque pixel

-Associe la luminosité à un caractère de la chaîne "density"

-Affiche le rendu ASCII dans une "div"

📂 Structure du projet
p5-ascii-webcam/
│── index.html   # Fichier principal HTML
│── sketch.js    # Code p5.js 
│── README.md    # Documentation du projet



📜 Licence

Vous pouvez l’utiliser et le modifier librement pour vos propres expérimentations.