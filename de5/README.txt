
    1. BRIEF DESCRIPTION OF THE DE5 DATABASE
    2. DISTRIBUTION                                 
    3. INSTALLATION AND TESTING                     
    4. CONTACT                                      
                                              
    1. --- BRIEF DESCRIPTION OF DE5 ---             
                                              
    DE5 (release 1.0) is a diphone database        
    for German provided in the context of the       
    MBROLA project                                  
    (http://tcts.fpms.ac.be/synthesis/).            
                                                    
    It provides a German female voice to be           
    used with the MBROLA program.                   
                                              
    Input files use the SAMPA (SAM Phonetic         
    Alphabet) notation as recommended by the        
    EEC-SAM Project. Here is a list of the          
    German speech sounds it accounts for:           
                                                    
    CONSONANTS:       
                      
    p  f  pf  m  l    
    b  v  ts  n  R    
    t  s  tS  N  6    
    d  z         j    
    k  S              
    g  Z              
    x                 
    C                 
    h          

    VOWELS:                       
                              
    i:  I  aI  E^ (= E~:)         
    y:  Y  aU  a^ (= a~:)         
    e:  @  OY  o^ (= o~:)         
    E:  E      E~                 
    2:  9      a~                 
    u:  U      o~                 
    o:  O                         
    a:  a                         

    PAUSE: _

    ENGLISH SPEECH SOUNDS:
    w	    T	   D
                                             
    Please note:                                    
    You can synthesize short closed vowels          
    (e.g. [i, e, u, o]) using the                   
    corresponding long vowels.                      

    A glottal stop [?] will occur if a vowel
    is preceded by a pause.                         

    Limitations:                                    
    Notice that not all diphones are possible       
    in German. Impossible ones will probably 
    produce a distorted output.                                  
                                                  
    2. --- DISTRIBUTION ---                         
                                                   
    This distribution of DE5 contains the        
    following files :                               

       de5      : the database itself               
       de5.txt  : This file  
                       
    and the example .PHO file in the TEST directory :  
       de5test.pho
                                                   
    Additional languages and voices, as well as     
    other example command files, are or will be     
    available in the context of the MBROLA          
    project. Please consult the MBROLA project      
    homepage :                                      
       http://tcts.fpms.ac.be/synthesis/        
    
    Registered users will automatically be notified 
    of the availability of new databases. To freely 
    register, simply send an email to               
    mbrola-interest-request@tcts.fpms.ac.be         
    with the word 'subscribe' in the message title. 
                                                
    3. --- INSTALLATION AND TESTING ---             
                                                       
    If you have not copied the MBROLA software      
    yet, please consult the MBROLA project          
    homepage and get it.                            
    Copy de5.zip into the mbrola directory and      
    unzip it :                                      
                                              
     unzip de5.zip (or pkunzip on PC/DOS)           
                                                    
    Try :
           mbrola de5 de5test.pho de5test.wav  
                 
    to create a sound file. In this example the     
    audio file follows the RIFF Wav format. But     
    depending on the extension .au, .aif,     
    or .raw you can obtain other file formats.   
    Listen to it with your favorite sound editor,   
    and try other command files (*.pho) to have     
    a better idea of the quality of speech you      
    can synthesize with the MBROLA technique.       
                                                    
    On Unix systems you can pipe the audio output               
    to the sound player as on a HP :                            
     mbrola de5/de5 de5/TEST/de5test.pho - | splayer -srate 16000 -l16       
                                                                
    Also refer to the readme.txt file provided with             
    the mbrola software for using it.                           
                                                                
    4. - CONTACT -                                              

    ATIP GmbH
    Daimlerstr. 32
    D-60599 Frankfurt/Main
    phone: ++49 69 941 963 178
    fax: ++49 69 941 963 188

    http://www.atip.de
                                   
    Email: info@atip.de, for                          
    questions concerning the database DE5.

    Email: mbrola@tcts.fpms.ac.be, for general
    information, questions on the installation of               
    software and databases.                                     
