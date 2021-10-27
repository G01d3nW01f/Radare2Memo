# ragg2

  radare2 egg (?)
  
  generate the padding 
    like a gdb-gef or peda's "pattern create"
    
    ragg2 -P 200 -r > junk.txt
    
    vim fuzz.rr2
    
    cat fuzz.rr2
    
    ->  #!/usr/bin/rarun2
        stdin=./junk.txt
        
  r2 -r fuzz.rr2 -d <binary_name>


  # shellcode generate
    ragg2 -i exec -b 32 (32bit)
    
    ragg2 -i exec -b 64
    
    
