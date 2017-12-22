NN         NN  LL           222222
NN N       NN  LL         22      22
NN  N      NN  LL                 22
NN   N     NN  LL                22
NN    N    NN  LL              22
NN     N   NN  LL            22
NN      N  NN  LL          22   
NN       N NN  LL         22   
NN         NN  LLLLLLLLL  2222222222  release 0.5 - Jun 98
--------------------------------------------------------------
NL2 - Dutch male voice for the MBROLA speech synthesizer

Created by Arthur Dirksen and Ludmila Menert
Fluency Speech Technology, Utrecht/NL
December 1996 - October 1997
--------------------------------------------------------------

UPDATE INFORMATION

For release 0.3 of this database, the following changes were
made:
- new recordings of bad diphones
- segmentation errors fixed
- new diphones added: [r] now combines with all consonants,
so it is possible to generate a "rolling r" in words such as
"arts" (doctor), "arm" (arm), "klaar" (ready); previously 
these words could only be synthesized using the "off-glide r" 
transcribed as [R].

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 Description of the NL2 diphone database
2.0 Distribution
3.0 Installation and tests
4.0 Announcement
5.0 Acknowledgements

--------------------------------------------------------------
1.0 Description of the NL2 diphone database
--------------------------------------------------------------

NL2 is a diphone database for Dutch, consisting of 2321 diphones, 
male voice.

The following phoneme symbols are assumed in our diphone sets. 
With a few exceptions this set uses the SAMPA notation for Dutch.


OBSTRUENTS AND NASALS
---------------------

                stop:           fricative:      nasal:
------------------------------------------------------
labial:         p, b            f, v            m
alveolar:       t, d            s, z            n
palatal:        tj, dj          S, Z            nj
velar:          k, g            x, G            N
glottal:        _ (silence)        h
------------------------------------------------------

Notes: 
- no distinction is made between glottal stop and silence
- Dutch /h/ is a voiced glottal fricative

Examples:

        pad [pAt]               bad [bAt]
        tak [tAk]               dak [dAk]
        potje [pOtj@]           djintan [djIntAn]
        kat [kAt]               zakdoek [zAGduk]

        fiets [fits]            vat [vAt]
        sap [sAp]               zat [zAt]
        sjaal [SaL]             plantage [plAntaZ@]
        lach [lAx]              regen [reG@(n)]
                                huis [h9ys]

        mat [mAt]
        nat [nAt]
        anjer [Anj@r]
        lang [lAN]


LIQUIDS AND GLIDES
------------------

            onset:      coda:
-----------------------------
liguid:     l, r        L, R, r
glide:      w, j        W, J
-----------------------------

Notes:
- the symbols in the right column are coda-allophones
of those in the left column. 
- the coda-allophones must be preceded by a vowel; the
onset-allophones must be followed by a vowel; for example,
there is no l-t diphone, instead L-t must be used.
- the allophone [W] can only follow the long vowels /i/,
/e/ en /y/.
- the allophone [J] can only follow the long vowels /u/,
/o/ and /a/, and the short vowels /O/ and /A/.
- with release 0.3, the allophone [r] can also be used
in coda.

Examples:

        al [AL]         alle [Al@]              al lang [ALlAN]
        haar [haR]      harig [har@x]           haar rug [haRrYx]
        sneeuw [sneW]   sneeuwen [snew@]        sneeuwwit [sneWwIt]
        aai [aJ]        aaien [aj@]             aai Jan [aJjAn]


SHORT VOWELS
------------

                front:                    back:
        [-round]        [+round]        [-round]        [+round]
----------------------------------------------------------------
high:      I               Y                
mid:       E                                @               O
low:                                        A
----------------------------------------------------------------

Examples:

        bid [bIt]               put [pYt]               bos [bOs]
        bed [bEt]               rede [red@]             bak [bAk]


LONG VOWELS
------------

                front:                    back:
        [-round]        [+round]        [-round]        [+round]
----------------------------------------------------------------
high:    i                 y                                u
mid:     e                 2                                o
low:                                        a
----------------------------------------------------------------

Examples:

        bied [bit]              buut [byt]              boek [buk]
        beet [bet]              beuk [b2k]              boot [bot]      
                                                        baat [bat]


DIPHTHONGS
----------

                front:                    back:
        [-round]        [+round]        [-round]        [+round]
----------------------------------------------------------------
mid:       Ei               9y                             Au
----------------------------------------------------------------

Examples:

        bijt [bEit]             buit [b9yt]             bout [bAut]


COLORED VOWELS (before /r/)
---------------------------

                front:                    back:
        [-round]        [+round]        [-round]        [+round]
----------------------------------------------------------------
mid:       I:              Y:                               O:
----------------------------------------------------------------

Notes:
- these symbols are allophones of the long mid vowels
/e/, /2/ and /o/ before /r/, and they must be followed
by either [R] or [r]
- the phoneme symbols /e/, /2/ and /o/ cannot be followed
by [R], but they can be followed by [r].

Examples: 

        beer /ber/ -> [bI:R]    beren /be-r@n/ -> [bI:r@n]
        deur /d2r/ -> [dY:R]    deuren /d2-r@n/ -> [dY:r@n]
        boor /bor/ -> [bO:R]    boren /bo-r@n/ -> [bO:r@n]

        meerook /me-rok/ -> [me-rok]
        meer ook /mer ok/ -> [mI:Rok]
        meer rook /mer rok/ -> [mI:Rrok]


----------------------------------
NASALIZED VOWELS (in French loans)
----------------------------------

                front:                    back:
        [-round]        [+round]        [-round]        [+round]
----------------------------------------------------------------
           E~              Y~              A~              O~
----------------------------------------------------------------

Examples:

        mannequin [mAn@kE~]
        parfum [pARfY~]
        chanson [SA~sO~]

-----------------
FRENCH VOWEL [Oe]
-----------------

Diphones for [Oe] were included so the following French loans 
could be synthesized:

        freule [frOel@]
        oeuvre [Oevr@]
        manoeuvre [manOevr@]
        boeuf [bOef]
        hors d'oeuvre [OrdOevr@]

Do not use [Oe] in any other context!
        

General remarks:

1. Geminate consonants are not included. They must be 
approximated by lengthening of single consonants. Geminate
vowels, however, are included.

2. In previous releases, the silence phoneme would sometimes
contain bits of a preceding vowel, rather annoying if the 
silence had a duration of over 200ms. We have fixed this: it
is now safe to use a single silence phoneme for a pause.

--------------------------------------------------------------
2.0 Distribution
--------------------------------------------------------------

This distribution of NL2.zip contains the following files : 

   NL2          - Dutch male voice
   NL2.txt      - this file
    
and a number of example .PHO files : 

   phone.pho    - home phone number of one of the authors
   singing.pho  - singing synthesis of the word "nee" (no)

   morgen.pho   - "Goedemorgen!" (Good morning!)
   middag.pho   - "Goeiemiddag!" (Good afternoon!)
   avond.pho    - "Goeienavond!" (Good evening!)

   maar.pho     - "Ja, dat ia nou wel erg leuk allemaal,
                  maar wat moet je ermee?" 
                  (casual)
   beetje.pho   - "'t Is een beetje vreemd, maar wel lekker"
                  (creaky)
   sta_op.pho   - "Sta je nou g.v.d. nog 's een keer op?" 
                  (angry)

The file phone.pho is an example of complete synthesis by rule
(input: the digit string "030-28 997 28"). 

All the other examples are copy synthesis. The last three 
examples are experiments in voice quality control and 
speaking style, with rather mixed results. 

The utterance in sta_op.pho sounds "angry" when you turn up 
the volume!


--------------------------------------------------------------
3.0 Installation and Tests
--------------------------------------------------------------

If you have not copied the MBROLA software yet, please consult
the MBROLA project homepage and get it.

Copy NL2.zip into the mbrola directory and unzip it : 

   unzip NL2.zip (or pkunzip on PC/DOS)

Try 

   mbrola NL2 phone.pho phone.wav

to create a sound file for a phone number. In this example the
audio file follows the RIFF Wave format. But depending on the 
extension phone.au, phone.aif, or phone.raw other file formats
can be obtained. Listen to it with your favorite sound editor,
and try the other command files (*.pho) to have a better idea of
the quality of speech that can be synthesized with MBROLA and the 
NL2 database.

On Unix systems you can pipe the audio ouput to the sound player as
on a HP : mbrola NL2 phone.pho - | splayer -srate 16000 -l16

Also refer to the readme.txt file provided with the mbrola 
software for using it.

--------------------------------------------------------------
4.0 Announcement
--------------------------------------------------------------

We are developing a speech synthesis system for Dutch, called
Fluent Dutch. This system, which runs on top of MBROLA and the 
NL2 database, included rules for duration and pitch control,
as well as preprocessing for numerical input. 

For more information and demos, consult the Fluent Dutch home
page at:

http://www-uilots.let.ruu.nl/~Arthur.Dirksen/fluent/fluent.htm

--------------------------------------------------------------
5.0 Acknowledgments
--------------------------------------------------------------

The NL2 database was developed in collaboration with the Research
Institute for Language and Speech/OTS, University of Utrecht.

We would like to thank Vincent Pagel for his efforts in converting
our diphone database to the MBROLA format.

--------------------------------------------------------------

October 1, 1997

Arthur Dirksen
Ludmila Menert

For more information contact: 

        dirksen@let.ruu.nl

or write to:

        Fluency Speech Technology
        Berkelstraat 137
        NL-3522 EM Utrecht, Netherlands
        
--------------------------------------------------------------

