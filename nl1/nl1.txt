NN         NN  LL            11
NN N       NN  LL          1 11
NN  N      NN  LL         1  11
NN   N     NN  LL            11
NN    N    NN  LL            11
NN     N   NN  LL            11
NN      N  NN  LL            11
NN       N NN  LL            11
NN         NN  LLLLLLLLL  11111111 preliminary release 0.2
----------------------------------------------------------------
Dutch male voice for the MBROLA speech synthesizer
!!IMPORTANT:This database only includes diphones for synthesizing 
numbers in Dutch

Copyright (C) 1996 by Arthur Dirksen and Ludmila Menert, Utrecht
----------------------------------------------------------------

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 Description of NL1
2.0 Distribution
3.0 Installation, and tests
4.0 Acknowledgements

--------------------------------------------------------------
1.0 Description of NL1
--------------------------------------------------------------

NL1 is a preliminary version of a diphone database for Dutch,
restricted to the purpose of synthesizing (phone) numbers. For
this purpose we needed to include only 142 diphones.

A FULL SET OF DIPHONES FOR DUTCH IS CURRENTLY UNDER 
CONSTRUCTION, AND WILL BE AVAILABLE SOON!
A FEMALE VOICE IS ALSO IN PREPARATION.

The following phoneme symbols are assumed in our diphone sets
(Note: only a small subset is currently used). With a few 
exceptions this set uses the SAMPA notation for Dutch.

OBSTRUENTS AND NASALS
---------------------

		stop:		fricative:	nasal:
------------------------------------------
labial:	p, b		f, v		m
alveolar:	t, d		s, z		n
palatal:	tj, dj	S, Z		nj
velar:	k, g		x, G		N
glottal:	_ (silence)	   h
------------------------------------------

Notes: 
- no distinction is made between glottal stop and silence
- Dutch /h/ is a voiced glottal fricative

Examples:

	pad [pAt]		bad [bAt]
	tak [tAk]		dak [dAk]
	potje [pOtj@]	djintan [djIntAn]
	kat [kAt]		zakdoek [zAGduk]

	fiets [fits]	vat [vAt]
	sap [sAp]		zat [zAt]
	sjaal [SaL]		plantage [plAntaZ@]
	lach [lAx]		regen [reG@(n)]
				huis [h9ys]

	mat [mAt]
	nat [nAt]
	anjer [Anj@r]
	lang [lAN]

LIQUIDS AND GLIDES
------------------

            onset:	coda:
-----------------------------
liguid:	l, r		L, R
glide:	w, j		W, J
----------------------------

Notes:
- the symbols in the right column are coda-allophones
of those in the left column. Examples:

	al [AL]		alle [Al@]	   	al lang [ALlAN]
	haar [haR]		harig [har@x]	haar rug [haRrYx]
	sneeuw [sneW]	sneeuwen [snew@]  sneeuwwit [sneWwIt]
	aai [aJ]		aaien [aj@]	   	aai Jan [aJjAn]

SHORT VOWELS
------------

		front:			  back:
	[-round]	[+round]	[-round]	[+round]
--------------------------------------------------
high:	   I           Y		
mid:     E				    @		    O
low:					    A
--------------------------------------------------

Examples:

bid [bIt]		put [pYt]		bos [bOs]
bed [bEt]		rede [red@]		bak [bAk]

LONG VOWELS
------------

		front:			  back:
	[-round]	[+round]	[-round]	[+round]
--------------------------------------------------
high:    i            y		                u
mid:     e            2				    o
low:					    a
--------------------------------------------------

Examples:

bied [bit]		buut [byt]		boek [buk]
beet [bet]		beuk [b2k]		boot [bot]	
						baat [bat]


DIPHTHONGS
----------

		front:			  back:
	[-round]	[+round]	[-round]	[+round]
--------------------------------------------------
mid:	   Ei		    9y			   Au
--------------------------------------------------

Examples:

bijt [bEit]		buit [b9yt]		bout [bAut]

COLORED VOWELS (before /r/)
---------------------------

		front:			  back:
	[-round]	[+round]	[-round]	[+round]
--------------------------------------------------
mid:	   I:		   Y:				    O:
--------------------------------------------------

Notes:
- these symbols are allophones of the long mid vowels
/e/, /2/ and /o/ before /r/. 

Examples: 

	beer	/ber/ -> [bI:R]
	deur	/d2r/ -> [dY:R]
	boor	/bor/ -> [bO:R]


In the present version, we have included only the diphones
needed to synthesize the following numbers and their 
combinations:

	0	[nYL]			11	[ELf]
	1	[en]			12	[twaLf]
	2	[twe]			13	[dERtin]
	3	[dri]			14	[vI:Rtin]
	4	[viR]			20	[twInt@x]
	5	[vEif]		30	[dERt@x]
	6	[zEs]			80	[tAxt@x]
	7	[zev@n]		100	[hOnd@rt]
	8	[Axt]
	9	[neG@n]
	10	[tin]

All numbers up to 999 not listed above are considered regular 
combinations of the above.

Remarks:

1. Voice assimilation in obstruent clusters is accounted for.
Thus, the sequence 6-3 is synthesized by [_zEzdri_] rather than 
[_zesdri_], although it is possible to ignore assimilation by 
insertion of silence: [_zEs_dri_]. Also, 8-3 is synthesized by
[_AGdri_] rather than [_axtdri_], although [_axt_dri_] is possible.

2. Degemination is obligatory. Thus, 8-10 is synthesized by [_Axtin_]
rather than [_Axttin_], although [_Axt_tin_] is admitted. Also, 
assimilated fricatives may undergo degemination: 5-5 is synthesized
by [_vEifEif_] (i.e. /vEif-vEif/ -> /vEif-fEif/ -> /vEifEif/).

3. Productive combinations such as 21 [_en@ntwInt@x_] (one and twenty)
are admitted. However, 24 should be transcribed as [_viR@ntwInt@x_]
rather than the theoretically correct [_vir@ntwInt@x_] 
(resyllabifcation).

4. Schwa-insertion as in /ELf/ -> /El@f/, /twaLf/ -> /twal@f] is not 
accounted for, regrettably.

5. Also, we have overlooked the fact that the numbers 40, 50, 60 
and 70 (as well as their combinations) are pronounced with an 
intitial voiceless rather than voiced fricative. Thus, although 
[_vI:Rt@x_] sounds wrong, it is the only way to synthesize the
number 40 with the current diphone set.

6. The final /n/ in /zev@n/ and /neG@n/ is often deleted (or
so they say). This is not accounted for. However, [_zev@n_] will
sound quite natural if the final /n/ is kept very short (say, 20 ms).

7. Although the current diphone set is restricted to numbers,
some non-numerical Dutch words have inadvertently been included.
Much to our surprise, it is possible to synthesize a complete
dialog: "Een hond? Nee, een eend!" [_@nhOnt_ne_@n_ent_] (A dog?
No, a duck!).

--------------------------------------------------------------
2.0 Distribution
--------------------------------------------------------------

This distribution of nl1.zip contains the following files : 

   nl1		- Dutch male voice
   nl1.txt		- this file
   license.txt - Read before using this database 

and a number of example .PHO files : 

   phone.pho	- home phone number of one of the authors
   singing.pho	- singing synthesis of the word "nee" (no)

   1-10.pho		- the numbers 1 to 10
   11-20.pho	- the numbers 11 to 20
   21-30.pho	- the numbers 21 to 30 (yawn!)
   888.pho		- the number 888
   dialog.pho	- "Een hond? Nee, een eend!" (A dog? No, a duck!)

The first two files are close copies of natural utterances. All the
other ones were generated by rule from a phonemic transcription.
Don't ask for a copy of these rules unless you are willing to
pay handsome amounts of money!

Additional languages and voices, as well as other example command
files, are or will be available in the context of the MBROLA 
project. Please consult the MBROLA project homepage :

   http://tcts.fpms.ac.be/synthesis/mbrola.html

Registered users will automatically be notified of the availability 
of new databases. To freely register, simply send an email to 
mbrola-interest-request@tcts.fpms.ac.be with the word 'subscribe'
in the message title.

--------------------------------------------------------------
3.0 Installation and Tests
--------------------------------------------------------------

If you have not copied the MBROLA software yet, please consult
the MBROLA project homepage and get it.

Copy nl1.zip into the mbrola directory and unzip it : 

   unzip nl1.zip (or pkunzip on PC/DOS)

Try 

   mbrola nl1 phone.pho phone.wav

to create a sound file for a phone number. In this example the
audio file follows the RIFF Wave format. But depending on the 
extension phone.au, phone.aif, or phone.raw other file formats
can be obtained. Listen to it with your favorite sound editor,
and try the other command files (*.pho) to have a better idea of
the quality of speech that can be synthesized with MBROLA and the 
NL1 database.

On Unix systems you can pipe the audio ouput to the sound player as
on a HP : mbrola nl1 phone.pho - | splayer -srate 16000 -l16

Also refer to the readme.txt file provided with the mbrola 
software for using it.

--------------------------------------------------------------
4.0 Acknowledgments
--------------------------------------------------------------

The NL1 database was developed in collaboration with the Research
Institute for Language and Speech/OTS, University of Utrecht.

We would like to thank Vincent Pagel for his efforts in converting
our diphone database to the MBROLA format.

--------------------------------------------------------------

October 1, 1996

Arthur Dirksen
Ludmila Menert

For more information contact: 

	dirksen@let.ruu.nl

or write to:

	Berkelstraat 137, 3522 EM Utrecht, Netherlands
--------------------------------------------------------------
