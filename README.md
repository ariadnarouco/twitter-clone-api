# twitter-clone-api
Twitter clone API. We will create the back-end logic for this project

Stack used is :
- Mongo
- Express
- Node.js
- **Git** (This is not included as part of the syllabus)


## Users (./users)

#### List (./users/) [GET]
+ request 
  + params
  + header
  + body
+ response(200)

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




#### Get One user (./users/:id) [GET]
+ request 
  + params
    + id (This is the id of the user)
  + header
    + x-access-token -credenciales
  + body
+ response(200)

```

{
  _id : "24534656FS3252524SRDER435343FE",
  "name" : "Juan",
  "last_name" : "Vicente"
}
```




### Crear uno (./users/)[POST]

request

params
header
x-access-token - credeneciales
body
    {
        "name" : "Juan",
        "lastname": "Rodriguez"
    }
response (201)

body { "_id": "21389asdhad9asdasdzxc" "name" : "Juan", "lastname": "Rodriguez" }



#### Get One user (./users/:id) [PUT]
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

+ response (204)


#### Delete One user (./users/:id) [DELETE]
+ request 
  + params
    + id (This is the id of the user)
  + header
    + x-access-token -credenciales
  + body
+ response (204)





