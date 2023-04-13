# Pricer-Option-Americaine

Ce projet a été fait en collaboration avec Julien Bensoussan, en 3ème année de l'ENSIMAG, à la suite d'un cours présenté par Mr Jerome Lelong

Ce projet propose une implémentation de l'algorithme de Longstaff-Schwartz permettant de pricer différents types d'option américaines. 

Ce projet nécessite la librairie PNL accéssible gratuitement sur internet. 

Pour compiler ce projet, un CMakeList.txt est proposé. 

Entrer les commandes : 

- mkdir build
- cd build
- cmake -DCMAKE_PREFIX_PATH=/Path/to/pnl/build/ ..
- make 

Différentes options peuvent être pricées à partir des fichiers du répertoire dat.

Entrer depuis le répertoire build : 
- ./mc-exemple ../dat/fichier.txt


