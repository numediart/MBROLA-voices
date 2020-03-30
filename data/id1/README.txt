Id1 Database 
Release 1

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 A brief description of the ID1 database
2.0 Distribution
3.0 Installation, and tests
4.0 Acknowledgments

--------------------------------------------------------------
1.0 A Brief Description of ID1
--------------------------------------------------------------
ID1 is a Indonesian diphone database provided in the
context of the MBROLA project
(see https://github.com/numediart/MBROLA/).

It provides a Indonesian male voice to be used with the MBROLA program.

List of phoneme available :

PHONEME 	EXAMPLE		SAMPA EQUIVALENT
p		apa		p
b		abang		b
t		atap		t
d		tadi		d
k		akan		k
g		gila		g

c		cari		tS
j		jadi		dZ
f		kafan		f
s		kasar		s
z		zebra		z
h		hitam		h

m		aman		m
n		anda		n
ng		angka		N
r		armada		r
l		alamat		l
w		bawa		w
y		bahaya		j
ny		kenyang		nY

a		bapa		V
e		petang		@
e		medan		e
i		bila		I
o		mohon		Q
u		bukan		U

ai		santai		aI
oi		amboi		OI
au		lampau		aU




_		silence	


--------------------------------------------------------------
2.0 Distribution
--------------------------------------------------------------

This distribution of mbrola contains the following files : 

   id1      : the database itself
   id1.txt  : This file
   license.txt : must read before using the database
   
   indo1.pho: sample pho files

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

Copy id1.zip into the mbrola directory and unzip it : 

   unzip id1.zip (or pkunzip on PC/DOS)
   (don't forget to delete the .zip file when this is done)

Try 

   mbrola indo1.pho


to create a sound file. In this example the audio file follows 
the RIFF Wav format. But depending on the extension test.au, test.aif, 
or test.raw you can obtain other file formats. Listen to it with your 
favorite sound editor, and try other command files (*.pho) to have 
a better idea of the quality of speech you can synthesize with the 
MBROLA technique.

On Unix systems you can pipe the audio ouput to the sound player as
on a HP : mbrola br2 1.pho - | splayer -srate 22050 -l16

Also refer to the readme.txt file provided with the mbrola 
software for using it.

--------------------------------------------------------------
4.0 Acknowledgements
--------------------------------------------------------------

I would like to Thierry Dutoit to let me work in TCTS Lab in Mons, Belgium.
Thanks also for everyone in TCTS Lab for nice working environment.

Thanks also to LIPPO-Indonesia for sponsoring me to go to Belgium.

--------------------------------------------------------------
Mons, Belgium
Arry Akhmad Arman
Lecturer/Researcher from Institut Teknologi Bandung
Bandung - Indonesia

e-mail: aa@lss.ee.itb.ac.id, for questions concerning the 
database id1.

e-mail: mbrola@tcts.fpms.ac.be, for general information, 
questions on the installation of software and databases.
