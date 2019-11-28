# Paris Perfumes

[Paris Perfumes](https://morning-escarpment-49800.herokuapp.com/) 

**Object**

*The Application [Paris Perfumes](https://morning-escarpment-49800.herokuapp.com/) is a MERN stack technologies develop for an online marketplace application complete with features that enable users to buy and sell product.*

[Presentation](https://github.com/fpinder/Project3/blob/master/ParisPerfume.pptx?raw=true) *Provides and overview of the intended development of the new site*

**Home Page**

<a href="#"><img src="https://github.com/fpinder/Project3/blob/master/client/assets/images/default.jpg" alt="Home Page"></a>


*A customer can access the site without having and account and view all the shops available*

`All Shops`

<a href="#"><img src="https://github.com/fpinder/Project3/blob/master/client/assets/images/AllShopst.jpg" alt="All Shops"></a>


**Sing up, Login and Profile**

*In order to complete or purchase a product a person will need to create and account or login. Addiitonally he/she has he ability to edit the profile to be an activity seller or just delete the account*

`Sing up`

<a href="#"><img src="https://github.com/fpinder/Project3/blob/master/client/assets/images/sing-up.jpg" alt="Sing up"></a>

`New Account`

<a href="#"><img src="https://github.com/fpinder/Project3/blob/master/client/assets/images/new-account.jpg" alt="New Account"></a>

`Profile`

<a href="#"><img src="https://github.com/fpinder/Project3/blob/master/client/assets/images/profile.jpg" alt="Profile"></a>

`Edit Profile`

<a href="#"><img src="https://github.com/fpinder/Project3/blob/master/client/assets/images/profile-edit.jpg" alt="Edit Profile"></a>

`Delete Account`

<a href="#"><img src="https://github.com/fpinder/Project3/blob/master/client/assets/images/deleteAcct.jpg" alt="Delete Account"></a>



**New Shops, Added Products, Ordering, Check out, and Invoices**

*When an account is created and if a customer acivate his/her account as a seller he/she can create a shop and add products to be sold. After the customes has seleted the items it's put in the checkout basket. When the customer click on checkout he/she will be taking to the checkout form to completed the order with the credit card number and shipment information. After the oreder is completed the customer will see the invoice of the iterms purchase*

`New Shops`

<a href="#"><img src="https://github.com/fpinder/Project3/blob/master/client/assets/images/new-shop-create.jpg" alt="New Shops"></a>

`Added Products`

<a href="#"><img src="https://github.com/fpinder/Project3/blob/master/client/assets/images/new-products.jpg" alt="Added Products"></a>

`Order`

<a href="#"><img src="https://github.com/fpinder/Project3/blob/master/client/assets/images/order.jpg" alt="Order"></a>

`Order Checkout`

<a href="#"><img src="https://github.com/fpinder/Project3/blob/master/client/assets/images/order-checkout.jpg" alt="Order Checkout"></a>

`Invoice`

<a href="#"><img src="https://github.com/fpinder/Project3/blob/master/client/assets/images/order-placed.jpg" alt="Invoice"></a>


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
 [Products.Metadata]

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

[Orders.Metadata]

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

[Shops.Metadata]

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


[Users.Metadata]

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