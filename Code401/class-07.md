## Reading Notes
## Assignment:

Statement: This topic is important because...
___

### Questions:
___

## Reading

[Intro to JWT](https://jwt.io/introduction/)

1.  What is a JSON Web Token (JWT)?
	- a standard that defines a self-contained way for securely transmitting information as a JSON object.
2.  When should we use JSON Web Tokens?
	- Authorization
	- Information exchange
3.  Claims are expected in which structural component of a JWT?
	- payload

[Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

1.  If I get a JWT and I can decode the payload, how can we call that secure?
	- the reciever can tell if the token has been interfered with, and can reject it
1.  If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
	- the secret
1.  Explain how concatenated content and secret can be sent and received securely to non-technical recruiter.
	- once it is encrypted and sent to the reciever, they must know the secret key in order to decipher the message that was sent, otherwise it isn't valid.

## Videos

[JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

1.  Why use JWT?
	- it is a compact and secure way to send private information
2.  JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
	- because you can send it in an URL via an HTTP method
1.  What are the three components (the structure) of a JWT signature?
	- header
	- payload
	- signature



### Things I want to know more about:
___


### Sources (if any):
___
