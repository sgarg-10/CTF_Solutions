In the computing industry, standards are established to facilitate information interchanges among American coders.
Unfortunately, I've made communication a little bit more difficult. Can you figure this one out? 
41 42 43 54 46 7B 34 35 43 31 31 5F 31 35 5F 55 35 33 46 55 4C 7D

#### SOLUTION<br><br>

So, here we have an easy challenge where we are given a string of mixed number and characters<br>
By reading the challenge, we can know they are talking about ASCII which is abbreviated from American Standard Code for Information Interchange, is a character encoding standard for electronic communication.<br>
So, we now know we have ASCII characters and we just need to convert it to plain text to get our flag.<br><br>
For this, we can use any ASCII decoder online, I prefer using : https://www.dcode.fr/ascii-code which will easily convert ASCII chars into different encoding techniques like HEX, OCT, DEC etc..<br>

We can copy paste the string given and can get text plain.<br><br>

![image](https://user-images.githubusercontent.com/65415517/86400586-82aace80-bcc6-11ea-88a6-d22b01104029.png)
<br><br>


It will give decryption with HEX, OCT , BINARY etc., but we can easily see, our flag is in HEX department, so it was an ASCII to HEX conversion.<br><br>

**FLAG : ABCTF{45C11_15_U53FUL}**



