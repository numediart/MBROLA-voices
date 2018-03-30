EEEEEE    EEEEEEE      1
E         E            1
E         E            1
E         E            1
EEEE      EEEE         1
E         E            1
E         E            1
E         E            1
EEEEEEE   EEEEEEE      1   release 07 April 2002

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 A brief description of the EE1 database
2.0 Distribution
3.0 Installation, and tests
4.0 Author

------------------------------------------------------------
1.0 A brief description of EE1
------------------------------------------------------------

EE1  release is a Standard  Estonian  diphone database provided in the
context of the MBROLA project:   http://tcts.fpms.ac.be/synthesis

It provides an Estonian male voice to be used with the MBROLA program.

Input  files use  the  Estonian  orthographic  notation. The  Estonian
orthography is not  phonetic. Some essential  phonological oppositions
as  well as phonologically  non-relevant phonetic facts (but important
from  the point of   view of orthoepy   and speech naturality) are not
exposed in the written form of Estonian.  

The   sound system of   Standard Estonian  comprises  9  vowel  and 17
consonant phonemes,  all of which can occur  as short (single) or long
(double  vowels and geminate  consonants).  In Estonian there are  two
segmental lengths  (short/long) and  three phonologically  distinctive
foot patterns - quantity degrees: Q1, Q2 and Q3. 

Below is a list of the  Standard Estonian phonemic  units in the SAMPA
transcription with examples in the Estonian orthography.

SAMPA		SAMPA			Orthography
symbol 	transcription

i		kilu			kilu  (Q1) 'sprat, nom.sg.'
ii		kiilu			kiilu (Q2) 'wedge, gen.sg.'
		kii:lu		kiilu (Q3) 'wedge, part.sg.'
e		ketA			keda	 (Q1) 'whom'
ee		keetA			keeda (Q2) 'boil, 2.sg.imperat.'
		kee:tA		keeda (Q3) 'boil, da-inf.'
{		k{ru			käru	 (Q1) 'barrow, nom.sg.'
{{		k{{ru			kääru (Q2) 'crook, gen.sg.'
		k{{:ru		kääru (Q3) 'crook, part.sg.'
y		myrin			mürin (Q1) 'rumble, nom.sg.'
yy		myyri			müüri (Q2) 'wall, gen.sg.'
		myy:ri		müüri (Q3) 'wall, part.sg.'
2		l2mA			löma	 (Q1) 'squash, nom.sg.'
22		l22mA			lööma (Q2) 'beating, gen.sg.'
		l22:mA		lööma (Q3) 'to beat, ma-inf.'
u		kuri			kuri  (Q1) 'evil, nom.sg.'
uu		kuuri			kuuri (Q2) 'shed, gen.sg.'
		kuu:ri		kuuri (Q3) 'shed, part.sg.'
o		pori			pori  (Q1) 'mud, nom.sg.'
oo		poori			poori (Q2) 'pore, gen.sg.'
		poo:ri		poori (Q3) 'pore, part.sg.'
7		k7mA			kõma  (Q1) 'boom, nom.sg.'
77		k77mA			kõõma (Q2) 'dandruff, gen.sg.'
		k77:mA		kõõma (Q3) 'dandruff, part.sg.'
A		sAtA			sada  (Q1) 'hundred, nom.sg.'
AA		sAAtA			saada (Q2) 'send, 2.sg.imperat.'
		SAA:tA		saada (Q3) 'get, da-inf.'

The vowel /7/ represents non-low back unrounded vowels.

P		tApA			taba  (Q1) 'padlock, nom.sg.'
pp		tAppA			tapa  (Q2) 'kill, 2.sg.imperat.'
		tAp:pA		tappa (Q3) 'kill, da-inf.'
t		pAtu			padu  (Q1) 'a low wet place, nom.sg.'
tt		pAttu			patu  (Q2) 'sin, gen.sg.'
		pAt:tu		pattu (Q3) 'sin, part.sg.'
t'		pAt'i			padi  (Q1) 'pillow, nom.sg.'
t't		pAt'ti		pati  (Q2) 'stalemate, gen.sg.'
		pAt':ti		patti (Q3) 'stalemate, part.sg.'	
k		kAku			kagu  (Q1) 'southeast, nom.sg.'
kk		kAkku			kaku  (Q2) 'loaf, owl, gen.sg.'
		kAk:ku		kakku (Q3) 'loaf, owl, part.sg.'
f		foori			foori (Q2) 'traffic lights, gen.sg.'
ff		tuffi			tufi  (Q2) 'tufa, gen.sg.'
		tuf:fi		tuffi (Q3) 'tufa, part.sg.'
v		kAvA			kava  (Q1) 'plan, nom.sg.'
vv		sAvvA			Savva (Q2) 'Savva, name, nom.sg.'
		kAv:vA		kavva (Q3) 'plan, illat.sg.'
s		m{su			mäsu  (Q1) 'tumult, nom.sg.'
ss		m{ssu			mässu (Q2) 'revolt, gen.sg.'
		m{s:su		mässu (Q3) 'revolt, part.sg.'
s'		kAs'i			kasi  (Q1) 'clean, 2.sg.imperat.'
s's		kAs'si		kassi (Q2) 'cat, gen.sg.'
		kAs':si		kassi (Q3) 'cat, part.sg.'
S		Seffi			efi  (Q2)'chief, gen.sg.'
 		looSi			loozi (Q2) 'loge, gen.sg.'
SS		tuSSi			tui  (Q2) 'Indian ink, gen.sg.'
		tuS:Si		tui (Q3) 'Indian ink, part.sg.'
h		sAhin			sahin (Q1) 'rustle, nom.sg.'
hh		SAhhi			ahhi (Q2) 'shah, gen.sg.'
		SAh:hi		ahhi (Q3) 'shah, part.sg.'
m		sAmu			samu  (Q1) 'same, part.pl.'
mm		sAmmu			sammu (Q2) 'step, gen.sg.'
  		sAm:mu		sammu (Q3) 'step, part.sg.'
n		kAnu			kanu  (Q1) 'hen, part.pl.'
nn		kAnnu			kannu (Q2) 'jug, gen.sg.'
		kAn:nu		kannu (Q3) 'jug, part.sg.'
n'		pAn'i			pani  (Q1) 'put, 3.sg.past'
n'n		pAn'ni		panni (Q2) 'pan, gen.sg.'
		pAn':ni		panni (Q3) 'pan, part.sg.'
l		kAlAs			kalas (Q1) 'fish, iness.sg.'
ll		kAllAs		kallas (Q2) 'shore, nom.sg.'
		kAl:lAs		kallas (Q3) 'pour, 3.sg.past'
l'		pAl'i			pali  (Q1) 'tub, nom.sg.'
l'l		pAl'li		palli (Q2) 'ball, gen.sg.'
		pAl':li		palli (Q3) 'ball, part.sg.'
r		nAri			nari  (Q1) 'plank bed, nom.sg.'
rr		nArri			narri (Q2) 'fool, gen.sg.'
		nAr:ri		narri (Q3) 'fool, part.sg.'
j		mAjA			maja  (Q1) 'house, nom.sg.'
jj		mAjjA			majja (Q3) 'house, illat.sg.'

Consonants with /'/ are palatalized.

Q1  and Q2 need no  special marking. Natural-sounding  Q2 is generated
from Q1 by doubling  the duration of  the respective short phonemes in
Q1 and changing the duration  of the stressed and unstressed syllables
to the needed  duration ratio, and by  determining the location of the
F0 peak in the stressed syllable. 

We mark  Q3 by a  colon placed after  the peak of the  Q3 foot. All Q3
feet are either  vowel-peaked or consonant-peaked.  The colon does not
denote a Q3 phoneme but indicates that the whole foot is in the Q3. At
the same   time the colon  signalises  the  duration increment  of the
preceding syllable-final phoneme.

In order to  distinguish the qualitatively  strongly reduced vowels of
an unstressed syllable of the Q3 foot  and the corresponding vowels of
the Q1 and Q2 feet, we mark the vowels of an  unstressed syllable of a
Q3 foot by number 3 (i3, e3,... etc.) in the diphone database.  

About detailed description of the Estonian diphone database see:

M.Mihkla, A.Eek, E.Meister, Creation of the Estonian diphone database
for text-to-speech  synthesis.  - Proceedings of  the Finnic Phonetics
Symposium,  August 11-14,  1998,  Pärnu, Estonia.  Linguistica Uralica
XXXIV, 1998, 3: 334-340.

Limitations:
-----------
EE1   diphone  database is currently  not   fully completed.  The full
diphone database will be   available after the test  period  currently
going on at the authors' laboratories. 

For  the  full text-to-speech we    need  to use  additional  programs
(morphologic analysis of input text, determination  of Q3 feet, adding
stress   marks  and   syllable  boundaries,  etc.)  developed  by  the
researchers from the Institute of Estonian Language (Tallinn) and from
Filosoft Ltd. (Tartu).

--------------------------------------------------------------
2.0 Distribution
--------------------------------------------------------------

This distribution of mbrola contains the following files : 

   ee1        : the database itself
   ee1.txt    : This file
   license.txt: must read before using the database
 
and example .PHO files:
  tere.pho
  example.pho

Additional languages  and  voices, as  well as other   example command
files,  are or   will  be available in   the   context of  the  MBROLA
project. Please consult the MBROLA project homepage : 
   http://tcts.fpms.ac.be/synthesis

Registered users will automatically be notified of the availability of
new   databases.  To   freely  register,  simply   send an   email  to
mbrola-interest-request@tcts.fpms.ac.be  with the word 'subscribe'  in
the message title.


--------------------------------------------------------------
3.0 Installation and Tests
--------------------------------------------------------------

If you have not copied the MBROLA software yet, please consult the
MBROLA project homepage and get it.

Copy ee1.zip into the mbrola directory and unzip it : 

 unzip ee1.zip (or pkunzip on PC/DOS)
 (don't forget to delete the .zip file when this is done)

On PC-Windows register ee1 with the Wizard in the control panel.

On unix platforms, try:

 mbrola ee1 TEST/example.pho example.wav

to create a  sound file. In this   example the audio  file follows the
RIFF Wav  format.   But    depending on the    extension   example.au,
example.aif, or example.raw you can obtain other file  formats. Listen
to it with your favorite sound editor, and try the other command files
(*.pho)   to have  a better idea   of  the quality  of  speech you can
synthesize with the MBROLA technique. 

On Unix systems you can pipe the audio ouput to the sound player as on
a HP : mbrola ee1 TEST/example.pho - | splayer -srate 16000 -l16 

Also refer  to the readme.txt file provided   with the mbrola software
for using it.

--------------------------------------------------------------
4.0 Author
--------------------------------------------------------------

This database was recorded by: 

Einar Meister, M.Sc. and Arvo Eek, Dr.Phil. from the
Laboratory of Phonetics and Speech Technology
Institute of Cybernetics
Akadeemia tee 21
Tallinn EE0026
ESTONIA

phone: +372 6204200 fax: +372 6397039 email: einar@ioc.ee

and

Meelis Mihkla
Institute of Estonian Language
Roosikrantsi 6
Tallinn 10119
ESTONIA

phone: +372 2 443564 fax: +372 6411443 email: meelis@eki.ee

For general information, questions on the installation of software and
databases, contact mbrola@tcts.fpms.ac.be
