#                              ______  
#                             /      \ 
#    ______    _______       |  $$$$$$\
#   /      \  /       \       \$$__| $$
#  |  $$$$$$\|  $$$$$$$        |     $$
#  | $$    $$ \$$    \        __\$$$$$\
#  | $$$$$$$$ _\$$$$$$\      |  \__| $$
#   \$$     \|       $$       \$$    $$
#    \$$$$$$$ \$$$$$$$         \$$$$$$ 
#                                      
#                                      
#                                      



release 1

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 A brief description of the ES3 database
2.0 Distribution
3.0 Installation, and tests
4.0 Acknowledgments

--------------------------------------------------------------
1.0 A brief description of ES3
--------------------------------------------------------------
ES3 equalized release is a Spanish diphone database provided in
the context of the MBROLA project (see
http://tcts.fpms.ac.be/synthesis).

It provides a Spanish female voice to be used with the MBROLA program.

Input files use the SAMPA (SAM Phonetic Alphabet) notation as
recommended by the EEC-SAM Project, but with some minor changes,as 
indicated. The following is derived from SAMPA for Spanish (J.C.Wells,
UCL,London).

SAMPA	EXAMPLE		TRANSCRIPTION
p	padre		"paDre
b	vino		"bino
t	tomo		"tomo
d	donde		"donde
k	casa		"kasa
g	gata		"gata

tS	mucho		"mutSo
jj	hielo		"jjelo
w	huele		"wele	(NOT sampa definition)

f	f·cil		"faTil
T	cinco		"Tinko
s	sala		"sala
x	mujer		mu"xer

m	mismo		"mismo
n	nunca		"nunka
J	aÒo		"aJo

l	lejos		"lexos
L	caballo		ka"baLo	
r	puro		"puro
rr	torre		"torre

i	pico		"piko
e	pero		"pero
a	valle		"baLe
o	toro		"toro
u	duro		"duro

_		silence	

Limitations:
-----------
A matrix provided suffers from some limitations that we hope to
eliminate in future versions. In particular the diphthongs are
not adequately treated in the current version of the database, nor
are the /b/ /B/, /d/ /D/, /g/ /G/ pairs.
The following are the original Sampa definitions left out.
j		rei		rrej
		pie		pje
w		deuda		"dewDa
		muy		mwi
B		cabra		"kaBra		(= /b/)
D		nada		"naDa		(= /d/)
G		luego		"lweGo	(= /g/)

--------------------------------------------------------------
2.0 Distribution
--------------------------------------------------------------

This distribution of mbrola contains the following files : 

   es3      : the database itself
   es3.txt  : This file
   license.txt : must read before using the database
    
and a TEST directory containing .PHO files. 

Additional languages and voices, as well as other example command
files, are or will be available in the context of the MBROLA 
project. Please consult the MBROLA project homepage :
   http://tcts.fpms.ac.be/synthesis

Registered users will automatically be notified of the availability 
of new databases. To freely register, simply send an email to 
mbrola-interest-request@tcts.fpms.ac.be with the word 'subscribe'
in the message title.

--------------------------------------------------------------
3.0 Installation and Tests
--------------------------------------------------------------

If you have not copied the MBROLA software yet, please consult
the MBROLA project homepage and get it.

Copy es3.zip into the mbrola directory and unzip it : 

   unzip es3.zip (or pkunzip on PC/DOS)
   (don't forget to delete the .zip file when this is done)

Try in a terminal

  $ mbrola es3 TEST/estafuncionando.pho estafuncionando.wav

to create a sound file. In this example the audio file follows 
the RIFF Wav format. But depending on the extension test.au, test.aif, 
or test.raw you can obtain other file formats. Listen to it with your 
favorite sound editor, and try other command files (*.pho) to have 
a better idea of the quality of speech you can synthesize with the 
MBROLA technique.

On Unix systems you can pipe the audio ouput to the sound player as
on a HP : mbrola es3 test.pho - | splayer -srate 16000 -l16

Also refer to the readme.txt file provided with the mbrola 
software for using it.

--------------------------------------------------------------
4.0 Acknowledgements
--------------------------------------------------------------

We could like to thank Emilia Méndez Barrios for the use of his voice, 
and its work doing this MBROLA database.
And Vincent Pagel and Thierry Dutoit for their work in preparing the database.

--------------------------------------------------------------

Javi F Gorostiza (jgorosti@ing.uc3m.es)

e-mail: mbrola@tcts.fpms.ac.be, for general information, 
questions on the installation of software and databases.
