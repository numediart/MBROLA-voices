  ##    ##########  ########
  ##        ##             ##
  ##        ##             ##
  ##        ##      ########
  ##        ##             ##
  ##        ##             ##
  ##        ##      ########  

release 0.1 - March 2001
--------------------------------------------------------------
IT3 - An Italian male voice for the MBROLA synthesizer

Created by :  IFD
              Istituto di Fonetica e Dialettologia
              Consiglio Nazionale delle Ricerche

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 Description of the IT3 diphone database
2.0 Installation and tests
3.0 Announcement
4.0 Acknowledgements

--------------------------------------------------------------
1.0 Description of the IT3 diphone database
--------------------------------------------------------------

IT3
An italian male voice for the MBROLA synthesiser
________________________________________________
release 0.1 - March 2001

IT3 is a diphone database for Italian, consisting of 1300
diphones, male voice.
The following phoneme symbols are assumed in our diphone  sets.

SYMBOL PRONOUNCED LIKE IN
       WORD    SAMPA

i	spinoso	s p i n o1 s o	
e	veloce	v e l o1 tS e 	
E	belpaese	b E l p a e1 z e	
a	vaiolo	v a j O1 l o	
o	polsino	p o l s i1 n o
O	norditalia	n O r d i t a1 l i a	
u	puntale	p u n t a1 l e 	
i1	così		k o s i1
e1	mercé		m e r tS e1	
E1	caffè		k a f f E1	
a1	bontà		b o n t a1	
o1	Roma		r o1 m a	
O1	però		p e r O1	
u1	più		p j u1	

j	piume		p j u1 m e
w	quando	k w a1 n d o	

p	pera		p e1 r a	
t	torre		t o1 r r e	
k	caldo		k a1 l d o	
b	botte		b o1 t t e	
d	dente		d E1 n t e	
g	gatto		g a1 t t o

f	faro		f a1 r o	
s	sole		s o1 l e	
S	sci		S i1	
v	via		v i1 a	
z	peso		p e1 s o	
Z	garage	g a r a1 Z	

ts	pizza		p i1 ts ts a	
tS	pece		p e1 tS e	
dz	zero		dz E1 r o	
dZ	magia		m a dZ i1 a	

m	mano		m a1 n o	
n	nave		n a1 v e	
J	legna		l e1 J J a	
nf	anfora	a1 nf f o r a	
ng	ingordo	i ng g o1 r d o	

l	palo		p a1 l o	
L	soglia	s O1 L L a	
r	remo		r E1 m o	

_	PAUSE   


--------------------------------------------------------------
2.0 Installation and Tests
--------------------------------------------------------------

If you have not copied the MBROLA software yet, please consult
the MBROLA project homepage and get it.

Copy it3.zip into the mbrola directory and unzip it : 

   unzip it3.zip (or pkunzip on PC/DOS)

Try 

   mbrola it3 TEST/sent1.pho test1.wav
   mbrola it3 TEST/sent2.pho test2.wav

to create two sound files for a short info. In these examples the audio
files follows the RIFF Wave format. But
depending on the extension test.au,  test.aif, or test.raw other file
formats can be obtained. Listen to it with your favorite sound editor,
and try the other command files (*.pho) to have a  better idea of the
quality of speech that can be synthesized with MBROLA and the it3
database.

On Unix systems you can pipe the audio ouput to the sound player as
on a HP : mbrola it3 sent1.pho - | splayer -srate 16000 -l16

Also refer to the readme.txt file provided with the mbrola software
for using it. 

--------------------------------------------------------------
3.0 Announcement
--------------------------------------------------------------

This database is a beta release, and we will take your comments into
account for future updates. Updates will be announced on the
mbrola-interrest mailing list.

For more information and demos, consult the IFD home page at: 

     http://nts.csrf.pd.cnr.it

and the Italian MBROLA page at

     http://nts.csrf.pd.cnr.it/IFD/Pages/Italian-TTS-MBROLA.htm

--------------------------------------------------------------
4.0 Acknowledgments
--------------------------------------------------------------

We would like to thank Graziano Tisato and Fabio Tesser for
their efforts in helping IFD to collect and develop this
database.

--------------------------------------------------------------
IFD
Istituto di Fonetica e Dialettologia
Consiglio Nazionale delle Ricerche
Via G. Anghinoni, 10
35121 Padova (Italy)

Tel: +39 049 8274418
Fax: +39 049 8274416
Email: cosi@csrf.pd.cnr.it
WWW: http://nts.csrf.pd.cnr.it/Ifd
--------------------------------------------------------------


Contact:
--------------------------------------------------------------
Piero Cosi
e-mail:	cosi@csrf.pd.cnr.it
www:		http://nts.csrf.pd.cnr.it/IFD/Pages/piero.htm
Tel:		+39 049 8274413
Fax:		+39 049 8274416

Istituto di Fonetica e Dialettologia del C.N.R.
Via G.Anghinoni, 10 - 35121 Padova
--------------------------------------------------------------
