       #                 #      1. BRIEF DESCRIPTION OF THE DE2 DATABASE
       ###################      2. DISTRIBUTION
       ###################      3. INSTALLATION AND TESTING
       #                 #      4. CONTACT
       #                 #
       #                 #      1. --- BRIEF DESCRIPTION OF DE2 ---
       ##               ##
        #####       #####       DE2 (release 990106) is a diphone database
          #############         for German provided in the context of the
             #######            MBROLA project
       #                 #      (https://github.com/numediart/MBROLA/).
       ###################
       ###################      It provides a German male voice to be
       #         #       #      used with the MBROLA program.
       #         #       #
       #         #       #      Input files use the SAMPA (SAM Phonetic
       #        ####     #      Alphabet) notation as recommended by the
       #                 #      EEC-SAM Project. Here is a list of the
       ##               ##      German speech sounds it accounts for:
                                                                                
                                CONSONANTS:       VOWELS:
       ###              #                                                      
       ### ##            #      p  f  pf  m  l    i:  I  aI  E^ (= E~:)         
       ###   #           #      b  v  ts  n  R    y:  Y  aU  a^ (= a~:)         
       ###   ###         #      t  s  tS  N  6    e:  @  OY  o^ (= o~:)         
       ###    ###       ##      d  z         j    E:  E      E~                 
       ###     ##########       k  S              2:  9      a~                 
        ##       #######        g  Z              u:  U      o~                 
                                x                 o:  O                         
                                C                 a:  a                         
                                h          PAUSE: _                      
                                                                         
                                Please note:                                    
                                You can synthesize short closed vowels          
                                (e.g. [i, e, u, o]) using the                   
                                corresponding long vowels.                      
                                For glottal stops [?] a pause has to            
       #                 #      occur before the vowel.                         
       ###################      Limitations:                                    
       ###################      Notice that not all diphones are possible       
       #         #              in German. Impossible ones will trigger an      
       #         #              error message.                                  
       ###     ###                                                            
         #######                2. --- DISTRIBUTION ---                         
 #               #                                                             
 ##            ###              This distribution of mbrola contains the        
  ###      #######              following files :                               
      ########                     de2      : the database itself               
         ###                       de2.txt  : This file                         
             ### #              and an example .PHO file :  lautern.pho             
                 #                                                             
                                Additional languages and voices, as well as     
                                other example command files, are or will be     
                                available in the context of the MBROLA          
                                project. Please consult the MBROLA project      
                                homepage :                                      
                                   https://github.com/numediart/MBROLA/            
                                Registered users will automatically be notified 
                                of the availability of new databases. To freely 
       #                        register, simply send an email to               
       #                        mbrola-interest-request@tcts.fpms.ac.be         
       # ###                    with the word 'subscribe' in the message title. 
             ###                                                            
             #  ###             3. --- INSTALLATION AND TESTING ---             
             #       ##                                                            
             #    ########      If you have not copied the MBROLA software      
             ########           yet, please consult the MBROLA project          
       #  ########              homepage and get it.                            
       #######                  Copy de2.zip into the mbrola directory and      
       ###                      unzip it :                                      
       #                                                                  
                      ####       unzip de2.zip (or pkunzip on PC/DOS)           
                        ##                                                      
                         #      Try                                             
       #                 #         mbrola de2/de2 test/lautern.pho lautern.wav
       ###################      to create a sound file. In this example the     
       ###################      audio file follows the RIFF Wav format. But     
       #                 #      depending on the extension .au, .aif,     
                         #      or .raw you can obtain other file formats.   
                        ##      Listen to it with your favorite sound editor,   
                      ####      and try other command files (*.pho) to have     
                                a better idea of the quality of speech you      
       #                 #      can synthesize with the MBROLA technique.       
       ###################                                                      
       ###################      Use tts.pho as input-file if you want to listen
       #                 #      to an example created with ATIP's experimental TTS.
                                
       #                 #      On Unix systems you can pipe the audio output
       ###################      to the sound player as on a HP :
       ###################       mbrola de2/de2 lautern.pho - | splayer -srate 16000 -l16
       #         #       # 
                 #       #      Also refer to the readme.txt file provided with
                 ##      #      the mbrola software for using it.
                  #      # 
                  ########      4. - CONTACT -
                   ##### 
                              
										  ATIP GbR
                                Advanced Technologies for Information Processing
                                Waldstr. 20
                                D-61194 Niddatal
                                GERMANY  

										  http://www.atip.de    Tel.: (+49) (0)6187   292071
										  EMail: info@atip.de   Fax: (+49) (0)6187  292076

										  e-mail: mbrola@tcts.fpms.ac.be, for general
										  information, questions on the installation of
										  software and databases.
