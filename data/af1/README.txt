--------------------------------------------------------------
AF1 - An Afrikaans male voice for the MBROLA synthesizer

Created by :    Daan Wissing 
                ntldpw@puk.ac.za	
              
-------------------------------------------------------
Table of Contents
-------------------------------------------------------
1. Description of Af1 database    
	a. SAMPA phonetic alphabet
2. Distribution and test
3. Acknowledgments

-------------------------------------------------------
1. Brief description of AF1 database
-------------------------------------------------------
AF1 is an Afrikaans male diphone database provided in the
context of the MBROLA project (https://github.com/numediart/MBROLA/).

It consists of 950 diphones.Only actually permissable combinations were taken into account.

We use the SAMPA phonetic alphabet for Text-to-Speech systems, and in developing a grapheme-to-phoneme converter for Afrikaans. For the SAMPA symbol set, as well as examples for each, cf. (http://www.phon.ucl.ac.uk/home/sampa/afrikaans-draft.htm). In the case of the primary diphthongs we made alternations: [@I] has been substituted by [&], [9y] by [}], and [9u] by [$]. 

AF1 database was recorded, segmented and processed by 
Daan Wissing (ntldpw@puk.ac.za), in the Human Language Technology Laboratory 
of the Faculty of Arts, North-West University, Potchefstroom Campus, South Africa. 

		SAMPA PHONETIC | AFRIKAANS WORD   | (AFRIKAANS GLOSS) | ENGLISH GLOSS
		SYMBOLS 	 (TRANSCRIBED) 	
CONSONANTS				
PLOSIVES				
		p			pAp		pap		porridge
		b			bAs		bas		bass
		t			tOt		tot		till
		d			dAx		dag		day
		k			kAt		kat		cat
		g			gOlf		gholf		golf
				
FRICATIVES				
		f			fEl		vel		hide
		v			vAt		wat		what
		s			sos		soos		sauce
		z			zulu		Zulu		Zulu
		S			SAmpu		sjampoe		shampoo
		Z			Zanr@		genre		genre
		x			xAt		gat		hole
		h			hAnt		hand		hand
		j			jar		jaar		year
				
NASALS				
		m			mAn		man		man
		n			nEt		net		only
		N			bAN		bang		afraid
				
LIQUIDS				
Lateral 	l			lAx		lag		laugh
Trill		r			rar		raar		odd

Glottal pulse	?			?Axt		agt		eight
				
SEMIVOWELS				
		j			jar		jaar		year
		w			twe		twee		two
		h			hAk		haak		hook
				
VOWELS				
FREE VOWELS				
		i			sin		sien		see
		e			met		meet		measure
		a			mar		maar		but
		u			suk		soek		seek
		o			?or		oor		ear
		y			fyr		vuur		fire
		2			mys2m		museum		museum
				
CHECKED VOWELS				
		E			pEn		pen		pen
		A			pAs		pas		fit
		O			pOl		pol		tuft
		@			p@t		pit		pip
		9			p9t		put		well
				
PRIMARY DIPHTHONGS				
		&			p&l		pyl		arrow
		$			b$		bou		build
		}			h}s		huis		house

REMARKS: 
Some of these symbols are different from that used in SAMPA for Afrikaans on the Web (http://www.phon.ucl.ac.uk/home/sampa/afrikaans-draft.htm): Long vowels are not indicated here by using a colon (e.g. [e:]); the symbols [& $ }] for diphthongs substitute respectively [@I 9u 9y].
[h] and [j] are sometimes treated as fricatives, sometimes as semivowels.


---------------------------------------------------------
2. Distribution and test
---------------------------------------------------------
If you have not copied the MBROLA software yet, please consult
the MBROLA project homepage (https://github.com/numediart/MBROLA/).
Refer to the readme.txt file provided with the mbrola software
for using it. 

This distribution of MBROLA database contains the following files:
AF1	        :the AF1 MBROLA database
AF1.txt		:this file  
test\*.pho	:pho examples 

----------------------------------------------------------
3. Acknowledgments
----------------------------------------------------------
I would like to specially thank 
Annick van Dijkhorst for her enthusiastic cooperation and interest in the project, 
Kjell Gustafson (KTH, Stockholm) for expert help and very kind support
and 
Baris Bozkurt of the MBROLA team for his constant and prompt help and support when building this database and his efforts on the mbrolization of the diphones.
Daan Wissing (ntldpw@puk.ac.za), 
Human Language Technology Laboratory 
Faculty of Arts, North-West University
Potchefstroom Campus
South Africa
