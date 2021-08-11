# thai_financial_ctf_RSA
problem: fcs1 encrypted message 2021

e.g.
Modulus=66786253706550106651546922109281130018108580330137737023063153215868656799140830401717687979014370575432349299822348593480105855792805572771414208174453015865282142790897714037523138606055539556245525288537575545283847375133918614361476148858960383966021995875312158222430892437413254837113655891077705651117, 

Exponent=65537, 

Ciphertext=12749394765516431449034499739125601990325706736084735370298294481006295950319880313028622069208933863271179363126998669104081129046906588139752425172379379140125773177398490330950513447674517261186502864161121453447478493471749882713780681624249523710721276469151056178838957928438137144394093885634730200738

--------------------------------------------------------------------------------------------------------
From the challenge given text, we know that n(Modulus) with 308 digits has 2 prime factors.

p = 8172 285708 817950 195609 942788 528777 311997 560168 630579 888192 183660 269368 178285 165655 478925 615144 750734 205408 878496 249047 888681 766674 672936 214471 503035 969937 (154 digits) 

q = 8172 285708 817950 195609 942788 528777 311997 560168 630579 888192 183660 269368 178285 165655 478925 615144 750734 205408 878496 249047 888681 766674 672936 214471 503035 970141 (154 digits)

We can now calculate d for the ciphertext easily. The only difference between 2-prime RSA and this implementation is phi (phi is equal to the product of all the factors of n, each decreased by 1 or)
The outputs exactly one thing: "Hello, my sweetheart. Mee"
