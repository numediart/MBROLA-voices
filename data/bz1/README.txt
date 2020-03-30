BBBBBBBB     ZZZZZZZZZZ      111
B       B    ZZ      ZZ     1111
B        B   Z      ZZ     11 11
B        B         ZZ         11
B       B         ZZ          11
BBBBBBBB         ZZ           11
B       B       ZZ            11
B        B     ZZ             11
B        B    ZZ      Z       11
B       B    ZZ      ZZ       11
BBBBBBBB     ZZZZZZZZZZ     111111 release 0.99

--------------------------------------------------------------
          Diaz titouroù difonemoù evit ar Brezhoneg
--------------------------------------------------------------

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 A brief description of the BZ1 database
2.0 Files
3.0 Installation, and tests
4.0 Authors

Appendice: BZ1 FAQ

--------------------------------------------------------------
1.0 A brief description of BZ1
--------------------------------------------------------------

BZ1 0.98 release is a Breton diphone database provided for
MBROLA by the KGB (Kenaoz ar Gomz e Brezhoneg) project (part
of IRISA research institute located at Lannuon Computing Labs) 

It provides a Breton female voice (great artist Annie Ebrel's)
whose central pitch is about 180-200Hz.

Phoneme coding is close to SAMPA conventions, '~' marks nazalisation
and ':' long vowels.

Long and short vowels are considered different (and the long version
is obtained from an accentuated segment), lot of diphtongs are considered
so the database is quite large. Size should decrease in the future
as undistinguishable "phonemes" will be identified.

Some diphtongs have a quite bad recording, and sound as two
consecutive vowels.

Then, unfortunately some xx to silence transitions are missing,
so phrase endings can sound bad.

For more informations about SAMPA, and ascii-coding of IPA charset
look at : http://www.phon.ucl.ac.uk/home/sampa/x-sampa.htm

SAMPA	EXAMPLES

A	dall
A:	bazh
A~	lann
A~:	man
e	bet
e:	ker
e~	bensel
e~:	
E	lemm
E:	bered
E~	peñse
E:~	deñved
2	meurzh
2:	
2~
2~:	
9	feulz
9:	meuleudi
9~:	
i	hili
i:	hir
i~	riñsoñ
i~:	fiñv, hiñvis
j	yar
o	pok
o:	rod
o~	plom
o~:	soñj
O	koll
O:	lovr
u	toull
u:	tour
y	pulluc'h
y:	mul
y~	[loc] puñs
y~:	puñs
w	war
H	ui

[It seems that y~ (i.e. ÿ), long or normal, is missing, We have
recorded it, wait for 0.99 !]

Diphtongs :

Aj		
Aw
A~w	
ew	
e~w
Ej	
Ew
iw
oj
ow
2j
2~j
9j
9~j

b	berr
d	du
f	fust
g	gar, genoù
g'	     [ missing in 0.98 ]
h	had, ar c'har
J	poaniañ, pign
k	kalon
k'	     [ missing in 0.98 ]
l	lenn
L	dilhad
m	mamm
n	nann
Nk	onkl [ missing in 0.98 ]
p	pri
r	ruz
s	sort
S	choual
t	ti
v	van
x	dic'houennañ
z	jeu
Z	bezañ


Not all diphones are present (of course !), some do not occur
in breton (nor any language), others can be rendered easily by
substitution of a close phoneme. Look at labels.txt to know
which transitions are defined or not.


--------------------------------------------------------------
2.0 Files
--------------------------------------------------------------

bz1.txt		: this file
bz1		: the (huge) diphone database
labels.txt	: the complete diphone list
mbrola.pho	: Example : "Va mouezh a zo adsavet gant ar benveg
		      nevez anvet MBROLA"
aman.pho	: another example : "Amañ emañ ma zad ha ma mamm"
galleg.pho	: french sentence, with breton accent.
cafe.pho	: french sentence, with breton accent and syntax.
doctor.pho	: french sentence, with typical breton syntax.

--------------------------------------------------------------
3.0 Installation and Tests
--------------------------------------------------------------

[part mostly cut&paste from MBROLA help files]

If you have not copied the MBROLA software yet, please consult
the MBROLA project homepage and get it at
https://github.com/numediart/MBROLA/

Copy bz1.zip into the mbrola directory and unzip it : 

   unzip bz12.zip (or pkunzip on PC/DOS)
   (don't forget to delete the .zip file when this is done)

Try 

   mbrola bz1 TEST/mbrola.pho mbrola.wav

to create a sound file for a phrase. In this example the
audio file follows the RIFF Wav format. But depending on the 
extension bonjour.au, bonjour.aif, or bonjour.raw you can obtain
other file formats. Listen to it with your favorite sound editor,
and try the other command files (*.pho) to have a better idea of
the quality of speech you can synthesize with the MBROLA technique.

On Unix systems you can pipe the audio ouput to the sound player as
on a HP : mbrola bz1 TEST/mbrola.pho - | splayer -srate 16000 -l16,
on Linux : mbrola bz1 TEST/mbrola.pho - | vplay -s 16000 -b 16
(vplay is part of snd-kit package).


Also refer to the readme.txt file provided with the mbrola 
software for using it.

To improve quality, use -l, -t and -f controls (and initialization
files), such as : -l 13000 -t 0.8

--------------------------------------------------------------
4.0 Author
--------------------------------------------------------------

This database was recorded by Annie Ebrel, a well known breton
traditional singer, in TooT studio at St-Brieuc.
This work is only a part of the whole KGB project, whose goal
is to provide high quality Breton speech synthesis for language
acquisition and teaching. Main partners in the team are :
	- Lannion Computing Labs (IRISA labs) KGB team (mercier@enssat.fr)
	            http://www.enssat.fr, http://www.irisa.fr
	- TES (Ti-Embann ar Skolioù Brezhonek) (tes@tes.c-si.fr)
		    http://www.ac-rennes.fr/crdp/tes/

For complaints, remarks, etc. about this specific work (the phoneme
database) write to Jean-Pierre.Messager@enssat.fr or Herve.Gourmelon@enssat.fr
Adress flames to /dev/null (or nul on dos/windoz sytems)

-------------------------------------------------------------
Appendice: BZ1 FAQ
-------------------------------------------------------------

Q: Are you working on a complete Text-To-Speech system for breton ?
A: Yes, we are.

Q: Is there any application using this database yet ?
A: There is: a vocal dictionnary (from F. Favereau "Geriadur ar Brezhoneg
a-vremañ") on CD-ROM for Windoze'95 will be released soon (editors TES for
schools and Skol Vreizh for individual users). A web version is planed too.

Q: Bz1 and "dialects"...
A: Our reference is center Brittany, Annie Ebrel's native place, and 
phonologic scheme from Goelo (F. Favereau's work). It's not difficult
to adapt for K.L.T. "dialects". Breton from Bro-Gwened will need more
work, probably recording another voice and (for TTS) building a
specific accentuation scheme.



