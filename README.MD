# NODEJS MODULE FOR MOOZISMS

Javascript client for sending SMS 

> Recover your API Credentials on Moozisms Dashboard

### INSTALL MODULE

```javascript
	    npm install moozisms
```

### USAGE

```javascript
	   var sms = require('moozisms')("API_KEY","API_SECRET");
	       sms.send("from","to","message"); 
	       sms.sendBulk("from /* Sender Alphanumeric ID */","listed contact with comma","message");
	       sms.checkStatus("reference");
	       sms.checkReport("date");

```


### FUNCTIONALITY

