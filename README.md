# twitter-clone-api
Twitter clone API. We will create the back-end logic for this project

Stack used is :
- Mongo
- Express
- Node.js
- **Git** (This is not included as part of the syllabus)


Users (./users)

####List [GET]
+ request 
  + params
  + header
  + body
+ response

####Get One user[GET]
+ request 
  + params
    + id (This is the id of the user)
  + header
    + x-access-token -credenciales
  + body
+ response

```
[{
  _id : "24534656FS3252524SRDER435343FE",
  "name" : "Juan",
  "last_name" : "Vicente"
},
{
  _id : "24534656FS3252524SRDER435343FE",
  "name" : "Juan",
  "last_name" : "Vicente"
}]
```



####Get One user[PUT]
+ request 
  + params
  + header
    + x-access-token -credenciales
  + body
    
    ```
{
  _id : "24534656FS3252524SRDER435343FE",
  "name" : "Juan",
  "last_name" : "Vicente"
}
```

+ response


####Get One user[PUT]
+ request 
  + params
  + header
    + x-access-token -credenciales
  + body
    
    ```
{
  _id : "24534656FS3252524SRDER435343FE",
  "name" : "Juan",
  "last_name" : "Vicente"
}
```


####Delete One user (./users/:id) [DELETE]
+ request 
  + params
    + id (This is the id of the user)
  + header
    + x-access-token -credenciales
  + body
+ response (204)





