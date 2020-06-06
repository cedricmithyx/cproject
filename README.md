# cproject
Sujet 4 Chiffrement des messages
Binôme : JEANJEAN Cedric, LECRIVAIN Maxime S2B.

Le fichier alphanumerique.c possède 2 fonctions : 
int accentcar(wchar_t *mot)
		Possède en entrée un texte en wchar_t* qui est le texte précédemment saisie par l'utilisateur lors du lancement du programme.
    Il est attendue qu'il retourne -1 si un caractére spécial est trouver soit /<>#({[]})*-+.@|&~"  
    Si aucun caractére spécial n'est trouver alors il appelle la procedure caractcar et retourne 1.
    
 void caractcar(wchar_t *mot)
		Possède en entrée un texte en wchar_t* qui est le texte précédemment saisie par l'utilisateur lors du lancement du programme.
    Il est attendue qu'il modifie le mot sans accent


Le fichier cesar.c possède 2 fonctions:
void cesar_crypt(int decallage, wchar_t *texte)
   Possède en entrée un texte en wchar_t* qui est le texte précédemment saisie par l'utilisateur lors du lancement du programme et    sans accent. Il possède aussi la clé pour le décallage voulu.
   Il est attendue qu'il modifie le texte grâce au décallage pour le crypter.
   
void cesar_decrypt(int decallage, wchar_t *texte)
   Possède en entrée un texte en wchar_t* qui est le texte précédemment saisie par l'utilisateur lors du lancement du programme et    sans accent. Il possède aussi la clé pour le décallage voulu.
   Il est attendue qu'il modifie le texte grâce au décallage pour le décrypter.

Le fichier vigenere.c possède 3 fonctions:
int rang(char lettre);
   Possède en entrée une lettre en minuscule et retourne sa position dans l'alphabet.
   
int rangMAJ(char lettre);
   Possède en entrée une lettre en majuscule et retourne sa position dans l'alphabet.
   
void vigenere(wchar_t *phrase, wchar_t *cle, wchar_t *resultat, int crypte)
    Possède en entrée la phrase a crypter ou decrypter, la clé et une valeur "crypte" pour indiquer si il faut crypter ou
    décrypter le message.
    En sortie le resultat du cryptage ou decryptage

 
