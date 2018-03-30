#     #            1
#     #  #    #   11
#     #  ##   #  1 1
#######  # #  #    1
#     #  #  # #    1
#     #  #   ##    1
#     #  #    #  11111
release 4 - 17 September 1999
--------------------------------------------------------------
HN1 - Hanmal (Korean language) male voice for the MBROLA synthesizer

Created by :  Prof. KIM, Kyongsok/GIM, Gyeongseog

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 Description of the HN1 diphone database
2.0 Installation and tests
3.0 Contacts

--------------------------------------------------------------
1.0 Description of the HN1 diphone database
--------------------------------------------------------------

This  database consist of 1909  diphones.  The name for Hanmal diphone
database  is HN.  Since,  both South and  North   Koreas use  the same
language, it does not seem proper to use as  a database name KR, which
stands for South Korea only. 

Therefore,  we    will  use   HN,  abbreviated  from    Hanmal (Korean
Language). 'Han' stands for Korean and 'Mal' for Language. 

Note: According to  ISO  3166-1,  KR and  KOR   are for  South   Korea 
(Republic of Korea) and  KP and PRK  are  for North Korea  (Democratic
People's Republic of Korea). 

For  the   same reason as   in  4), we  will    use "Hanbando" (Korean
Penninsula) flag for HN  diphone database. The flag  was first used at
some   international   table  tennis game  in    1991  to  represent a
South-and-North-Koreas-unified team. The   flag is also being  used at
ships   which carries South Korean  tourists   going to Geumgangsan in
North Korea. The  flag shows the  whole Korean Penninsula, i.e.,  both
South and North Koreas. 

Software used for recording, labeling, etc: speech filing system (sfs)
developed at Department  of   Phonetics  and  Linguistics,  University
College London, London, U.K:

      http://www.phon.ucl.ac.uk/resource/sfs.html


SAMPA Description of Hanmal Romanization Symbols (1999.07.29, 10:00 KST)
 ------------------------------------------------
 
XSAMPA (Extended SAMPA) has been use to encode the database. Thanks to
the  mbrola renaming mechanism,  one  can use initialization files (or
Mbroli  renaming/mapping  tables)  to use an   alternative phoneme set
issued from romanization of  Hangeul  - MOE  1959 (Korean  Ministry of
Eduction, 1959 edition),  which is  nearly the  same as ISO  TR 11941:
Transliteration  of  Korean script (Method II   in case of Consonantal
lettres.)

 Consonants (Onset Position)
 ---------------------------
      Roman SAMPA Description
 
 101. g     k     velar lax plosive, voiceless
 102. gg    k_>   non-pulmonic velar ejective 
 103. n     n     alveolar nasal
 104. d     t     alveolar lax plosive, voiceless
 105. dd    t_>   non-pulmonic alveolar ejective
 106. r     4     alveolar tap
 107. m     m     bilabial nasal
 108. b     p     bilabial lax plosive, voiceless
 109. bb    p_>   non-pulmonic bilabial ejective 
 110. s     s     alveolar fricative, voicelss
 111. ss    s_>   non-pulmonic alveolar fricative ejective
 112. ngo   ??    ???
 113. j     ts\   alveolo-palatal lax affricate, voiceless
 114. jj    ts\_> non-pulmonic postalveolar affricate ejective
 115. ch    ts\_h postalveolar aspirated affricate, voiceless
 116. k     k_h   velar aspirated plosive, voiceless
 117. t     t_h   alveolar aspirated plosive, voiceless
 118. p     p_h   bilabial aspirated plosive, voiceless
 119. h     h     glottal fricative, voiceless
 120. gv    g     velar plosive, voiced
 121. dv    d     alveolar plosive, voiced
 122. bv    b     bilabial plosive, voiced
 123. jv    dz\   postalveolar affricate, voiced
 124. sh    s\    alveolo-palatal fricative, voiceless
 125. lo    l     alveolar lateral approximant


 Consonants (Coda Position)
 --------------------------
 
      Roman SAMPA Description
 
 301. gc    k_}   velar plosive, voiceless
 304. nc    n_}   alveolar nasal, no audible release
 307. dc    t_}   alveolar plosive, voiceless
 308. l     l_}   alveolar lateral approximant, no audible release
 316. mc    m_}   bilabial nasal, no audible release
 317. bc    p_}   bilabial plosive, voiceless
 321. ng    N     velar nasal
 
 Vowels
 ------
 
      Roman SAMPA Description
 
 201. a     a     open front unrounded, Cardinal 4
 202. ae    E     open-mid front unrounded, Cardinal 3
 203. ya    ja    palatal approximant + open front unrounded
 204. yae   jE    palatal approximant + open-mid front unrounded
 205. eo    V     open-mid back unrounded
 206. e     e     close-mid front unrounded, Cardinal 2
 207. yeo   jV    palatal approximant + open-mid back unrounded
 208. ye    je    palatal approximant + close-mid front unrounded
 209. o     o     close-mid back rounded, Cardinal 7
 210. wa    wa    voiced labial-velar approximant + open front unrounded
 211. wae   wE    voiced labial-velar approximant + open-mid front unrounded
 212. oe    2     close-mid front rounded
 213. yo    jo    palatal approximant + close-mid back rounded
 214. u     u     close back rounded, Cardinal 8
 215. weo   wV    voiced labial-velar approximant + open-mid back unrounded
 216. we    we    voiced labial-velar approximant + close-mid front unrounded
 217. wi    wi    voiced labial-velar approximant + close front unrounded
 218. yu    ju    palatal approximant + close back rounded
 219. eu    M     close back unrounded
 220. eui   M\i   velar approximant + close front unrounded
 221. i     i     close front unrounded, Cardinal 1

--------------------------------------------------------------
2.0 Installation and Tests
--------------------------------------------------------------

If  you  have  not copied   the MBROLA software   yet,  please consult
the MBROLA project homepage and get it:

                    http://tcts.fpms.ac.be/synthesis 

Copy hn1.zip into the mbrola directory and unzip it : 

   unzip hn1.zip (or pkunzip on PC/DOS)


On Unix, try:
------------
   mbrola hn1/hn1 hn1/TEST/s131.pho test.wav
  
If you want to use the romanize phoneme set:
   mbrola -I hn1/TEST/hn1roman hn1/hn1 hn1/TEST/s131roman.pho test.wav

It creates a short  sound file, RIFF Wave  format in this example. But
depending  on the extension test.au,  test.aif, or test.raw other file
formats can be obtained. Listen to it with your favorite sound editor,
and try the other command files  (*.pho) to have a  better idea of the
quality of speech that  can  be synthesized with   MBROLA and the  HN1
database.

On Unix  systems you can pipe  the audio ouput  to the sound player as
on a HP : mbrola hn1 TEST/s132.pho - | splayer -srate 16000 -l16

Also refer  to the readme.txt file provided  with  the mbrola software
for using it. 

On Windows:
----------
Once hn1 has been registered in Mbroli, simply double click on
TEST/s131.pho

If you want to use renamed phoneme set, you must initialize Mbroli's
diphone renaming/mapping with the file hn1roman.mbroli

--------------------------------------------------------------
3.0  Contacts:
--------------------------------------------------------------
 
 1) Prof. GIM, Gyeongseog/KIM, Kyongsok. 
    Internet: gimgs@asadal.cs.pusan.ac.kr
       http://asadal.cs.pusan.ac.kr/hangeul/ (Hangeul/Hanmal info.)
       http://asadal.cs.pusan.ac.kr/         (General info.)
     Phone: +82-51-510-2292 (office) or +82-51-947-6581 (home)
     Fax:   +82-51-515-2208
     Address: Division of Computer Science and Engineering
              College of Engineering, Busan National University
              BUSAN 609-735, South KOREA
 
   2) Mr. Chung, Hyunsong.  
     Internet: hchung@pitch.phon.ucl.ac.uk
       http://www.phon.ucl.ac.uk/home/hchung/home.htm
     Address: Department of Phonetics and Linguistics,
              University College London, London WC1E 6BT, U.K.
              TEL: +44 171 504 5026, FAX: +44 171 383 0752
