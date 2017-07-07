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


> LIST OF FUNCTIONALITY AVALAIBLE

#### SENDING Simple SMS
#### SENDING Bulk SMS
#### MANAGE CONTACT 
#### CHECK SMS STATUS 
#### CHECK SMS STATUS 
#### CHECK SMS REPORT 



### LICENCE 
MIT