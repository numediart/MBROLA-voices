 SSSSS   W     W     1
S     S  W  W  W    11
S        W  W  W   1 1
 SSSSS   W  W  W     1
      S  W  W  W     1
S     S  W  W  W     1
 SSSSS    WW WW    11111

Release 1.00
--------------------------------------------------------------
SW1-Lukas voice, a Swedish male voice for the MBROLA synthesizer

Created  by Marcus  Filipsson  and Gösta Bruce   of the  Department of
Linguistics and Phonetics of Lund University, Sweden.

------------------------------------------------------------
1.0 A brief description of SW1
------------------------------------------------------------

SW1 1.00 release is a Swedish diphone database provided in the context
of the MBROLA project :

   http://tcts.fpms.ac.be/synthesis/mbrola.html

It provides a Swedish male voice  (known as "Lukas") to be used with
the MBROLA program.

Input files  use  the SAMPA  phonetic notation,  as adopted  in other
MBROLA databases. Below is  a list of the 49 Swedish speech sounds it
accounts for, with examples. 

Symbol	Word	Transcription

p	spil	spi:l
b	bil	bi:l
t	stal	stA:l
d	dal	dA:l
k	skal	skA:l
g	gås	go:s
f	fil	fi:l
v	vår	vo:r
s	sil	si:l
S	sjuk	S}:k
h	hal	hA:l
C	tjock	COk
m	mil	mi:l
n	nål	no:l
N	ring	rIN
r	ris	ri:s
l	lös	l2:s
j	jag	jA:g
i:	vit	vi:t
e:	vet	ve:t
E:	säl	sE:l
y:	syl	sy:l
}:	hus	h}:s
2:	föl	f2:l
u:	sol	su:l
o:	hål	ho:l
A:	hal	hA:l
I	vitt	vIt
e	vett	vet
Y	bytt	bYt
u0	buss	bu0s
2	föll	f2l
U	bott	bUt
O	håll	hOl
a	hall	hal
{:	här	h{:r	pre-r allophone of E:
9:	för	f9:r		"	   2:
{	herr	h{r		"	   e
9	förr	f9r		"	   2
@	pojken	pOjk@n  schwa vowel allophone
rt	hjort	jUrt	retroflex consonant
rd	bord	bu:rd		"
rn	barn	bA:rn		"
rs	fors	fOrs		"
rl	karl	kA:rl		"
ph	pil	pi:l	aspirated p
th	tal	tA:l	aspirated t
kh	kal	kA:l	aspirated k
rh	portal	pUrhA:l	aspirated rt


Limitations:
-----------
Not  all of  the 49x49 +  49 initial  + 49 final  =  2499 diphones are
available.   Many    of them  are     more   or  less  phonotactically
impossible. This includes initial retroflex sounds, aspirated plosives
before consonanants, initial schwa and others. To keep the size of the
database  down, these  have not  been  recorded, and will  generate an
error  if  entered into  a pho-file.   In the  end  2059 diphones were
recorded. Below is a list of the 440 excluded diphones. 

2-rd	 9:-2:	  N-N	   j-N	    n-rl     rh-h     th-k     {-p
2-rh	 9:-9	  N-rd	   j-rd	    n-rn     rh-j     th-kh    {-ph
2-rl	 9:-9:	  N-rh	   j-rh	    n-rt     rh-k     th-l     {-s
2-rn	 9:-@	  N-rl	   j-rl	    p-N	     rh-kh    th-m     {-t
2-rt	 9:-A:	  N-rn	   j-rn	    p-rd     rh-l     th-n     {-th
2:-rd	 9:-C	  N-rt	   j-rt	    p-rh     rh-m     th-p     {-u0
2:-rh	 9:-E:	  S-N	   k-N	    p-rl     rh-n     th-ph    {-u:
2:-rl	 9:-I	  S-rd	   k-rd	    p-rn     rh-p     th-r     {-v
2:-rn	 9:-N	  S-rh	   k-rh	    p-rt     rh-ph    th-rd    {-y:
2:-rt	 9:-O	  S-rl	   k-rl	    ph-C     rh-r     th-rh    {-{
9-2	 9:-S	  S-rn	   k-rn	    ph-N     rh-rd    th-rl    {-{:
9-2:	 9:-U	  S-rt	   k-rt	    ph-S     rh-rh    th-rn    {-}:
9-9	 9:-Y	  Y-rd	   kh-C	    ph-_     rh-rl    th-rs    {:-2
9-9:	 9:-_	  Y-rl	   kh-N	    ph-b     rh-rn    th-rt    {:-2:
9-@	 9:-a	  Y-rn	   kh-S	    ph-d     rh-rs    th-s     {:-9
9-A:	 9:-b	  _-N	   kh-_	    ph-f     rh-rt    th-t     {:-9:
9-C	 9:-d	  _-rd	   kh-b	    ph-g     rh-s     th-th    {:-@
9-E:	 9:-e	  _-rh	   kh-d	    ph-h     rh-t     th-v     {:-A:
9-I	 9:-e:	  _-rl	   kh-f	    ph-j     rh-th    v-N      {:-C
9-N	 9:-f	  _-rn	   kh-g	    ph-k     rh-v     v-rd     {:-E:
9-O	 9:-g	  _-rt	   kh-h	    ph-kh    rl-N     v-rh     {:-I
9-S	 9:-h	  b-N	   kh-j	    ph-l     rl-rd    v-rl     {:-N
9-U	 9:-i:	  b-rd	   kh-k	    ph-m     rl-rh    v-rn     {:-O
9-Y	 9:-j	  b-rh	   kh-kh    ph-n     rl-rl    v-rt     {:-S
9-_	 9:-k	  b-rl	   kh-l	    ph-p     rl-rn    {-2      {:-U
9-a	 9:-kh	  b-rn	   kh-m	    ph-ph    rl-rt    {-2:     {:-Y
9-b	 9:-l	  b-rt	   kh-n	    ph-r     rn-N     {-9      {:-_
9-d	 9:-m	  d-N	   kh-p	    ph-rd    rn-rn    {-9:     {:-a
9-e	 9:-n	  d-rd	   kh-ph    ph-rh    rs-N     {-@      {:-b
9-e:	 9:-o:	  d-rh	   kh-r	    ph-rl    rt-N     {-A:     {:-d
9-f	 9:-p	  d-rl	   kh-rd    ph-rn    rt-rd    {-C      {:-e
9-g	 9:-ph	  d-rn	   kh-rh    ph-rs    rt-rh    {-E:     {:-e:
9-h	 9:-s	  d-rt	   kh-rl    ph-rt    rt-rt    {-I      {:-f
9-i:	 9:-t	  e-rh	   kh-rn    ph-s     s-N      {-N      {:-g
9-j	 9:-th	  e-rt	   kh-rs    ph-t     s-rd     {-O      {:-h
9-k	 9:-u0	  f-N	   kh-rt    ph-th    s-rh     {-S      {:-i:
9-kh	 9:-u:	  f-rd	   kh-s	    ph-v     s-rl     {-U      {:-j
9-l	 9:-v	  f-rh	   kh-t	    r-N	     s-rn     {-Y      {:-k
9-m	 9:-y:	  f-rl	   kh-th    r-rd     s-rt     {-_      {:-kh
9-n	 9:-{	  f-rn	   kh-v	    r-rh     t-N      {-a      {:-l
9-o:	 9:-{:	  f-rt	   l-N	    r-rl     t-rd     {-b      {:-m
9-p	 9:-}:	  g-N	   l-rd	    r-rn     t-rh     {-d      {:-n
9-ph	 @-N	  g-rd	   l-rh	    r-rt     t-rl     {-e      {:-o:
9-rl	 C-N	  g-rh	   l-rl	    rd-N     t-rn     {-e:     {:-p
9-s	 C-rd	  g-rl	   l-rn	    rd-rd    t-rt     {-f      {:-ph
9-t	 C-rh	  g-rn	   l-rt	    rd-rh    th-C     {-g      {:-s
9-th	 C-rl	  g-rt	   m-N	    rd-rt    th-N     {-h      {:-t
9-u0	 C-rn	  h-N	   m-rd	    rh-C     th-S     {-i:     {:-th
9-u:	 C-rt	  h-rd	   m-rh	    rh-N     th-_     {-j      {:-u0
9-v	 E:-rd	  h-rh	   m-rl	    rh-S     th-b     {-k      {:-u:
9-y:	 E:-rh	  h-rl	   m-rn	    rh-_     th-d     {-kh     {:-v
9-{	 E:-rl	  h-rn	   m-rt	    rh-b     th-f     {-l      {:-y:
9-{:	 E:-rn	  h-rt	   n-N	    rh-d     th-g     {-m      {:-{
9-}:	 E:-rt	  i:-rh	   n-rd	    rh-f     th-h     {-n      {:-{:
9:-2	 I-rn	  i:-rt	   n-rh	    rh-g     th-j     {-o:     {:-}:


------------------------------------------------------------
2.0 Distribution
------------------------------------------------------------

This distribution of mbrola contains the following files :

sw1         : the database itself
sw1.txt     : this file
license.txt : must read before using the database

TEST        : a directory containing the following examples ->
				  lukas.pho:	introduction to this database
				  lukas2.pho:	a short sentence

Additional  languages and voices, as well as  other  example
command  files, are or will be available in the  context  of
the  MBROLA  project.  Please  consult  the  MBROLA  project
homepage :

   http://tcts.fpms.ac.be/synthesis

Registered  users  will automatically  be  notified  of  the
availability  of  new databases. To freely register,  simply
send  an  email  to  mbrola-interest-request@tcts.fpms.ac.be
with the word 'subscribe' in the message title.

------------------------------------------------------------
4.0 Acknowledgments
------------------------------------------------------------

We  would  like  to  thank Merle Horne, Johan Frid, Mechtild Tronnier,
and many others  at the Department of  Linguistics and Phonetics, Lund
University for their support. 

Look at:
        http://www.ling.lu.se

for more information, and for contact info on the persons mentioned in
this document.

(Other possible uses of the mbrola speech synthesizer  within complete
TTS systems are listed at : 

   http://tcts.fpms.ac.be/synthesis/mbrtts.html)


--------------------------------------------------------------
		  Marcus Filipsson
		  Gösta Bruce
		  Department of Linguistics and Phonetics
		  Helgonabacken 12
		  Lund University
		  223 62 Lund
		  SWEDEN
		  http://www.ling.lu.se
