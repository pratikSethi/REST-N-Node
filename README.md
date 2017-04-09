# REST-N-Node
RESTful API design with Node.js

How to run the application

Make sure you have mongodb installed locally. Follow the instructions on
	https://docs.mongodb.com/manual/installation/

Run the mongod server using the command 
	$mongod

Go to the root folder of the app and run the following command
	$node server.js

Open Postman (Rest Client) url -> localhost:3000/users/

	For 'Post'
	In body use x-www-form-url-encoded
	Add the key value pairs as per the schema

	Hit the Send button and you should get a response.

	For 'Get'
	localhost:3000/users/ and hit send 
