# Challenge-sys

FTP Authentification:
Demarrez le challenge, ensuite ouvrir le fichier telecharger avec wireshark, puis, selectionnez un paquet TCP.
Ensuite, faite un clic droit et suivre le flux TCP. A la fin on peut voir le mot de passe 
et il suffit de l'envoyer sur le site.

TELNET-authentification:
Meme methode c'est à dire ouvrir le fichier telechargé avec wireshark, ensuite selectionnez un paquet TELNET et suivre son flux TCP pour pouvoir 
obtenir le mot de passe et le tester sur le site

ETHERNET-Trame:
Apres avoir telechargé le fichier, on obtient un code hexadecimal. D'abord, il faut decoder le code avec un site qui en est capable.
Puis, on obtient un code. Encore une fois le decoder avec un autre site qui a été concu pour cela. Et enfin, on obtient un mot de passe 
quand on envoie sur le site pour le tester

AUTHENTIFICATION-Twitter:
Demarrez le challenge en ouvrant le fichier telechargé avec wireshark, faite un clic droit sur le seul paquet qu'il y a dedans et suivre le flux HTTP.
Ensuite, on obtient un code qu'il faut decoder avec un site capable de decoder des codes. ET on obtient le mot de passe à la fin.

BLUETOOTH-Fichier inconnu:
Demarrez le challenge afin d'obtenir le fichier qu'il faut ouvrir avec wireshark. Apres, il faut aller vers le menu wireless.
Puis, cliquer sur Equipemments Bluetooth pour obtenir l'adresse MAC el le nom du telephone. 
Ensuite, comme le sujet l'indique, il fautfaire le hash SHA1 de la concaténation de l’adresse MAC (en majuscules) et du nom du téléphone,
Par exemple, AB:CD:EF:12:34:56monTelephone et l'envoyer sur le site https://www.sha1.fr/. 
Enfin, on obtient le mot de passe qu'on doit tester sur le site du challenge.
