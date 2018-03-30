######             #
#     #   #####   ##
#     #     #    # #
######      #      #
#           #      #
#           #      #
#           #    #####

release 0.1 - May 2000
--------------------------------------------------------------
PT1 - A European Portuguese female voice for the MBROLA synthesizer

Created by :  Babel Technology SA
              Speech Synthesis Group

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 Description of the PT1 diphone database
2.0 Installation and tests
3.0 Announcement
4.0 Acknowledgements

--------------------------------------------------------------
1.0 Description of the PT1 diphone database
--------------------------------------------------------------

PT1 is a diphone database for European Portuguese, consisting of 1369
diphones, female voice.

The following  phoneme  symbols are  assumed in  our diphone  sets. 

Plosives

  Symbol   Word    Transcription
  p   pai    paj
  b   barco  "barku
  t   tenho  "teJu
  d   doce   "dos@
  k   com    ko~
  g   grande "gr6nd@

Fricatives 

  f   falo    "falu
  v   verde   "verd@
  s   céu    sEw
  z   casa    "kaz6
  S   chapéu   S6"pEw
  Z   jóia    "ZOj6

Nasals 

  m   mar    mar
  n   nada    "nad6
  J   vinho   "viJu

Liquids 

  l   lanche   "l6nS@
  L   trabalho  tr6"baLu
  r   caro    "karu
  R   rua    "Ru6

Vowels and diphthongs 
  i   vinte   "vint@
  e   fazer   f6"zer
  E   belo    "bElu 
  a   falo    "falu
  6   cama    "k6m6 
  O   ontem   "Ont6~j~
  o   lobo    "lobu
  u   jus    ZuS 
  @   felizes  f@"liz@S

  i~  fim    fi~ 
  e~  emprego  e~"pregu 
  6~  irmã    ir"m6~
  o~  bom    bo~
  u~  um  u~

  w   mau    maw 
  j   mais   (majS)  dei (dEj)  mui (muj) pei (pej) boi (bOj)  bóia (boj6)

  6~j~    têm    t6~j~

--------------------------------------------------------------
2.0 Installation and Tests
--------------------------------------------------------------

If  you  have  not copied   the MBROLA software   yet,  please consult
the MBROLA project homepage and get it.

Copy pt1.zip into the mbrola directory and unzip it : 

   unzip pt1.zip (or pkunzip on PC/DOS)

Try 

   mbrola pt1/pt1 pt1/TEST/test.pho test.wav

to create a sound file. In this  example the audio file  follows
the RIFF  Wave format. But depending on the extension test.au,
test.aif, or test.raw other file formats can be obtained. Listen to it
with your favorite sound editor, and try the other command files
(*.pho) to have a better idea of the quality of speech that can be
synthesized with  MBROLA and the PT1 database.

On Unix systems you can pipe the audio ouput to the sound player as
on a HP : mbrola pt1 test.pho - | splayer -srate 16000 -l16

Also refer to the readme.txt file provided with the mbrola software
for using it. 

--------------------------------------------------------------
3.0 Announcement
--------------------------------------------------------------

This database is a beta release, and we will take your comments into
account for  future updates. Updates  will be announced on the
mbrola-news mailing list.

For more information and demos, consult the Babel Technology SA home
page at: 

   http://www.babeltech.com

--------------------------------------------------------------
4.0 Acknowledgments
--------------------------------------------------------------

We would like to thank Maria Abalho for her collaboration

--------------------------------------------------------------

Babel Technology SA
Speech Synthesis Group
33 bvd Dolez
B7000 MONS
Belgium

Tel: +32 65 37 42 75
Fax: +32 65 37 42 76
Email: pagel@babeltech.com
WWW: http://www.babeltech.com
    
--------------------------------------------------------------

