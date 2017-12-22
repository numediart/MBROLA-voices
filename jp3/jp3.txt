   ########       ##########      ######
      ##          ##        ##   #      #
      ##          ##        ##          #
      ##          ##########          ##
      ##          ##                  ## 
  ##  ##          ##                    #
   ####           ##             #      # 
    ##            ##              ######  
--------------------------------------------------------------
JP3 - A Japanese male voice for the MBROLA synthesizer

Created by :  Yoram Meron @ The University of Tokyo

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 Description of the JP3 diphone database
2.0 Installation and tests


--------------------------------------------------------------
1.0 Description of the JP3 diphone database
--------------------------------------------------------------

JP3 is a female diphone database for Japanese (Tokyo accent), 
consisting of 371 diphones. This database was constructed in a similar way to JP1.
In fact it was made before JP1, but was not released because it was felt its quality
is not as good.

The following  phoneme  symbols are  assumed in  our diphone  set. 
The symbols do not exactly follow any one phonetic standard for Japanese
transcription, but most symbols are fairly standard. Below there is a
description only of differences to the "standard" roma-ji transcription. 
(Note - the set is the same as that for JP1, except for 'G' which does not exist for jp3).

SYMBOL  COMMENTS:
=================

_       silence

Vowels: 
a
i
u
e 
o

Consonants:
b          
t          as in ta, te, to (chi, tsu are separately represented)
d          as in da, de, do (dji, dzu are separately represented)
k          
g          
s          
S          sh sound
m          
n          na, ni, nu, ne, no
w          
j          ya, yu, yo, and also used for creating kya, kyu ...
rr         ra, ri, ... 
tS         ch sound (transcribed as ti or tyi)
dZ         'j' sound (as in 'jikan' (time))  
h          
p           
ts         as in tsu  
f          f sound, for foreign words
v          v sound, for foreign words
N          geminated n sound ("shiNjuku")
z          

Geminated consonants - the 'Q' represents gemination ("sokuon")
Qt          
Qp          
Qk          
QS          
Qs          
Qts          
QtS          
Qd          (for foreign words)


Limitations: 
----------- 
The diphone matrix is not full - 'rare diphones' were not
recorded.  In particular diphthongs are not included in the database,
and all the CyV syllables (kya, myo, gyu...) are considered to be made
of C+j+V.



--------------------------------------------------------------
2.0 Installation and Tests
--------------------------------------------------------------

If  you  have  not copied   the MBROLA software   yet,  please consult
the MBROLA project homepage and get it.

Copy jp3.zip into the mbrola directory and unzip it : 

   unzip jp3.zip (or pkunzip on PC/DOS)

Try 

   mbrola jp3/jp3 jp3/TEST/tst.pho test.wav

to create a sound file. In
this   example the  audio  file   follows  the RIFF   Wave format. But
depending  on the extension test.au,  test.aif, or test.raw other file
formats can be obtained. Listen to it with your favorite sound editor,
and try the other command files  (*.pho) to have a  better idea of the
quality of speech that  can  be synthesized with   MBROLA and the  US1
database.

On Unix  systems you can pipe  the audio ouput  to the sound player as
on a HP : mbrola jp3/jp3 tst.pho - | splayer -srate 16000 -l16

Also refer  to the readme.txt file provided  with  the mbrola software
for using it. 

Thanks to the people of the Hirose Lab in the university of tokyo for their help,
and to Baris Bozkurt for processing the database.


Yoram Meron
meron_y@yahoo.com
--------------------------------------------------------------

