   ########       ##########          ##
      ##          ##        ##      ####
      ##          ##        ##    ##  ##
      ##          ##########          ##
      ##          ##                  ##
  ##  ##          ##                  ##
   ####           ##                  ##  
    ##            ##                ######
--------------------------------------------------------------
JP1 - A Japanese male voice for the MBROLA synthesizer

Created by :  Yoram Meron @ The University of Tokyo

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 Description of the JP1 diphone database
2.0 Installation and tests
3.0 Announcement
4.0 Acknowledgements

--------------------------------------------------------------
1.0 Description of the JP1 diphone database
--------------------------------------------------------------

JP1   is the first release of a diphone database  for  Japanese, 
(Tokyo accent), consisting of 379 diphones, male voice.

The following  phoneme  symbols are  assumed in  our diphone  sets. 
The symbols do not exactly follow any one phonetic standard for Japanese
transcription, but most symbols are fairly standard. Below there is a
description only of differences to the "standard" roma-ji transcription. 

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
g          this was the natural way the speaker read 'g' - in many
           cases this is an ng sound.
G          a hard 'g' sound (not ng)
s          
S          sh sound
m          
n          na, ni, nu, ne, no
w          
j          ya, yu, yo, and also used for creating kya, kyu ...
rr         ra, ri, ... 
tS         ch sound (transcribed as ti ot tyi)
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

Copy jp1.zip into the mbrola directory and unzip it : 

   unzip jp1.zip (or pkunzip on PC/DOS)

Try 

   mbrola jp1/jp1 jp1/TEST/tst.pho test.wav

to create a sound file for a short excerpt  of Alice in Wonderland. In
this   example the  audio  file   follows  the RIFF   Wave format. But
depending  on the extension test.au,  test.aif, or test.raw other file
formats can be obtained. Listen to it with your favorite sound editor,
and try the other command files  (*.pho) to have a  better idea of the
quality of speech that  can  be synthesized with   MBROLA and the  US1
database.

On Unix  systems you can pipe  the audio ouput  to the sound player as
on a HP : mbrola jp1/jp1 tst.pho - | splayer -srate 16000 -l16

Also refer  to the readme.txt file provided  with  the mbrola software
for using it. 

--------------------------------------------------------------
3.0 Announcement
--------------------------------------------------------------

--------------------------------------------------------------
4.0 Acknowledgments
--------------------------------------------------------------

Thanks to Koji Iwano for his help with the recordings, and to 
Vincent Pagel  for his help and efforts.

--------------------------------------------------------------

Yoram Meron
meron@gavo.t.u-tokyo.ac.jp
http://WWW.gavo.t.u-tokyo.ac.jp/~meron/HomePage-e.html
        
--------------------------------------------------------------

