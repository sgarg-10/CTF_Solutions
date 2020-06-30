**See if you can leak the whole database. The flag is in there somwhere… https://web.ctflearn.com/web4/**


#### SOLUTION:

So, this is web challenge on CTF learn. To solve this challenge, we have been given a website's link. When we copy paste it in our browser, we are greeted with this site.<br><br>


![SS1](https://user-images.githubusercontent.com/65415517/86117506-c8ac3a80-baec-11ea-9f30-7eca6e98a015.PNG)


As we can see, here it is written, **You know what to do**, So firstly we will inspect this webpage and for inspecting we will right click anywhere and click Inspect.<br><br>


![image](https://user-images.githubusercontent.com/65415517/86119439-15dddb80-baf0-11ea-96ec-e9bff2ad098f.png)


Here it is written, Try some names like Hiroki, Noah , Luke.<br>
So, we can enter these names in INPUT so as to get some information.<br>
Nothing happens with the name of Hiroki and Noah, but yes , interestingly we get something on entering name **Luke**.<br><br>


![image](https://user-images.githubusercontent.com/65415517/86119468-24c48e00-baf0-11ea-9385-71579465855e.png)


But this isnt enough for us. Its just giving some information related to Luke but nothing more.<br>
So here we use our technique called SQL Injection (name of challenge also suggests that) which helps us to get more usernames on entering a condition which will always produce a true result.<br>
By this, we induce a query into the database which inturn is put with a condition which will be always true, so when the condition is true, we can get all the usernames from the databse.<br>
You can learn about SQL injection on : **https://www.w3schools.com/sql/sql_injection.asp**<br><br>
Here, it is written that we can get usernames from a database on entering a condition.

So , here we enter a condition :   **'OR '1' = '1**<br><br>


![image](https://user-images.githubusercontent.com/65415517/86119489-31e17d00-baf0-11ea-9110-f7c694ce8cf2.png)


And on entering we get a huge lists of all the usernames and data related to it.<br>
And fortunately, we get our flag in it. So, this is how we can get our flag with the help of Basic SQL injection which is quite an important technique in entering into a database and getting all the usernames from it.<br><br>

FLAG: **CTFlearn{th4t_is_why_you_n33d_to_sanitiz3_inputs}**       (or try ABCTF{th4t_is_why_you_n33d_to_sanitiz3_inputs} )








