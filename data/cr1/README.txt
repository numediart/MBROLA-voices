CR1
--------------------------------------------------------------------------
Croatian male voice for the MBROLA speech synthesizer

Copyright (C) 1998 by Juraj Bakran and Nikolaj Lazic, University of Zagreb 
--------------------------------------------------------------------------
Table of Contents
--------------------------------------------------------------------------

1.0 Description of CR1
2.0 Distribution
3.0 Installation, and tests
4.0 Acknowledgments

--------------------------------------------------------------------------
1.0 Description of  CR1
--------------------------------------------------------------------------

CR1 is first version of a diphone database for Croatian. It includes 930
diphones.

The following phoneme symbols are assumed in our diphone set: 

Note: This set uses the SAMPA notation for Croatian. In the representation
      of Croatian orthography shown below, 

   * c' stands for c with an acute accent;
   * d' stands for a barred d;
   * c^ s^ z^ stand for c s z with a wedge accent (hacek).


Vowels. There are five vowels in Croatian. Additionally, r can function as
a vowel.

SAMPA symbol    Orthography     Transcription    Gloss

i               sir             "sir <F>         cheese

e               pet             "pe:t <F>        five
						 
a               sat             "sa:t <F>        watch

o               bol             "bo:l <F>        pain

u               put             "pu:t <F>        way

r               prst            "prst <F>        finger

Consonants. The Croatian consonant system comprises 17 obstruents and 7
sonorant phonemes.

SAMPA symbol    Orthography     Transcription    Gloss

p               pas             "pas <F>         dog

b               bas             "bas <F>         base

t               tip             "ti:p <F>        type

d               dan             "da:n <F>        day

k               kap             "ka:p <F>        drop

g               gol             "go:l <F>        naked

ts              cura            "tsura <F>       girl

tS              c^ar            "tSa:r <F>       thrill

dZ              dz^ep           "dZep  <F>       pocket

tS'             noc'            "no:tS'<F>       night

dZ'             d'ak            "dZ'a:k <F>      pupil

f               fonetika        fo"netika<R>     phonetics

s               sat             "sa:t <F>        hour

z               zid             "zi:d <F>        wall

S               s^ef            "Se:f <F>        chief

Z               z^ena           "Zena <R>        woman

x               hod             "xo:d <F>        walking

m               most            "mo:st <F>       bridge
						 
n               noga            "noga  <R>       leg

J               njiva           "Jiva  <F>       field

l               lud             "lu:d <F>        mad

L               ljut            "Lu:t <F>        bitter

r               ruka            "ru:ka <R>       hand

v               vid             "vi:d <F>        sight

j               ja              "ja: <F>         I

--------------------------------------------------------------------------
2.0 Distribution
--------------------------------------------------------------------------
This distribution of cr1.zip contains the following files : 

cr1             - Croatian male voice
cr1.txt         - this file

and a number of example .PHO files : 

brazilac.pho
kantica.pho     
zalostan.pho
naslov.pho
example.pho

Please consult the MBROLA project homepage :

   https://github.com/numediart/MBROLA/

Registered users will automatically be notified of the availability 
of new databases. To freely register, simply send an email to 
mbrola-interest-request@tcts.fpms.ac.be with the word 'subscribe'
in the message title.

--------------------------------------------------------------------------
3.0 Installation and Tests
--------------------------------------------------------------------------

If you have not copied the MBROLA software yet, please consult
the MBROLA project homepage and get it. Also refer to the readme.txt file
provided with the mbrola software for using it.

Copy cr1.zip into the mbrola directory and unzip it.

Try 

   mbrola cr1 zalostan.pho zalostan.wav

to create a sound file for the word /Zalostan/ (sad). Listen to it with
your favorite sound editor, and try the other command files (*.pho) to
have a better idea of the quality of speech that can be synthesized with
MBROLA and the cr1 database.

In the creation of new *.pho files, there is no need  to worry about
allophones. They are included in the database by allowing natural
assimilation in the course of pronunciation. You need simply write the
phonemic (SAMPA) transcription in the *.pho file.

--------------------------------------------------------------------------
4.0 Acknowledgments
--------------------------------------------------------------------------

The cr1 database was developed in Department of  Phonetics at University
of Zagreb.

We would like to thank Vincent Pagel for his efforts in converting our
diphone database to the MBROLA format and for all suggestions during the
construction and transfer of the database. Also, we would like to thank
to all students of phonetics who took part in the construction of the
database. 


July 1, 1998.

Juraj Bakran and Nikolaj Lazic

For more information contact: 

			juraj.bakran@ffzg.hr    or
			nikolaj.lazic@ffzg.hr 

or write to:
Department of Phonetics, I. Lucica 3, 10000 Zagreb, CROATIA 
--------------------------------------------------------------------------
