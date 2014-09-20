YM14 est un protocole de cryptage polymorphe.

Le message est cryté de façon polymorphique ce qui signifie que pour le même message clair
 le message crypté peut prendre différente forme. Dans le cas du protocole YM14 il y a une infinité de
 forme pour le  message crypté. Ce qui lui confère une résistance importante face à la cryptanalyse.

UTILISATION

Vous pouvez écrire le message à crypter dans le fichier "message.ym14" ou, 
si ce fichier n'est pas dans le répertoire de travail de l'émission il vous sera demandé de saisir un message.

Pour émettre un méssage crypté, vous devez avoir au moins les fichiers YM14Emission et le fichier annuaire.ym14 dans un même répertoire
et permettre l'écriture sur le fichier messageCrypte.ym14.

Pour décrypter un message, vous devez avoir au moins les fichiers YM14Reception,le fichier messageCrypte.ym14 et
 le fichier annuaire.ym14 dans un même répertoire.

Les caractères autorisés pour l'écriture du message sont:
" abcdefghijklmnopqrstuvwxyz0123456789.,?-ABCDEFGHIJKLMNOPQRSTUVWXYZéèà"

Pour cette version de test il y a uniquement trois utilisateurs bob, alice et anonymous.

Les pass phrases de ces trois utilisateurs sont
	pour alice     "jesuisuneblonde"
	pour bob       "jesuisungeek"
	pour anonymous ""

Ce protocole est en back tout back. Les pass phrases sont là pour éviter tout attaque par dictionnaire (elle ne sont pas limitées en taille).
L'annuaire est une autorité de référence permettant la vérification des identités émettrice et réceptrice.
L'annuaire en vérifiant les identités bloque toute tentative d'attaque du type man in the middle.

Les fichiers sont compilés pour une architecture linux 64 bits type ubuntu/débian.
