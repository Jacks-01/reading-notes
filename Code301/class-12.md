# Class 12: 


## Reading
    In your own words, describe what each group of status code represents:
        100’s = Continue current operation, OK
        200’s = OK, request completed with no problems
        300’s = Indicates request had multiple choices
        400’s = Error
        500’s = Server Error
    What is a status code 202?
        - request was accepted but has not been processed yet
    What is a status code 308?
        - Permanent redirect
    What code would you use if an update didn’t return data to a client?
        - 200
    What code would you use if a resource used to exist but no longer does?
        - 202/204
    What is the ‘Forbidden’ status code?
        - 403


## Videos


    - Why do we need to pull our MongoDB database string out of our server and put it into our .env?
      - So we are able to keep the access link private, otherwise it would just be hardcoded which allows security issues.
    - What is middleware?
      - Middleware is the decryption software that helps the client and server talk to eachother.
    - What does app.use(express.json()) do?
      - It parses incoming requests and puts it into a variable (req.)
    - What does the /:id mean in a route?
      - The id is the id of the object that wer are running a CRUD function on. It allows us to reference an object by name
    - What is the difference between PUT and PATCH?
      - PUT updates an entire resource, PATCH only updates the nessecary info.
    - How do you make a default value in a schema?
      - You create a schema model with the key value pairs that you want your document to contain.
    - What does a 500 error status code mean?
      -  That means there was an issue with the server.
    - What is the difference between a status 200 and a status 201?
      - A status 200 is a general OK code that has a different context depending on the HTTP method, a 201 is specific to a PUT or POST request.
