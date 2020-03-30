 GGGGG       RRRRR         1111
GG    G     R     R       11 11
G           R     R      11  11
G           R     R     11   11
G   GGGGG   RRRRRR           11
G      GG   R    R           11
G     GG    R     R          11
GG   GG     R      R         11
 GGGGG      R       R   release 1.01

-------------------------------------------------------
Table of Contents
-------------------------------------------------------
1. Brief description of GR1 database
    a.SAMPA examples
    b.Special features
    c.Limitations
2. Distribution
3. Diphones included
4. Acknowledgments

-------------------------------------------------------
1. Brief description of GR1 database
-------------------------------------------------------
GR1 1.00 release is a Hellenic diphone database provided in the
context of the MBROLA project (https://github.com/numediart/MBROLA/).

It provides a Greek male voice to be used with the MBROLA program.

Input  files   use the SAMPA   (SAM   Phonetic  Alphabet) notation  as
recommended by the EEC-SAM Project. Here is a list of the Greek speech
sounds  it accounts for, with examples.   [ASCII ISO8859-1 encode; use
ASCII editor to see it correctly] 

a. SAMPA examples
--------------------------------------------------------
SAMPA	Example (othographic)	GR1-Mbroli player transcription

_	(silence)		_
a	Asteri			asteri
o	Oreos			oreos
u	Ute			ute
e	Elato			elato
i	Ippeas			ipeas

p	PaPas			papas
b	Belas			belas
t	Tipos			tipos
d	Dimenos			dimenos
k	Kamenos			kamenos
c	paKeto,Kima		paceto,cima
g	Garizo			garizo
gj	aGGelos,Ginia		angjelos,gjinja

ts	TSatismenos		tsatizmenos
dz	aTZamis			adzamis

v	Varkaris		varkaris
D	aTHerfos,THelfini	aDerfos,Delfini
f	Fotia,fasi		fotja,fasi
x	Xoros			xoros
C	Xeri,Xina		Ceri,Cina
T	THalassa		Talasa
G	Gala,Gamos		Gala,Gamos
jj	Giorti,Gios		jjorti,jjos
z	Zalismenos		zalizmenos

r	Rota,Roga		rota,roGa

l	allos,Logariasmos	alos,loGarjazmos

m	Minas			minas
n	Niki,Nikos		nici,nikos

j	elIa,idIos,ennIa	elja,iDjos,enja

Only rudimentary implemented:
n (as an Allophone) in cases such as
	aggelos,feggari		angjelos,fengari

b. Special Features
--------------------------------------------------------
Please note:
All  diphthongs  are covered. Special  treatment   has been given  to
(excessive) diphthongs like in 'piato','niata','diafora' 
                                 (=pjato ,=njata ,=Djafora)
where acoustic representation   (phone)  of /i/  depends on   previous
consonant, when phonemic represantation ('j') is kept the same.  

Consonant "mishaps" (exceptions)  have been  taken into account.   So,
don't expect   diphones like /sv/,/sG/  : they   have been replaced by
/zv/,/zG/    respectively. For  example  we  write  'asvestis' but  we
pronnounce /azvestis/. Read table.xls for  a complete list of included
diphones.

For best synthesis results  it is recommended  to avoid pauses between
words, so inter-word phone combinations have been included.

c. Limitation
---------------------------------------------------------
Notice that not all diphones are possible (C-n for example)

Inter-word phone  combinations, which can be  found due  to the use of
foreign words in Greek vocabulary  and may not  be included in the db,
can   be replaced by   'phone1'+pause+'phone2'.   That's why  most  of
'phone'+silence, silence+'phone' combinations have been included. Read
table.xls for a complete list of included diphones.

/mb/  diphone is NOT included because  of inattention. Replace it with
/b/. Next release of GR1 WILL include it.
/is/ diphone seems having metamorphosed to /us/. 

We apologize  for the mistakes. Next  release of GR1 WILL correct each
of them.

---------------------------------------------------------
2. Distribution
---------------------------------------------------------
This distribution of mbrola db contains the following files:
  gr1	  :the MBROLA database
  gr1.txt	  :this file
  table.xls : a MS-Excel (WIN 95, ver.7) table 
                         with all GR1 diphones.
  .PHO examples in TEST directory

Additional languages and voices, as well as other example command
files, are or will be available in the context of the MBROLA
project. Please consult the MBROLA project homepage : 
   https://github.com/numediart/MBROLA/

Registered users will automatically be notified of the availability of
new  databases.   To  freely   register, simply   send   an email   to
mbrola-interest-request@tcts.fpms.ac.be with   the word 'subscribe' in
the message title. 

----------------------------------------------------------
3. Diphones Included
----------------------------------------------------------

All diphones included can be found in Table.xls

----------------------------------------------------------
4. Acknowledgments
----------------------------------------------------------
We would like to thank our associable speaker, A.Yiamalis, for his
constant pitch (around 100 Hz).

We   appreciate the  help of  people  at  Electroacoustics Lab  of our
department, where  recordings were made.

Finally, we would like to thank   Thierry Dutoit and Vincent Pagel for
their help in building an efficient version of this database. 

Aggelos Bletsas
email:ample@egnatia.ee.auth.gr

Dr George Sergiadis
email:sergiadi@vergina.eng.auth.gr
tel:	++3-31-996314
fax:	++3-31-996312

MRI Lab-Telecommunication Lab
Electrical Engineering Department
Aristotle University of Thessaloniki
