DE7 -- a female German voice with three levels of vocal effort
==============================================================

1. General description
2. Diphone inventory
3. Examples
4. Contact

1. General description
======================

DE7 is a female German diphone voice created in the context of the EU project
NECA (IST-2000-28580), with the aim of being particularly suitable for the
flexible synthesis of expressive speech.

The main feature of DE7 is therefore that it contains a complete diphone
set for three different voice qualities defined by their vocal effort, low
effort ("soft voice"), medium effort ("normal or modal voice"), and high
effort ("loud voice").

2. Diphone inventory
====================

DE7 uses the SAMPA phonetic alphabet as defined under
http://www.phon.ucl.ac.uk/home/sampa/home.htm. In addition to the German
phonemes, some English and French phonemes are included in order to allow
for the synthesis of foreign words. These additions do not claim
completeness and are not intended for the synthesis of full-sentence
English or French speech, but solely for the generation of a typical German
speaker's rendition of English or French words.

German phonotactics do not allow all possible diphones. Therefore, only
those diphones considered relevant were recorded. However, as some users
may intend to use the database for different tasks than expected, a
translation table maps *all* unexisting diphones to similar existing
diphones. As a consequence, for all combinations of the phone symbols
listed below into diphones, at least an approximate realisation is
provided.

As an example, final devoicing in German usually makes it impossible to
have voiced consonants at the end of a word or a morpheme. Therefore,
diphones such as "d-f" were not recorded. If this diphone is requested,
"t-f" will be realised instead.

Phone inventory:
----------------

Silence
        _               Silence before and after phrases

German phones:
--------------
(examples taken from http://www.phon.ucl.ac.uk/home/sampa/german.htm,
slightly adapted)

Vowels:

	I		Sitz		zIts
	E		Gesetz		g@zEts
	a		Satz		zats
	O		Trotz		trOts
	U		Schutz		SUts
	Y		hübsch		hYpS
	9		plötzlich	pl9tslIC

	i:		Lied		li:t
	e:		Beet		be:t
	E:		spät		SpE:t
	a:		Tat		ta:t
	o:		rot		ro:t
	u:		Blut		blu:t
	y:		süß		zy:s
	2:		blöd		bl2:t

	aI		Eis		aIs
	aU		Haus		haUs
	OY		Kreuz		krOYts

	@		bitte		bIt@
	6		besser		bEs6

Glottal stop:
	?		Verein			fE6?aIn

The glottal stop is treated as a normal phone with which diphones can be
built (in the example: "6-?" and "?-aI"). It was recorded as a
word-internal juncture which is smaller than real silence "_".

Consonants:
	p		Pein			paIn
	b		Bein			baIn
	t		Teich			taIC
	d		Deich			daIC
	k		Kunst			kUnst
	g		Gunst			gUnst

	pf		Pfahl			pfa:l
	ts		Zahl			tsa:l
	tS		deutsch			dOYtS

The "dZ" is not included as a separate phone due to its rarity in
German. It can be approximated as "d"+"Z".

	f		fast			fast
	v		was			vas
	s		Tasse			tas@
	z		Hase			ha:z@
	S		waschen			vaS@n
	Z		Genie			Zeni:
	C		sicher			zIC6
	j		Jahr			ja:6
	x		Buch			bu:x
	h		Hand			hant

	m		mein			maIn
	n		nein			naIn
	N		Ding			dIN
	l		Leim			laIm
	R		Reim			RaIm

English phones added:
---------------------
(examples taken from http://www.phon.ucl.ac.uk/home/sampa/english.htm,
slightly adapted)

	EI		raise			rEIz
Note that "EI" is used instead of English sampa "eI".

	T		thin			TIn
	D		this			DIs

	r		wrong			rON
	w		wasp			wOsp


French phones added:
--------------------
(examples taken from http://www.phon.ucl.ac.uk/home/sampa/french.htm,
slightly adapted)

	e~		vin			ve~
	a~		vent			va~


Vocal effort
------------

Each of the above-mentioned phone symbols also exists in a variant recorded
with higher vocal effort and in a variant recorded with lower vocal
effort. These variants are identified by appending a suffix to the phone
symbol, "_loud" for the high-vocal-effort variant and "_soft" for the
low-vocal-effort variant. The default variant, with no suffix, corresponds
to a medium, "normal" level of vocal effort.

For each vocal effort setting, a full diphone set was recorded. In order to
increase naturalness and ease of use, the low-vocal-effort diphone set is
normalised at -1.5dB relative to the default, medium-vocal-effort diphone
set, and the high-vocal-effort diphone set is normalised at +1.5dB relative
to the default. For ease of reference, the simplifying integrated
descriptions "loud" and "soft" were preferred over the more accurate, but
less intuitive descriptions "higher vocal effort" and "lower vocal effort".

While not yet explored scientifically, it is technically possible to
combine phones from different vocal efforts in an utterance. The diphones
at the joints between different vocal effort stretches are taken from the
"loud" diphone set for medium-loud joints, from the "soft" diphone set for
medium-soft joints, and from the default diphone set for soft-loud joints.
That means, in 

_	10
z	91	(0,106)
a	72	(0,116)
6       40
b_loud	59
R_loud	51
Y_loud	77	(49,80)
k	108
@	97
n	66	(100,75)
_	400

the diphones used would be "_-z", "z-a", "a-6", "6_loud-b_loud",
"b_loud-R_loud", "R_loud-Y_loud", "Y_loud-"k_loud", "k-@", "@-n", and
"n-_".

Note there is only one symbol for silence, "_", and only one symbol for a
glottal stop, "?". No vocal-effort-specific versions of these phone symbols
exist.

3. Examples
===========

The TEST/ directory contains a number of .pho files, some of which are
taken from an early version of the "Socialite" demonstrator developed in
the NECA project. See http://www.ai.univie.ac.at/NECA for more information
about the project in general and the role of emotional speech synthesis in
the project. Some foreign language files are meant to demonstrate the
degree to which the voice can be used for speaking other languages with a
German accent.

4. Contact
==========

This diphone database was recorded jointly by the Institute of Phonetics at
Saarland University and by the Language Technology Department at DFKI,
Saarbrücken.

For any enquiries, contact Marc Schröder, schroed@dfki.de.
