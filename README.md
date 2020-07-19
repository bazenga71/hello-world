TWILIO_ACCOUNT_ID=AC418c674610da5ed5bbc7c3a76e32a086
TWILIO_AUTH_TOKEN=86df05ba7fedbe3cca8dfc7f38ca14ab
PORT=9095
Run the server using node server
The endpoints work under the base url http://localhost:{{port}}/api/v1/twiliosm
From postman you can test the endpoint
URL: [http://localhost:9095/api/v1/twiliosms](http://localhost:9095/api/v1/twiliosms)  
Method: POST  
Body JSON: {  
	"message": "test message",  
	"to": "573008169506"  
}

Response: {  
	"accountSid": "AC418c674610da5ed5bbc7c3a76e32a086",  
	"apiVersion": "2010-04-01",  
	"body": "test message",  
	"dateCreated": "2020-04-14T21:48:52.000Z",  
	"dateUpdated": "2020-04-14T21:48:52.000Z",  
	"dateSent": null,  
	"direction": "outbound-api",  
	"errorCode": null,  
	"errorMessage": null,  
	"from": "+13345004344",  
	"messagingServiceSid": null,  
	"numMedia": "0",  
	"numSegments": "1",  
	"price": null,  
	"priceUnit": "USD",  
	"sid": "xxxxxxxxxxxxxxxxxxxxx",  
	"status": "queued",  
	"subresourceUris": {  
		"media": "/2010-04-01/Accounts/xxxxxxxxxxxxxxxxxxxxx/Messages/SM70ea733f0f884b90b4549c570c5f2b15/Media.json"  
	},  
	"to": "+1xxxxxxxx",  
	"uri": "/2010-04-01/Accounts/xxxxxxxxxxxxxxxxxxxxx/Messages/SM70ea733f0f884b90b4549c570c5f2b15.json"  
}
