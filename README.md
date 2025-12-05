# Miaou-challenge-HackTheBox
Titre de la vulnérabilité : Authentification Telnet avec identifiants faibles

Etape 1 : Presentation de la machine

![image alt](https://github.com/cheikhsamake63/Miaou-challenge-HackTheBox/blob/78b2f039a1a8579139e73cce9dba01904d8ece7d/Captures%20d%E2%80%99%C3%A9cran/1.png)


Etape 2 : Ping
Commande exécutée : ping 10.129.1.17
Résultat : la machine répond correctement (64 bytes reçus, temps ~117 ms, 0% packet loss)

![image alt](https://github.com/cheikhsamake63/Miaou-challenge-HackTheBox/blob/main/Captures%20d%E2%80%99%C3%A9cran/2.png)

Etape 3 : Scan nmap

Commande : nmap -sC -sV 10.129.1.17
Résultats du scan :
Un seul port ouvert : 23/tcp open telnet
Service : Linux telnetd
Aucune autre information (pas de version précise)

![image alt](https://github.com/cheikhsamake63/Miaou-challenge-HackTheBox/blob/main/Captures%20d%E2%80%99%C3%A9cran/3.png?raw=true)

Etape 4 : 

Commande tapée (entourée en rouge) : telnet 10.129.1.17
La connexion Telnet est en cours d’établissement (rien n’apparaît encore à l’écran)
![image alt](https://github.com/cheikhsamake63/Miaou-challenge-HackTheBox/blob/main/Captures%20d%E2%80%99%C3%A9cran/4.png?raw=true)

Etape 5 : Connexion Telnet réussie

![image alt](https://github.com/cheikhsamake63/Miaou-challenge-HackTheBox/blob/main/Captures%20d%E2%80%99%C3%A9cran/5.png?raw=true)

Etape 6 : Nous avons le flag

![image alt](https://github.com/cheikhsamake63/Miaou-challenge-HackTheBox/blob/main/Captures%20d%E2%80%99%C3%A9cran/6.png?raw=true)
