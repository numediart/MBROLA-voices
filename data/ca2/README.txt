

CCCCCCCCCC         A          2222222
C                 A A        2       2
C                A   A                 2
C               A     A               2   
C              AAAAAAAAA             2     
C             A         A           2     
C            A           A        2     
C           A             A    2 2
CCCCCCCCCC  A             A  2222222222   

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 A brief description of the CA2 database
2.0 Distribution
3.0 Installation, and tests
4.0 Author

--------------------------------------------------------------
1.0 A brief description of CA2
--------------------------------------------------------------

CA2 release 03/10/22 is a Canadian-French diphone database provided in the context
of the MBROLA project see: http://tcts.fpms.ac.be/synthesis

It  provides  a French-Canadian male half-singing voice to be used with the MBROLA
program. The central pitch of the database is ##200Hz, and the nominal
sampling rate is 22050Hz. 

Input files use the SAMPA (SAM Phonetic Alphabet) notation  as
recommended by  the EEC-SAM Project. Here is a list of the French
phonemes it accounts for, with examples. 

(NB : the table below is encoded as ASCII ISO8859-1 (Latin-1);  use an ASCII
editor to see it correctly ) 

SAMPA	EXAMPLES
i	idiot, ami
e	ému, été
E	perdu, maison
a	alarme, patte
O	obstacle, corps
o	auditeur, beau
u	coupable, loup
y	punir, élu
2	creuser, deux
9	malheureux, peur
@	petite, fortement
e~	peinture, matin
a~	vantardise, temps
o~	rondeur, bon
9~	lundi, brun
j	piétiner, choyer
w	quoi, fouine
H	huile, nuage
p	patte, repas, cap
t	tête, net
k	carte, écaille, bec
b	bête, habile, robe
d	dire, rondeur, chaud
g	gauche, égal, bague
f	feu, affiche, chef
s	soeur, assez, passe
S	chanter, machine, poche
v	vent, inventer, rêve
z	zéro, raisonner, rose
Z	jardin, manger, piège
l	long, élire, bal
R	rond, charriot, sentir
m	madame, aimer, pomme
n	nous, punir, bonne
N     ping, pong
_	(silence marker)
$	inspiration sound
%	expiration sound

Limitations:
-----------
Notice that SAMPA 'h' (halte,hop) is not defined.

SAMPA 'J'(agneau, peigner, règne) should  be entered as two separate
phonemes : 'n' and 'j'. The two phonemes must be separated by a '_' (silence).

SAMPA '$' has to be followed by SAMPA '_' (silence). No other sequence is valid.

SAMPA '%' can follow vowels only.

For a sample file using inspirations and expirations, see 'apres_la_pluie.pho'

--------------------------------------------------------------
2.0 Distribution
--------------------------------------------------------------

This distribution of mbrola contains the following files :

   CA2       : the database itself
   Ca2.txt   : This file
   license.txt: must read before using the database
    
and a number of example .PHO files : 

hier.pho        Oldies
kundera.pho     Milan Kundera, Unbearable lightness of being
mbrola.pho      My voice is synthesized thanks to a new bla bla bla
apres_la_pluie.pho      After the rain


--------------------------------------------------------------
4.0 Author
--------------------------------------------------------------

This database was recorded by Silex creations inc. - Montreal, Canada.
For questions concerning  the database itself contact
lanctot@silexcreations.com

Contact mbrola@tcts.fpms.ac.be, for general information, questions on
the installation of software and databases.
