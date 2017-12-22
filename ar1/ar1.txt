   A               1
  A A    rrrrr    11
 A   A   r    r  1 1
A     A  r    r    1
AAAAAAA  rrrrr     1
A     A  r   r     1
A     A  r    r  11111

release 1.0 November 1998
-----------------------------------------------------------------

AR1 is a diphone database providing an Arabic male voice.

Created by: Nawfal Tounsi, Faculte Polytechnique de Mons - Belgium

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 Description of the AR1 diphone database
2.0 Installation and tests
3.0 Announcement

--------------------------------------------------------------
1.0 Description of the AR1 diphone database
--------------------------------------------------------------

The following phoneme symbols are assumed in our diphone sets. 
With a few exceptions this set uses the SAMPA notation.

OBSTRUENTS AND NASALS
---------------------

                         stop(plosive):  fricative:      nasal:      flap:    lateral:
--------------------------------------------------------------------------------------
labial:                  b               f, v            m           --       --
alveolar:                t, d            s, z            n           r        l
alveolar velarized:      --              s.              --          --       --
palatal:                 --              S, Z            --          --       --
velar:                   k, g            x, G            --          --       --
glottal:                 ?               h               --          --       --
pharyngeal:              --              X, H            --          --       --
dental:                  --              T, D            --          --       --
debtal velarized         t., d.          --              --          --       --
interdental velarized:   --              z.              --          --       --
uvular:                  q               --              --          --       --
--------------------------------------------------------------------------------------

Notes: 
 d. , t. , s. and z. don't exist in the SAMPA notation

Examples:

phonemes:  letters:      examples:           english translation:
-----------------------------------------------------------------

b          baa?          kalbii [kalbi]      "my dog"
t          taa?          tilaawa [tilawa]    "reading book"
T          thaa?         tha9lab [TaHlab]    "a fox"
Z          jiim          jamaal [Zamal]      "beauty"
X          Haa?          Harbun [Xarbun]     "a war"
x          khaa?         kharaja [xaraZa]    "he went out"
d          daal          dahaba [dahaba]     "he left"
D          dhaal         dhi?bun [Di?bun]    "a worse"
r          raa?          rajulun [rajulun]   "a man"
z          zayn          yazuuru [yazuru]    "he visit"
s          siin          samaka [samaka]     "a fish"
S          shiin         shajara [SaZara]    "a tree"
s.         Saad          Sabaqa [s.a.baqa]   "he passed"
d.         Daad          yuDhiru [jud.hiru]  "it hurst"
t.         Taa?          muHiiT [muXit.]     "sea"
z.         Zaa?          maZluum [maz.lum]   "unfairly"
H          9ayn          9ilmun [Hilmun]     "khowledge"
G          ghayn         ghaabatun [Gabatun] "forest"
f          faa?          faaza [faaza]       "he won"
q          qaaf          qalamun [qalamun]   "a pencil"
k          kaaf          kalbun [kalbun]     "a dog"
l          laam          la9aba [laHaba]     "he played"
m          miim          maata [mata]        "he dead"
n          nuun          naama [nama]        "he slept"
h          haa?          hajama [haZama]     "he attacked"
w          waaw          Daw?un [d.a.w?un]   "a light"
j          yaa?          yal9abu [jalHabu]   "he play"
?          hamza         bi?run [bi?run]     "a well"

VOWELS
------

fatha   a
kasra   i
Damma   u

Notes:
To have a long vowel just write aa , ii and uu respectively

COLORED VOWELS (after /d./ /t./ /z./ and /s./)
---------------------------

fatha   a.
kasra   i.
Damma   u.

Notes:
 Never put /a/, /i/ or /u/ after /d./, /t./, /z./ or /s./.

Examples: 

     Suraakh ("a cry") --> [s.u.rax]   but [s.urax] is FALSE

 mbrola us2 phone.pho - | splayer -srate 16000 -l16

Also refer  to the readme.txt file provided  with  the mbrola software
for using it. 

--------------------------------------------------------------
2.0 Installation and Tests
--------------------------------------------------------------

If  you  have  not copied   the MBROLA software   yet,  please consult
the MBROLA project homepage and get it:

	 http://tcts.fpms.ac.be/synthesis

Copy ar1.zip into your target directory and unzip it : 

   unzip ar1.zip (or pkunzip on PC/DOS)

WINDOWS USERS: If you  have installed Mbrolatools, and registered  ar1
with the Mbrola  Wizard in the  control panel you  can directly double
click on the .pho files distributed in the TEST directory.

Otherwise, try:

  mbrola ar1 TEST/assalam.pho test.wav

to create  a  sound file  for a  short  greeting audio file.   In this
example the audio file follows the RIFF Wave  format. But depending on
the extension test.au, test.aif, or test.raw other file formats can be
obtained.  Listen to it  with your favorite  sound editor, and try the
other command files (*.pho)  to have a  better idea of the quality  of
speech that can be synthesized with MBROLA and the AR1 database. 

On Unix systems you can pipe the audio ouput to the sound player as
on a HP :
 
 mbrola ar1 TEST/assalaam.pho - | splayer  -srate 16000 -l16

On SUN: 

 mbrola ar1 TEST/assalaam.pho -.au | audioplay

Also refer  to the readme.txt file provided  with  the mbrola software
for using it. 

--------------------------------------------------------------
3.0 Announcement
--------------------------------------------------------------

Other databases, or  upgrades  will be  announced in the   mbrola-news
mailing list. 

To subscribe  send  an e-mail  to  mbrola-news-request@tcts.fpms.ac.be
with the word 'subscribe' in either the header or the main text.

-------------------------------------------------------------
Labo. Traitement du Signal et Theorie des Circuits
Faculte Polytechnique de Mons
31, bvd Dolez, B-7000 Mons, Belgium
tel: +32 65 374133  fax:374129            
email : mbrola@tcts.fpms.ac.be
web   : http://tcts.fpms.ac.be/synthesis
--------------------------------------------------------------
