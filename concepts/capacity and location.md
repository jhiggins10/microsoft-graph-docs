# Addition of capaicity and location in beta


From the latest beta release we can see that graph can be used to see the value of an address and name using the following command.

```
https://graph.microsoft.com/beta/me/findrooms
```

Using this command we get the following: 

```
"value": [
    {
        "name": "42nd street",
        "address": "ndstreet@doortablet.microsoft.com"
        
    }
    ]
```    

However is there a way that could show the capicity and the location of the address? Another example of this in action can be seen below:


```
"value": [
    {
        "name": "42nd street",
        "address": "ndstreet@doortablet.microsoft.com",
        "location": "london",
        "capicity": "30"
        
    }
    ]
```    
   
