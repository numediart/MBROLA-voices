#    # #   #    #
#    # #   #   ## 
#    # #   #  # #
###### #   # #  #
#    # #   #    #
#    # #   #    # 
#    #  ###     #
 
release 2

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 A brief description of the HU1 database
2.0 Distribution
3.0 Installation, and tests
4.0 Acknowledgments

--------------------------------------------------------------
1.0 A brief description of HU1
--------------------------------------------------------------
HU1 1.002 equalized release is a Hungarian diphone database provided in
the context of the MBROLA project (see
https://github.com/numediart/MBROLA/).

It provides a Hungarian female voice to be used with the MBROLA program.

Input files use the SAMPA (SAM Phonetic Alphabet) notation as
recommended by the EEC-SAM Project, (http://www.phon.ucl.ac.uk/home/sampa/hung-uni.htm) but with some minor changes,as indicated. The following is derived from SAMPA for Spanish (J.C.Wells, UCL,London and Klára Vicsi, vicsi@ttt-202.ttt.bme.hu).

SAMPA	EXAMPLE		TRANSCRIPTION
   i		hit			 hit
	i:		szít			 si:t
	E		vet			 vEt
	e:		méz			 me:z
	O 		hat			 hOt
	a:		láb			 la:b
	o		sok			 Sok
	o:		pók			 po:k
	2		köt			 k2t
	2:		sõt 			 S2:t
	u		fut			 fut
	u:		kút			 ku:t
	y		süt			 Syt
	y:		fût 			 fy:t


   p		Pál			 pa:l
	b		bál			 ba:l
	t		tár			 ta:r
	d		dán			 da:n
	t'		tyúk			 t'u:k
	d'		gyár			 d'a:r
	k		kád			 ka:d
	g		gát			 ga:t
	ts		cél			 tse:l
	dz		bodza			 bodza
	tS		csõ 			 tS2:
	dZ		dzsem			 dZEm
	f		fát			 fa:t
	v		vád			 va:d
	s		szép			 se:p
	z		zár			 za:r
	S		só			    So:
	Z		zsír			 Zi:r
	m		már			 ma:r
	n		nád			 na:d
	J		nyom			 Jom
	r		rák			 ra:k
	l		láp			 la:p
	j		jön, lyuk	 j2n, juk
	h		hát			 ha:t
	x		achát			 Oxa:t
	
_		silence	

Limitations:
-----------
A matrix provided suffers from some limitations that we hope to
eliminate in future versions. 

The following are the original Sampa definitions left out.
for the phoneme /h/:
	x		doh			   dox
	x		ihlet			   ixlEt
	h\		lehet			   lEh\Et

for the phoneme /j/:
	x'		kapj			   kOpx'

for the phonemes /m, n/
	F		kámfor			ka:Ffor
			hamvas			hOFvOS
			honvágy			hoFva:d'
			honfitárs		hoFfita:rS
	N		ing			   iNg
			tönk			   t2Nk


--------------------------------------------------------------
2.0 Distribution
--------------------------------------------------------------

This distribution of mbrola contains the following files : 

   hu1      : the database itself
   hu1.txt  : This file
   license.txt : must read before using the database
    
and a TEST directory containing .PHO files. Some of the .PHO
files are automatically generates, some copy natural prosody.

Additional languages and voices, as well as other example command
files, are or will be available in the context of the MBROLA 
project. Please consult the MBROLA project homepage :
   https://github.com/numediart/MBROLA/

Registered users will automatically be notified of the availability 
of new databases. To freely register, simply send an email to 
mbrola-interest-request@tcts.fpms.ac.be with the word 'subscribe'
in the message title.

--------------------------------------------------------------
3.0 Installation and Tests
--------------------------------------------------------------

If you have not copied the MBROLA software yet, please consult
the MBROLA project homepage and get it.

Copy hu1.zip into the mbrola directory and unzip it : 

   unzip hu1.zip (or pkunzip on PC/DOS)
   (don't forget to delete the .zip file when this is done)

Try 

   mbrola hu1 TEST/kisk1.pho kisk1.wav
	play kisk1.wav

to create a sound file. In this example the audio file follows 
the RIFF Wav format. But depending on the extension test.au, test.aif, 
or test.raw you can obtain other file formats. Listen to it with your 
favorite sound editor, and try other command files (*.pho) to have 
a better idea of the quality of speech you can synthesize with the 
MBROLA technique.

On Unix systems you can pipe the audio ouput to the sound player as
on a HP : mbrola hu1 test.pho - | splayer -srate 16000 -l16

Also refer to the readme.txt file provided with the mbrola 
software for using it.

--------------------------------------------------------------
4.0 Acknowledgements
--------------------------------------------------------------

We would like to thank Vincent Pagel and
Thierry Dutoit for their work in preparing the database.

--------------------------------------------------------------

Eleonora (eleonora45@gmx.net)

e-mail: eleonora45@gmx.net, for questions concerning the 
database hu1.

e-mail: mbrola@tcts.fpms.ac.be, for general information, 
questions on the installation of software and databases.
