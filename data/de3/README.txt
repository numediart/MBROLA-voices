 
   .:::::    .::::::::          .::               
   .::   .:: .::      .:: .::   .::               
   .::    .::.::          .::   .::      .::   .::
   .::    .::.::::::   .::      .:: .::   .:: .:: 
   .::    .::.::          ::.   .::   .::   .:::  
   .::   .:: .::           :::. .::   .::    .::  
   .:::::    .::::::::.::::::   .:: .::     .::   
                                         .::     
           .:    .::: .:::::: .:: .:::::::  
          .: ::       .::     .:: .::    .::
         .:  .::      .::     .:: .::    .::
        .::   .::     .::     .:: .:::::::  
       .:::::: .::    .::     .:: .::       
      .::       .::   .::     .:: .::       
     .::         .::  .::     .:: .::       

    1. BRIEF DESCRIPTION OF THE DE3 DATABASE
    2. DISTRIBUTION                                 
    3. INSTALLATION AND TESTING                     
    4. CONTACT                                      
                                              
    1. --- BRIEF DESCRIPTION OF DE3 ---             
                                              
    DE3 (release 1.0) is a diphone database        
    for German provided in the context of the       
    MBROLA project                                  
    (https://github.com/numediart/MBROLA/).            
                                                    
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
                                             
    Please note:                                    
    You can synthesize short closed vowels          
    (e.g. [i, e, u, o]) using the                   
    corresponding long vowels.                      

    A glottal stop [?] will occur if a vowel
    is preceded by a pause.                         

    Limitations:                                    
    Notice that not all diphones are possible       
    in German. Impossible ones will trigger an      
    error message.                                  
                                                  
    2. --- DISTRIBUTION ---                         
                                                   
    This distribution of DE3 contains the        
    following files :                               

       de3      : the database itself               
       de3.txt  : This file  
                       
    and two example .PHO files in the TEST directory :  
       de3test.pho
       de3tts.pho             
                                                   
    Additional languages and voices, as well as     
    other example command files, are or will be     
    available in the context of the MBROLA          
    project. Please consult the MBROLA project      
    homepage :                                      
       https://github.com/numediart/MBROLA/        
    
    Registered users will automatically be notified 
    of the availability of new databases. To freely 
    register, simply send an email to               
    mbrola-interest-request@tcts.fpms.ac.be         
    with the word 'subscribe' in the message title. 
                                                
    3. --- INSTALLATION AND TESTING ---             
                                                       
    If you have not copied the MBROLA software      
    yet, please consult the MBROLA project          
    homepage and get it.                            
    Copy de3.zip into the mbrola directory and      
    unzip it :                                      
                                              
     unzip de3.zip (or pkunzip on PC/DOS)           
                                                    
    Try :
           mbrola de3 de3test.pho de3test.wav  
                 
    to create a sound file. In this example the     
    audio file follows the RIFF Wav format. But     
    depending on the extension .au, .aif,     
    or .raw you can obtain other file formats.   
    Listen to it with your favorite sound editor,   
    and try other command files (*.pho) to have     
    a better idea of the quality of speech you      
    can synthesize with the MBROLA technique.       
                                                    
    Use de3tts.pho as input-file if you want to listen
    to an example created with ATIP's Text-to-Speech
    system PROSER.   
    
    On Unix systems you can pipe the audio output               
    to the sound player as on a HP :                            
     mbrola de3/de3 de3/TEST/de3test.pho - | splayer -srate 16000 -l16       
                                                                
    Also refer to the readme.txt file provided with             
    the mbrola software for using it.                           
                                                                
    4. - CONTACT -                                              
                                                                
    ATIP GmbH
    Waldstr. 20                                                 
    D-61194 Niddatal                                            
    GERMANY
                      
    Tel.: 06187/292071
    Fax: 06187/292076

    http://www.atip.de                     

    Email: info@atip.de, for                          
    questions concerning the database DE3.

    Email: mbrola@tcts.fpms.ac.be, for general
    information, questions on the installation of               
    software and databases.                                     
