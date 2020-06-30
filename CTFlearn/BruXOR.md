There is a technique called bruteforce. Message: q{vpln'bH_varHuebcrqxetrHOXEj No key! Just brute .. brute .. brute ... :D

**SOLUTION:**

So, here we have given some encoded text : **q{vpln'bH_varHuebcrqxetrHOXEj**. <br>
By reading the challenge and the challenge name, we can guess its brute force technique in XOR operation.<br>
Brute force is technique of applying all sorts of combination corresponding to particular method inorder to get answer we need.<br>
We try each possible combination until we succeed in getting the required answer and by reading the challenge, we can know we have to apply bruteforce technique in XOR Operation.<br><br>

For this, we can use any online XOR decoder, I prefer using : **https://www.dcode.fr/xor-cipher** as we have ***BRUTEFORCE/TEST ALL KEYS FROM 1 TO 8 BITS (SINGLE BYTE)*** option present here.<br>

By entering the message, and decoding it (Dont forget to select BRUTEFORCE/TEST ALL KEYS FROM 1 TO 8 BITS (SINGLE BYTE) option), we get all possible solutions.<br>

One of these is what we are looking for: FLAG[Y�U�hAVE�BRUTEFORCE�xor].<br><br>
Though, this is not the final solution as it is not in the official format of a flag.We need to change a little bit inorder to submit it.<br><br>

**FLAG : FLAG{Y0U_hAVE_BRUTEFORCE_xor}**


