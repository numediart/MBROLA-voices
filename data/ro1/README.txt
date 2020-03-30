######  #######    #
#     # #     #   ##
#     # #     #  # #
######  #     #    #
#   #   #     #    #
#    #  #     #    #
#     # #######  #####
 
release 1.00

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 A brief description of the RO1 database
2.0 Distribution
3.0 Installation, and tests

--------------------------------------------------------------
1.0 A brief description of RO1
--------------------------------------------------------------
RO1 2.020 release is a Romanian diphone database provided in the
context of the MBROLA project
(see https://github.com/numediart/MBROLA/).

It provides a Romanian male voice to be used with the MBROLA program.

Input files use the SAMPA (SAM Phonetic Alphabet) notation as
recommended by the EEC-SAM Project. 

--------------------------------------------------------------
2.0 Distribution
--------------------------------------------------------------

This distribution of mbrola contains the following files : 

   ro1        : the database itself
   ro1.txt    : This file
   license.txt: To read before any use
    
and a TEST directory containing .PHO files

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

Copy ro1.zip into the mbrola directory and unzip it : 

   unzip ro1.zip (or pkunzip on PC/DOS)
   (don't forget to delete the .zip file when this is done)

Try 

   mbrola ro1 TEST/bonjour.pho test.wav

to create a sound file. In this example the audio file follows 
the RIFF Wav format. But depending on the extension test.au, test.aif, 
or test.raw you can obtain other file formats. Listen to it with your 
favorite sound editor, and try other command files (*.pho) to have 
a better idea of the quality of speech you can synthesize with the 
MBROLA technique.

On Unix systems you can pipe the audio ouput to the sound player as
on a HP : mbrola ro1 test.pho - | splayer -srate 16000 -l16

Also refer to the readme.txt file provided with the mbrola 
software for using it.

Dr Marian Boldea

Computer Science Department
"Politechnica" university
Blvd V. Parvan 2
1900 TIMISOARA
ROMANIA

e-mail: boldea@utt.ro , for
questions concerning the database ro1.

e-mail: mbrola@tcts.fpms.ac.be, for general information, 
questions on the installation of software and databases.
