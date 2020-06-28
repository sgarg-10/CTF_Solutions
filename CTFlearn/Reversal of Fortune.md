Our team of agents have been tracking a hacker that sends cryptic messages to other hackers about what he's doing.
We intercepted the below message he sent recently, can you figure out what it says? He mentions his hacker name in it, that's the code you need.

.nac uoy fi tIe$reveRpilF eldnah ym gnisu em egassem ,avaj yllacificeps ,gnidoc emos htiw pleh deen I ,deifitnedi tegrat txeN


**SOLUTION**:

So this is another challenge on CTFlearn, a quite easy one.<br>
You just need to see the encoded line with a much more closer look and you we will be able to guess it.
Yes, the line is written in a reverse order and we can get the exact meaning of this line by using an online tool: **https://codebeautify.org/reverse-string** helping us to reverse the content of line.<br>
So, using this we can get:<br>
 *Next target identified, I need help with some coding, specifically java, message me using my handle FlipRever$eIt if you can.*<br>
 
 We can see the hacker's handle in it as **FlipRever$eIt**.<br>
 
 FLAG: CTFlearn{FlipRever$eIt}.

