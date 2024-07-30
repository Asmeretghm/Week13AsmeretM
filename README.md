Week13
## Common Errors When executing GET, POST, DELETE Routes: 

![alt text](image.png)

This error is a result of using [https], e.g. (https://localhost:3000/item) instead of http://localhost:3000/item

** Don't enter anything in the body Json content format request**, Except for POST you will need to enter the key and value. 


### Common Error when executing POST

Not properly declaring the key and value, properly. 

E.g., if the body Json Content has no key and value. An undefined key will be stored in the scratch folder.  

The response is: 

{
  "message": "Item with key 'undefined' stored successfully"
}

If the data is entered incorrect: 
e.g., 

{
  "key": "selam",
  "Value": "peace to all"
  }

  Here the Value will be undefined

  If entered this way: (IF BOTH CAPITALIZED IN THE BEGINNING),

  {
  "Key": "selam",
  "Value": "peace to all"
  }
  
  
  If both key and value are capitalized, both will be save as undefined key and undefined value.  To save them correctly, both key and value need to be typed in a small letter case. 

  #### To request app.delete 
  ![alt text](image-1.png)
