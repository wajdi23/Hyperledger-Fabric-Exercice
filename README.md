# Design a the network 

Dans cet exercice nous allons nous reférer a notre premier exemple e-commerce network 

On va supposer qu’on est dans un réseau d’entreprise.  Par Example dans notre cas ici du E-commerce international  
On a différents organismes qui traitent les uns avec les autres avec chacun son système d’information  
Nos participant sont :
Buyer ou Acheteur  
Seller ou vendeur  
FinanceCo ou Banque (par exemple PayPal) 
Shipper ou service de livraison (par exemple rapide post) 
Et on a différentes transactions entre eux. On va dire que dans notre cas les cas se passe comme suite :  
1. L’acheteur place une commande (sac, chaussure, jeux vidéo) qui est reçu par le vendeur  
2. Et il paye l’organisme de financement  
3. Le vendeur qui a reçu la commande de l’acheteur va contacter Paypal pour le payement  
4. Et Paypal va payer le vendeur si tout est en ordre  
5. Ensuite une fois il est payé, notre Vendeur va contacter son service de livraison préférée (Rapid Post) et lui demander de livrer le produis.
6. Le service de livraison livre le produis à l’acheteur  
Proposer une conception du réseau en vous référant à cette description et les étapes suivante  
Générez les crédenciales pour vos composantes du réseau 
Générez le genesis block  
Générez la transaction de Channel  
Composez votre réseau à l’aide de docker-compose  
Forkez le projet et faites les modifications nécessaires. Une fois le réseau implémenté, démarrez-le et envoyez un Screenshot des containers  
pour voir les container vous devez tapez la commande   

