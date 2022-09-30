## Reading Notes
## Assignment: Authentification

Statement: This topic is important because... Authentification is extremely important for secure applications especially in todays world where cybersecurity is essential to safe web use.
___

### Questions:
___

## Readings

[Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

1.  Explain to a non-technical friend how you would safely hash and store a password.
    - Hashing is the process of converting characters in a password to something completely unintelligble so your sensitive info isnt just siting in a DB
2.  What is Bcrypt?
	- Bcrypt is an encryption algorithm that is adaptive.
3.  Why might you use something like Bcrypt?
	- because it is extremely hard to crack, and takes extremely long if you decide to do so. It is highly resistant to most forms of cybercrime.

[Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

1.  What is Basic Authentication?
	- a basic auth process consisting of a username and password sent through HTTP headers.
2.  What properties are necessary in the header of a Basic Auth request?
	- Authorization: Basic username:password
1.  How are `username:password` in Basic Auth encoded?
	- They are encoded with Base64.

[OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

1.  Define the authentication process to a non-technical recruiter.
	- You create a username and password that adhere to the requirements set by the auth process, then it is sent to the server to check if you are who you say you are.
2.  How should your error messaging respond (both HTTP and HTML)? Why?
	- They should be generic and not prone to the discrepancy factor.
3.  Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

## Bookmark and Review

[bcrypt docs](https://www.npmjs.com/package/bcrypt)



### Things I want to know more about:
___


### Sources (if any):
___
