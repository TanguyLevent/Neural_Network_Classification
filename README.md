# Neural_Network_Classification

Il s'agit d'un exemple simple et pédagogique d'une application non réaliste de Neural Network. Il s'agit de reconnaître certaines configurations d'une image réduite à la composition de 4 carrés noirs ou blancs. Pendant la phase d'apprentissage, on présente au réseau les configurations que l'on souhaite reconnaôtre. Puis, pendant la phase de reconnaissance on présente des configurations arbitraires afin de vérifier que le réseau reconnaît bien celles qu'il a apprises. L'image contient 4 pixels soit 16 configurations possibles de remplissage en noir ou blanc afin de les catégorier. En sortie on choisit arbitrairement d'avoir un tableau de deux valeurs permettant ainsi de pouvoir représenter 4 catégories facilement : 00 si aucun ou total pixels noirs, 01 pour 1 pixel noir, 10 pour 2 pixels noirs, 11 pour celles ayant trois pixels noirs.

Notre réseau sera composé de 4 neurones d'entrée, de 4 neurones cachés et 2 neurones de sortie.


