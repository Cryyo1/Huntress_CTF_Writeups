# Challenge

Caesar caesar, on the wall, who is the fairest of them all?

Perhaps a clever ROT13?


# Solution

## Part 1
```bash
alias rot13="tr 'A-Za-z' 'N-ZA-Mn-za-m'"
```
```bash
└─$ cat caesarmirror.txt | rot13 
     Oh boy! Wow, this warmup challenge sure   os I !rehtegot tup ot nuf fo tol a saw 
    definitely absolutely always love trying   sgniht evitavonni dna wen pu kniht ot 
       to do with the very basic, common and   fo trap tsrif ehT !seuqinhcet FTC cissalc 
     your flag is flag{julius_ and that is a   gnihtyreve ton si ti tub trats taerg 
 that you will need to solve this challenge.    dna edih ot gniyrt ekil t'nod I 
  separate each part of the flag. The second   od uoy tub _a_ni si galf eht fo trap 
   need just a little bit more. What exactly   ekam dna yrt ot ereh edulcni ew dluohs 
     this filler text look more engaging and   ?senilwen dda ew dluohS ?elihwhtrow 
    Should we add spaces and try and make it   hguone si senil ynam woH ?lacirtemmys 
 to make this filler text look believable? A    a nihtiw srettel fo erauqs dilos 
 simple, monospace-font text file looks good   eht ta tsomla ew erA .em ot hguone 
   end? It looks like it! I hope it is good.   }noitcelfer si galf ruoy fo trap driht ehT 
and at this point you should have everything   rof galf siht timbus ot deen uoy taht 
    points. The beginning is marked with the   ,ecarb ylruc gninepo eht dna xiferp galf 
  and it includes English words separated by   ylruc gnisolc a ni dne ot ,serocsrednu 
  brace. Wow! Now THAT is a CTF! Who knew we   siht ot rehpic raseac eht klim dluoc 
            extent?? Someone get that Julius   !ladem a yug raseaC 
```

- so flag part 1 is : flag{julius_

## Part 2

```bash
└─$ cat caesarmirror.txt | rot13 | rev                                                                                                                                
 was a lot of fun to put together! I so   erus egnellahc pumraw siht ,woW !yob hO     
 to think up new and innovative things   gniyrt evol syawla yletulosba yletinifed    
 classic CTF techniques! The first part of   dna nommoc ,cisab yrev eht htiw od ot       
 great start but it is not everything   a si taht dna _suiluj{galf si galf ruoy     
 I don't like trying to hide and    .egnellahc siht evlos ot deen lliw uoy taht 
 part of the flag is in_a_ but you do   dnoces ehT .galf eht fo trap hcae etarapes  
 should we include here to try and make   yltcaxe tahW .erom tib elttil a tsuj deen   
 worthwhile? Should we add newlines?   dna gnigagne erom kool txet rellif siht     
 symmetrical? How many lines is enough   ti ekam dna yrt dna secaps dda ew dluohS    
 solid square of letters within a    A ?elbaveileb kool txet rellif siht ekam ot 
 enough to me. Are we almost at the   doog skool elif txet tnof-ecapsonom ,elpmis 
 The third part of your flag is reflection}   .doog si ti epoh I !ti ekil skool tI ?dne   
 that you need to submit this flag for   gnihtyreve evah dluohs uoy tniop siht ta dna
 flag prefix and the opening curly brace,   eht htiw dekram si gninnigeb ehT .stniop    
 underscores, to end in a closing curly   yb detarapes sdrow hsilgnE sedulcni ti dna  
 could milk the caesar cipher to this   ew wenk ohW !FTC a si TAHT woN !woW .ecarb  
 Caesar guy a medal!   suiluJ taht teg enoemoS ??tnetxe 
```
- so flag part 2 is : in_a_

- so flag part 3 is : reflection}