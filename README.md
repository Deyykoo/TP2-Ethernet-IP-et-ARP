# TP2-Ethernet-IP-et-AR
## I- Setup IP 
```	
1
commande = ipconfig /all  
pc 1 : adresse ip : 192.168.11.20  
pc 2 : adresse ip : 192.168.11.21  
adresse réseau : 192.168.11.0  
broadcast : 192.168.11.254  
ping : 192.168.11.20  

Envoi d’une requête 'Ping'  192.168.11.20 avec 32 octets de données :
Réponse de 192.168.11.20 : octets=32 temps=1134 ms TTL=128
Réponse de 192.168.11.20 : octets=32 temps<1ms TTL=128
Réponse de 192.168.11.20 : octets=32 temps<1ms TTL=128
Réponse de 192.168.11.20 : octets=32 temps=4 ms TTL=128

Statistiques Ping pour 192.168.11.20:
    Paquets : envoyés = 4, reçus = 4, perdus = 0 (perte 0%),
Durée approximative des boucles en millisecondes :
    Minimum = 0ms, Maximum = 1134ms, Moyenne = 284ms
```
II- ARP my bro
```
1- commande = arp -a ou arp -g  
adresse mac binome = d4-93-90-23-52-c9

>ipconfig /all  
Interface :  10.33.70.209 --- 0x10  
Adresse Internet     Adresse physique      Type
10.33.79.254          7c-5a-1c-d3-d8-76     dynamique
```
commande = arp -d  
