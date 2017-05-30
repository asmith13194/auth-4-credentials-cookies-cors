# Credentials, Cookies, and CORS Quiz.
## Coookieee! Om Nom Nom!

### Instructions
With your partner, in words both of you will understand 6 months from now, answer the following questions.

> How would you best summarize credentials when it comes to auth?

Credentials are what proves your identification to be true and therefore can be authorized. This would include both your password and your username.

> Describe how cookies are exchanged between client and server.  Make sure you touch on the technical implementation of cookies.

Cookies are used to store client's credentials on the client side. They can only be up to 4kb in size combined. They are set by the server in the response header. The browser sends all cookies it has stored in the request.  

> From the perspective of a developer, name some basic strengths of using cookies and some weaknesses.

Cookies allow the server to store the client authorization. Session hijacking or Cookie hijacking is a hacking process by which the hacker gains unauthorized access to some confidential information in a way which is not facilitated by the user or a secure session. CORS can also become an issue. brute force Attacks are also a vulnerability to cookies.

> What is the difference between a session cookie and a persistent cookie?

Cookies have expirations, either session(expires at the end of session) or persistent(expires at a specified date and time).

> What is your opinion of the same-origin policy?  Support your opinion with some evidence.

I think that it is a good thing on the client side, because it keeps the user's information secure.
If you have been authorized on a certain domain, you can access the whole site. If you are directed to a third party site, you will have to be authorized again because each request needs to be made at the same origin.

> Based on what you know, how would you explain CORS?

If you are on one site and want to make a request to another site, the first site must authorize this request in order for it to be allowed.
