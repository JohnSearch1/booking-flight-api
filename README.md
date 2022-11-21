# booking-flight-api
ZURI TRAINING

### HOW TO UPDATE A SPECIFIC FLIGHT RECORD
+ send a put request to `baseURL/flight/flightID` , flightID is the ID of the flight record you wish to update
+ the request body shoud have the properties you wish to update, for example; 
  ```javascript
     { "title" : "hahahahaha", "price" : 35900 }
  ```
