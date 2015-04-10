YM14 is a polymorphic encryption protocol.

The message is encrypted so polymorphic which means that for the same clear message
 the encrypted message can take different form. In the case of YM14 protocol there is an infinity of
 form for the encrypted message. Which gives it a significant resistance to cryptanalysis.

USE

You can write the message to encrypt the file "messageEnClair.ym14" or,
If this file is not in the working directory of the show you will be asked to enter a message.

To send an encrypted message, you must have the YM14Emission file with performing rights,
allow playback on a file containing the message to be transmitted (eg messageEnClair.ym14)
and allow writing to a file (for example: messageCrypte.ym14) which will contain the encrypted message to transmit.
You should also leave a connection on the file "http://ym001.github.io/YM14/annuaire.ym14" or place the file in the working folder (if you work without connection).
A terminal in order to encrypt the message will be: $ ./YM14Emission messageEnClair.ym14 messageCrypte.ym14

Now you need to convey the message (file: messageCrypte.ym14). By your convenience channel caller </ p>

To decrypt a message, you must have the YM14Reception messageCrypte.ym14 file and the file in the same directory.
You should also leave a connection on the file "http://ym001.github.io/YM14/annuaire.ym14" or place the file in the working folder (if you work without connection).
In a terminal command to decrypt a message will be: $ ./YM14Reception messageCrypte.ym14

The characters for the writing of the message are:
"ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789, -.? ABCDEFGHIJKLMNOPQRSTUVWXYZéèà"

For this test version there are only three users bob, alice and anonymous.

The pass sentences of these users are
for alice "jesuisuneblonde"
for bob "jesuisungeek"
for anonymous ""

This protocol is back everything back. The pass phrases are there to prevent dictionary attacks (which are not limited in size).
The directory is a reference authority for verification of transmitter and receiver identities.
The book by checking the identities blocks any attempt to attack the man in the middle type.

The files are compiled for 64-bit architecture linux ubuntu kind / Debian.

Pour nos amis les frenchys...

YM14 est un protocole de cryptage polymorphe.

Le message est crypté de façon polymorphique ce qui signifie que pour le même message clair
 le message crypté peut prendre différente forme. Dans le cas du protocole YM14 il y a une infinité de
 forme pour le  message crypté. Ce qui lui confère une résistance importante face à la cryptanalyse.

UTILISATION

Vous pouvez écrire le message à crypter dans le fichier "messageEnClair.ym14" ou, 
si ce fichier n'est pas dans le répertoire de travail de l'émission il vous sera demandé de saisir un message.

Pour émettre un message crypté, vous devez avoir le fichier YM14Emission avec les droits d'execution, 
permettre la lecture sur un fichier contenant le message à transmettre (par exemple : messageEnClair.ym14) 
et permettre l'écriture sur un fichier (par exemple :messageCrypte.ym14) qui contiendra le message crypté à transmettre.
Vous devez aussi laisser une connexion sur le fichier "http://ym001.github.io/YM14/annuaire.ym14" ou déposer ce fichier dans le dossier de travail(si vous travaillez sans connexion).
Dans un terminal la commande pour crypter un message sera : $ ./YM14Emission messageEnClair.ym14 messageCrypte.ym14

Il vous faut maintenant transmettre le message(fichier:messageCrypte.ym14) par un canal de votre convenance à votre interlocuteur.</p>

Pour décrypter un message, vous devez avoir le fichier YM14Reception et le fichier messageCrypte.ym14 dans un même répertoire.
Vous devez aussi laisser une connexion sur le fichier "http://ym001.github.io/YM14/annuaire.ym14" ou déposer ce fichier dans le dossier de travail(si vous travaillez sans connexion).
Dans un terminal la commande pour décrypter un message sera : $ ./YM14Reception  messageCrypte.ym14

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

