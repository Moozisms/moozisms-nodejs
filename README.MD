# NODEJS MODULE FOR MOOZISMS
Javascript client for sending SMS 

> Recover your API Credentials on Moozisms Dashboard

### INSTALLATION MODULE

```javascript
   npm install moozisms
```

### USAGE

```javascript
   var moozi = require('moozisms');
   var sms = new moozi.setup(
      "API_KEY": "XXXX", 
      "API_SECRET": "XXXX",
      "CONTENT_TYPE": "XXXX" /* optionnal json is used by default. value possible (json or xml) */
    );
   sms.send("from","to","message"); 
   sms.sendBulk("from","listed contact with comma","message");
   sms.checkStatus("reference");
   sms.checkReport("date");

```


### FUNCTIONALITY

## SENDING Simple SMS


### LICENCE 
MIT