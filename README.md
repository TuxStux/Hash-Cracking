# Hash-Cracking
Tools that could aid in password hashes

# HashId 
- Built in Parrot tool (possibly Kali?) that will run hashes through an algorithm to determine the hash format for hashcat 
- CMD {hashid <md5 hash>}

#Hashcat
-CMD {hashcat -m 0 -a 0 -o cracked.txt target_hashes.txt /usr/share/wordlists/rockyou.txt}
