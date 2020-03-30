 GGGGGG        RRRRR         22222222 
GG    GG      RR   RR       222     222
GG            RR   RR      22        22
GG            RR   R               222
GG   GGGGGG   RRRRRR             2222
GG    GG  G   RR  RR       22222222
GG    GG      RR   RR     222
GG    GG      RR    RR    2222
 GGGGGG       RR     RR   22222222222.v1.May2001
--------------------------------------------------------------
GR2 - An Hellenic (or Greek) male voice for the MBROLA synthesizer

Created by :	Speech Group		
		Department of Informatics and Telecommunications
		University of Athens
		http://www.di.uoa.gr/speech
              
-------------------------------------------------------
Table of Contents
-------------------------------------------------------
1. Description of GR2 database    
	a. UoA-TtS-PA
	b. Use
2. Distribution and test
3. Acknowledgments

-------------------------------------------------------
1. Brief description of GR2 database
-------------------------------------------------------
GR2 is an Hellenic male diphone database provided in the
context of the MBROLA project (https://github.com/numediart/MBROLA/).

It consists of 1081 diphones.

We use the UoA-TtS-PA phonetic alphabet for Text-to-Speech systems 
version 1 (http://www.di.uoa.gr/speech/synthesis/ttspa), which inherits from SAMPA 
but additionally, it introduces some group of phones as clusters. 
This enhances the phonemic representation in Text-to-Speech synthesizers, 
because complex coarticulations are handled as single clusters and not as 
concatenation of discrete phones.

a. UoA-TtS-PA
-------------
General rules:
- We use the notion of 'cluster' instead of 'phoneme' as some units in the database
comprises of more than one traditional 'phoneme' (e.g. /X/ -> /k//s/)
- Each cluster is assigned to a single byte (ASCII character) for faster processing
in the Text-to-Speech system
- Capital vowels imply accents (e.g. /A/ instead of /'a/), but there is not such a 
distinction in the current version of the database.
- Thus, 37 clusters are currently defined:

UoA-TtS-PA 	SAMPA	Example 	Hellenic transcription (ISO8859-7)(English)
_		_	(silence)	(ðáýóç) (pause)

[consonants]
p		p	patAta		ðáôÜôá (potato)
b		b	balOni		ìðáëüíé (baloon)
t		t	tirOpita	ôõñüðéôôá (cheesepie)
d		d	dInome		íôýíïìáé (get dressed)
k		k	kalAmi		êáëÜìé (cane)
c		c	cerI		êåñß (candle)
g		g	gremIzo		ãêñåìßæù (blast) 
q		gj	aqelIa		áããåëßá (announcement)

f		f	fotinO		öùôåéíü (luminous)
v		v	vuLAzo		âïõëéÜæù (sink)
T		T	Talassa		èÜëáóóá (sea)
D		D	DAskalos	äÜóêáëïò (teacher)
s		s	salAta		óáëÜôá (salad)
z		z	zoGraficI	æùãñáöéêÞ (paint)

G		G	GAla		ãÜëá (milk)
j		jj,j	jortI, vjEno	ãéïñôÞ, âãáßíù (celebration, go out)

x		x	xarUmenos	÷áñïýìåíïò (happy)
C		C	CEri		÷Ýñé (hand)
	
m		m	mATima		ìÜèçìá (lesson)
M		mj	apaneMA		áðáíåìéÜ (calm)

n		n	nanUrisma	íáíïýñéóìá (lullaby)
N		nj	NaurIzo		íéáïõñßæù (meow)
V		(-)	aVgaLAzo	áãêáëéÜæù (bosom)

r		r	ropI		ñïðÞ (torsion)
R		r	tRopI		ôñïðÞ (turn)

l		l	lAva		ëÜâá (lava)
L		lj	LOno		ëéþíù (melt)

S		ts	SalakOno	ôóáëáêþíù (crumple)
Z		dz	ZamarIa		ôæáìáñßá (glass)
X		ks	XirAfi  	îõñÜöé (razor) 
Y		ps	YAri		øÜñé (fish)

[vowels]
a		a	aEras		áÝñáò (wind)
e		e	elpIDa		åëðßäá (hope)
i		i	irIni		åéñÞíç (peace)
o		o	Oros		üñïò (clause)
u		u	uranOs		ïõñáíüò (sky)

b. Use of the database
----------------------
All the combinations of clusters are supported 
apart from the cases:

1. /M/, /N/, /L/, /C/, /c/, /j/, /q/
	must be followed by vowel (/a/, /e/, /i/, /o/, /u/)
	
2. /r/	must follow a vowel or silence (/a/, /e/, /i/, /o/, /u/, /_/)

3. /R/	must follow a consonant

4. /V/	must be followed by /g/ or /q/

---------------------------------------------------------
2. Distribution and test
---------------------------------------------------------
If you have not copied the MBROLA software yet, please consult
the MBROLA project homepage (https://github.com/numediart/MBROLA/).
Refer to the readme.txt file provided with the mbrola software
for using it. 

This distribution of MBROLA database contains the following files:
gr2		:the GR2 MBROLA database
gr2.txt		:this file  
test\*.pho	:pho examples 

----------------------------------------------------------
3. Acknowledgments
----------------------------------------------------------
The voice of GR2 MBROLA database belongs to Gerasimos Xydas
(email:gxydas@di.uoa.gr). The database was recorded, 
segmented and processed by him in the Speech Lab of our department.

We would like to especially thank Baris Bozkurt for his help 
in building this database and his efforts on the mbrolization 
of the database.

Dr. George Kouroupetroglou
University of Athens 
Department of Informatics 
Division of Communication and Signal Processing 
Panepistimiopolis, Ilisia 
GR-15784 Athens, Greece 
email:koupe@di.uoa.gr
tel.:  + 30 1 7275305 
fax:   + 30 1 6018677
