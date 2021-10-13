# CodePathCybersecurity

Here are just some of the notes I took while trying to use this for the first time.
- Needed to change the Internet explorer LAN setting for Burp and FoxyProxy to work properly. 
- In order to continue a request (aka stop it from just loading forever since Burp is intercepting the request), we must "forward" the request in the "Proxy" panel of Burp.
- We can enumerate attacks by sending requests through the intruder panel of Burp. By we can add, essentially, $$s that act as dummy variables such that each element of the list we paste can be put in a request. 
- To check whether any of the usernames in our list are correct, we notice for which username has a different length value compared to the other generic, incorrect usernames. Afterward, we use this correct username and enumerate for the password value and notice that a certain password had the 302 status which indicates success.
-Must uncheck using the proxy in order for configured web platforms to work again, like Incognito and other browsers other than what I used (Chrome)
