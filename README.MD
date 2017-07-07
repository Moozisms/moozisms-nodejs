#NODEJS MODULE FOR MOOZISMS
Javascript client for sending SMS *

> Recover your API Credentials on Moozisms Dashboard

### INSTALL MODULE

	``` javascript
	    npm install moozisms
	```

### USAGE

	``` javascript
	   var sms = require('moozisms')("API_KEY","API_SECRET");
	       sms.send("to","from","message"); /* to : alphanumeric sender id maximum 11 characters and 18 for only numeric sender ID */
	       sms.sendBulk("listed contact with comma","from","message");
	       sms.checkStatus("reference");
	       sms.checkReport("date");

	```


### FUNCTIONALITY

 