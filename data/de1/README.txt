DDD	  EEEEEEE	1
D  D	  E	      1 1
D   D	  E	    1	1
D    D	  E		1
D     D	  EEEE		1
D    D	  E		1
D   D	  E		1
D  D	  E		1
DDD	  EEEEEEE    1111111 release 2.050

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 A brief description of the DE1 database
2.0 Distribution
3.0 Installation, and tests
4.0 Acknowledgments

--------------------------------------------------------------
1.0 A brief description of DE1
--------------------------------------------------------------
DE1 1.00 release is a German diphone database provided in the
context of the MBROLA project
(see https://github.com/numediart/MBROLA/).

It provides a German female voice to be used with the MBROLA program.

Input files use the SAMPA (SAM Phonetic Alphabet) notation as
recommended by the EEC-SAM Project. Here is a list of the German
speech sounds it accounts for, with examples.

(NB : the table below is encoded as ASCII ISO8859-1; use an ASCII 
editor to see it correctly )

--------------------------------------------------------------
SAMPA	EXAMPLES (orthographic)

_	(silence, no signal)

p	Pier, aB
b	Bier, KraBBe
t	Tier, GraD
d	Dir, eDel
k	Kasse, taG
g	Gasse, eGal

f	Vogel, schlaF
v	Wasser, eVentuell
s	aSt, haSS
z	Sieb, beSen
S	Spät, aSCHe
Z	Genie, DSCHungel
x	naCH, doCH
C	diCH, honiG
h	Hut, aHorn
                        
pf	PFerd, toPF
ts	Zwei, plaTZ
tS	kuTSCHe, Cello

m	Mut, haMMer
n	Nase, kaNNe
N	eNG, baNGe
                        
l	Liebe, haLLe
R	Riese, kRaut 
6	opER, deR
j	Jetzt, Jagd
                        
aI	EIns, kAIser
OY	ÄUßerung, nEU 
aU	AUf, schAU
 
@	sehEn, bEsagt
i:	Igel, bIEten
I	In, bItten
y:	Übung, hÜten
Y	Ypsilon, hÜtten
e:	bEten, schnEE
E	bEtten, gÄste
E:	Äsen, geblÄse
2:	Öfen, mÖgen
9	Öffnen, kÖnnen
u:	bUHlen, gUt
U	lUstig, bUtter
o:	Ofen, kOHl
O	Offen, tOpf
a:	wAr, wAHr
a	An, kAnn

Only rudimentary implemented:

E^ (= E~:)	bulletIN
a^ (= a~:)	pendANT
9^ (= 9~:)	parfUM
o^ (= o~:) 	feuilletON
E~		IMpair
a~		pENdant
o~		nONchalant

at	breath noise (only in conjunction with silence: at-_, _-at)
--------------------------------------------------------------

Please note:

Short closed vowels (e.g. [i, e, u, o]) should be synthesized using
the corresponding long vowels (e.g. [i:, e:, u:, o:]) with approbiate
duration values.

For best synthesis results it is recommended to avoid pauses [_] 
between words, however, if a vowel should be produced with a 
glottal stop [?], a pause has to occur before the vowel.


Limitations:
-----------

Notice that not all diphones are possible in German.
Impossible ones will trigger an error message (e.g. h-N
or 9-9) 

--------------------------------------------------------------
2.0 Distribution
--------------------------------------------------------------

This distribution of mbrola contains the following files : 

   de1      : the database itself
   de1.txt  : This file
    
and .PHO examples in a TEST directory

Additional languages and voices, as well as other example command
files, are or will be available in the context of the MBROLA 
project. Please consult the MBROLA project homepage :
   https://github.com/numediart/MBROLA/
Registered users will automatically be notified of the availability 
of new databases. To freely register, simply send an email to 
mbrola-interest-request@tcts.fpms.ac.be with the word 'subscribe'
in the message title.

--------------------------------------------------------------
3.0 Installation and Tests
--------------------------------------------------------------

If you have not copied the MBROLA software yet, please consult
the MBROLA project homepage and get it.

Copy de1.zip into the mbrola directory and unzip it : 

   unzip de1.zip (or pkunzip on PC/DOS)
   (don't forget to delete the .zip file when this is done)

Try 

   mbrola de1/de1 TEST/wetter2.pho wetter2.wav

to create a sound file. In this example the audio file follows 
the RIFF Wav format. But depending on the extension wetter2.au, wetter2.aif, 
or wetter2.raw you can obtain other file formats. Listen to it with your 
favorite sound editor, and try other command files (*.pho) to have 
a better idea of the quality of speech you can synthesize with the 
MBROLA technique.

On Unix systems you can pipe the audio output to the sound player as
on a HP : mbrola de1 wetter2.pho - | splayer -srate 16000 -l16

Also refer to the readme.txt file provided with the mbrola 
software for using it.

--------------------------------------------------------------
4.0 Acknowledgments
--------------------------------------------------------------
I would like to thank Vincent Pagel for his help in building
an efficient version of this database.

--------------------------------------------------------------

Dr Fred Englert

Johann Wolfgang Goethe-Universitaet
Institut für Phonetik
PF 11 19 32
D-60054 Frankfurt am Main  

Tel.: +49.69.79823744
Fax.: +49.69.79823774

e-mail: englert@ieee.org, for
questions concerning the database de1.

e-mail: mbrola@tcts.fpms.ac.be, for general information, 
questions on the installation of software and databases.



