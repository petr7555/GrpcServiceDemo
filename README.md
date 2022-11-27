In Postman:
- type `localhost:5287` as server URL
- import `GrpcServiceDemo/Protos/greet.proto` as proto file
- send message:
	```json
	{
	  "name": "John"
	}
	```
- receive response:
	```json
	{
	  "message": "Hello John"
	}
	```
