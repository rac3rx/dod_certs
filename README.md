# dod root certs install

    two bash scripts one for linux and the other for osx; they're forked and repurposed
    
    linux script 
        - backs-up the trusted store if that target is populated
        - validates the number of certs within the archive vs what's in the trusted certificate store
        - performs an intersection if the previous check passes
    osx script 
        - not that great; can't figure out how to store the 38 or so certs without sudo needing to be validated 38 times too :

    
    
