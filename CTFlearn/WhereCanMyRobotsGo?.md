#### Where do robots find what pages are on a website?<br>

Hint:<br>

What does disallow tell a robot?<br>


**SOLUTION:**<br>

So, this is the question I solved first which comes under easy category on CTFlearn.<br><br>
It says "Where do robots find what pages are on a website" and a int given as well as what does disallow tell a robot.<br>
For solving this, we must know there is a robots.txt file some websites.<br>
The robots. txt file, also known as the robots exclusion protocol or standard, is a text file that tells web robots (most often search engines) which pages on your site to crawl.<br>
It also tells web robots which pages not to crawl. Let's say a search engine is about to visit a site.<br><br>

So for CTFlearn we can go to its robots.txt by : https://ctflearn.com/robots.txt.<br>
Here we will find its written :<br>

                 **User-agent: *<br>
                 Disallow: /70r3hnanldfspufdsoifnlds.html<br>**
                 
We got disallow and theres a .html site on this.<br>

So we can now go to : ctflearn.com/70r3hnanldfspufdsoifnlds.html and we will find the flag as :   **CTFlearn{r0b0ts_4r3_th3_futur3}**.<br><br>

So by this way we can solve this problem, quite an easy one though you must know robots.txt can help you getsolution for many problems in a CTF.<br>

**FLAG:  CTFlearn{r0b0ts_4r3_th3_futur3}**<br>

                   
