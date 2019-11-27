# Paris Perfumes

[Paris Perfumes](https://morning-escarpment-49800.herokuapp.com/) 

**Object**

*The Application [Paris Perfumes](https://morning-escarpment-49800.herokuapp.com/) is a MERN stack technologies develop for an online marketplace application complete with features that enable users to buy and sell product.*

[Presentation](https://github.com/fpinder/Project3/blob/master/ParisPerfume.pptx?raw=true) *Provides and overview of the intended development of the new site*

`Home Page`

<a href="#"><img src="/" alt="Home Page"></a>


*The application also has an error checking process to ensure that all required are fields completed before the page order is submitted*

`Error Checking`

<a href="#"><img src="/" alt="error checking"></a>

`order Detail`

<a href="#"><img src="/" alt="order Detail"></a>

**The application Paris Perfumes is organized with the following struiture:** 

```
Paris Perfume 
    
    
```


**_Development Dependencies_**


 Files Used   |  Role in the App                                                                  |
| ------------ | -------------------------------------------------------------------------------------- |
| Babel | modules are needed for converting ES6 and JSX to suitable JavaScript for all browsers. |
| Webpack | modules will help bundle the compiled JavaScript, both for the client-side and server-side code. |
| nodemon  | to watch server-side changes during development |
| JWT  | Authentication with JSON Web Tokens  |
| Material-UI  | Material-UI is an open-source project that features React components that implement Google's Material Design |
| Express | To handle HTTP requests and serve responses properly | 
| Mongoose | to define a connection with the MongoDB database.  |
| Stripe   | to authenticate and completed order  |



**_Metadata_**

*The application's data is stored in side of the `Mongoose data base` as an  objects.* 

 ```
 [products.metadata]

 {
    "options": {},
    "indexes": [
        {
            "v": {
                "$numberInt": "2"
            },
            "key": {
                "_id": {
                    "$numberInt": "1"
                }
            },
            "name": "_id_",
            "ns": "mernproject.products"
        }
    ],
    "uuid": "f85d05c1129944ac9203db6cd78eae2c"
}

[orders.metadata]

{
    "options": {},
    "indexes": [
        {
            "v": {
                "$numberInt": "2"
            },
            "key": {
                "_id": {
                    "$numberInt": "1"
                }
            },
            "name": "_id_",
            "ns": "mernproject.orders"
        }
    ],
    "uuid": "8de176c60585498fb3f1502bdf4d82f4"
}

[shops.metadata]

{
    "options": {},
    "indexes": [
        {
            "v": {
                "$numberInt": "2"
            },
            "key": {
                "_id": {
                    "$numberInt": "1"
                }
            },
            "name": "_id_",
            "ns": "mernproject.shops"
        }
    ],
    "uuid": "a7755ed35ea64c68a94d32e85bbf6da9"
}


[users.metadata]

{
    "options": {},
    "indexes": [
        {
            "v": {
                "$numberInt": "2"
            },
            "key": {
                "_id": {
                    "$numberInt": "1"
                }
            },
            "name": "_id_",
            "ns": "mernproject.users"
        },
        {
            "v": {
                "$numberInt": "2"
            },
            "unique": true,
            "key": {
                "email": {
                    "$numberInt": "1"
                }
            },
            "name": "email_1",
            "ns": "mernproject.users",
            "background": true
        }
    ],
    "uuid": "b6755d5f4f30477fb978d44c9690e95d"
}

```

#
Lincense by <a href="https://creativecommons.org/licenses/by/3.0/" rel="nofollow">CC-BY</a>