  ##        ##    ##########          ##
  ##        ##    ##        ##      ####
  ##        ##    ##        ##    ##  ##
  ############    ##########          ##
  ##        ##    ##        ##        ##
  ##        ##    ##        ##        ##
  ##        ##    ##########        ######

--------------------------------------------------------------
HB1 - A Hebrew male voice for the MBROLA synthesizer

Created by :  Yoram Meron @ The University of Tokyo

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 Description of the HB1 diphone database
2.0 Installation and tests
3.0 Announcement
4.0 Acknowledgements

--------------------------------------------------------------
1.0 Description of the HB1 diphone database
--------------------------------------------------------------

HB1   is the first release of a diphone database  for  Hebrew, 
"Ashkenazi" accent, consisting of 807 diphones, male voice.

The following  phoneme  symbols are  assumed in  our diphone  sets. 
The symbols do not follow any phonetic standard for Hebrew
transcription, although most symbols are fairly standard. 

SYMBOL  PRONOUNCED LIKE IN (hebrew examples)
_       silence

Vowels: 
a
e
i
o
u

Consonants:
^       ani (meaning - 'I') (in this example - the initial glottal stop)
b       bayit
v       vered
g       gadol
dZ      George (g' - (as pronounced in English) for foreign words only)
d       delet
h       hem
w       washington (v' - for foreign words only)
z       zamar
J       George (j' - (as pronounced in French) for foreign words only)
x       xevel - (meaning - 'rope')  the letter 'het'
t       tefer
j       yeled (the first 'y' sound)
k       kelev
l       lamad
m       matok
n       nafal
s       sefer
p       peleg
f       tof 
Ts      Tsadik
TS      Chernobil (Ts' - only for foreign words)
r       regel
S       shalom ('right shin')
N       baNk (for foreign words only).

Limitations: 
----------- 
The diphone matrix is not full - 'rare diphones' were not
recorded.  In particular diphthongs are not included in the database,
as well as some "Sefaradi accent" consonants.


--------------------------------------------------------------
2.0 Installation and Tests
--------------------------------------------------------------

If  you  have  not copied   the MBROLA software   yet,  please consult
the MBROLA project homepage and get it.

Copy hb1.zip into the mbrola directory and unzip it : 

   unzip hb1.zip (or pkunzip on PC/DOS)

Try 

   mbrola hb1/hb1 hb1/TEST/tst123.pho test.wav

to create a sound file for a short excerpt  of Alice in Wonderland. In
this   example the  audio  file   follows  the RIFF   Wave format. But
depending  on the extension test.au,  test.aif, or test.raw other file
formats can be obtained. Listen to it with your favorite sound editor,
and try the other command files  (*.pho) to have a  better idea of the
quality of speech that  can  be synthesized with   MBROLA and the  US1
database.

On Unix  systems you can pipe  the audio ouput  to the sound player as
on a HP : mbrola hb1/hb1 tst123.pho - | splayer -srate 16000 -l16

Also refer  to the readme.txt file provided  with  the mbrola software
for using it. 

--------------------------------------------------------------
3.0 Announcement
--------------------------------------------------------------

--------------------------------------------------------------
4.0 Acknowledgments
--------------------------------------------------------------

Thanks to Vincent Pagel  for his help and efforts.

--------------------------------------------------------------

Yoram Meron
meron@gavo.t.u-tokyo.ac.jp
http://WWW.gavo.t.u-tokyo.ac.jp/~meron/HomePage-e.html
        
--------------------------------------------------------------

