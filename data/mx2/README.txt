MX2
release 0.1 - May 05
--------------------------------------------------------------
MX2 - A Mexican Spanish male voice for the MBROLA synthesizer

Created by : The voice was created by Humberto Pérez Espinosa
at Instituto Nacional de Astrofísica Óptica y Electrónica,
México

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 Description of the MX2 diphone database
2.0 Installation and tests

--------------------------------------------------------------
1.0 Description of the MX2 diphone database
--------------------------------------------------------------

MX2 is a diphone database for Mexican Spanish, consisting of 613
diphones, male voice.

The following  phoneme  symbols are  assumed in  our diphone  sets.

SYMBOL  PRONOUNCED LIKE IN
Phonetic Alphabet
SAMPA   EXAMPLE         TRANSCRIPTION
p       padre           "padre
b       vino            "bino
t       tomo            "tomo
d       donde           "donde
k       casa            "kasa
g       gata            "gata

tS      mucho           "mutSo
w       huele           "wele   (NOT sampa definition)

f       fácil           "fasil
s       sala            "sala
j       mujer           "mujer

m       mismo           "mismo
n       nunca           "nunka
ny       año             "anyo

l       lejos           "lejos
r       puro            "puro
rr      torre           "torre

i       pico            "piko
e       pero            "pero
a       valle           "badZe
o       toro            "toro
u       duro            "duro
x       extraño         "extranyo

dZ      john            "dZon
N       tang            "taN

_               silence



--------------------------------------------------------------
2.0 Installation and Tests
--------------------------------------------------------------

If  you  have  not copied   the MBROLA software   yet,  please consult
the MBROLA project homepage and get it.

Copy mx2.zip into the mbrola directory and unzip it : 

   unzip mx2.zip (or pkunzip on PC/DOS)

Try 

   mbrola mx2 TEST/example1.pho test.wav

to create a sound file for a short excerpt  of Alice in Wonderland. In
this   example the  audio  file   follows  the RIFF   Wave format. But
depending  on the extension test.au,  test.aif, or test.raw other file
formats can be obtained. Listen to it with your favorite sound editor,
and try the other command files  (*.pho) to have a  better idea of the
quality of speech that  can  be synthesized with   MBROLA and the  MX2
database.

On Unix  systems you can pipe  the audio ouput  to the sound player as
on a HP : mbrola mx2 phone.pho - | splayer -srate 16000 -l16

Also refer  to the readme.txt file provided  with  the mbrola software
for using it. 

        
--------------------------------------------------------------
Interesting link: http://ccc.inaoep.mx/

Contact:

Instituto Nacional de Astrofísica Óptica y Electrónica 
P.O. Box 72000
Tonantzintla
Puebla
México

email: humbertop@ccc.inaoep.mx
