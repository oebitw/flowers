# Rose System Overview

## Business Requirements
Our application will power an online storefront that will allow our users to browse our product offerings by category, place items in their shopping cart, and check-out when they are ready to make their purchase.



## The core requirements and functionality


### Header

- The header should present the application title and main menu.

- All Pages will have the same Header in Order to have consistent Design through our web app.



### Home Page

- Dynamic Hero Image will be background for the navbar too. with a text will appear as index 1 above the hero image and it will change as the Hero image changes (the changing texts will show our main values and vision).
There will be a call to action button for the user to courage him to order.

- Note: In order to have a contestant Design, all the static pages will have Hero image with text and CTA on it.


- A brief educational section where user will be educated briefly about the product with a button to redirect user to discover us page.

- categories section display cards of our product categories, when the user hover on any Bouquet, animated Call to action button will appear to redirect the user to the product page.

- Testimonial section shows previous buyers feedback to build trust with the potential customers and users.
 

### Shopping Cart

- Shopping cart (simple version) always visible on screen.

- Ability to add or remove items  

- Ability to Edit items

### Account Icon

- This is a shadow button to test if the users are interested in creating an account. 

- When the user clicks on it a  greeting and thanking message will appear to him/her for their interest in creating an account. and stating that the feature will launched soon.


### Rose Bouquets 

- shows product images, description and stock statement

- ability to filter products by categories(box colors), Rose colors and Bouquet sizes.

- Ability to get universe picture on specific  from nasa API.

- Ability to add a customize message to add it to the picture.

- Ability to see your message, edit it and delete it.

- Ability to see order summary section, that shows the user what he/she ordered (Bouquet and Picture frame). 
 
- Ability to add the product to the shopping cart and checkout to pay.

- Refer to this [**DOCUMENT**](https://oebitw.github.io/flowers/articles/products-info) to have a solid idea about this page.

- Refer to the [wireframe and Business process flow](https://miro.com/app/board/o9J_l6EW_DY=/) for better and clearer vision.




### Discover Us 

- this page which will increase user awareness about our products.

- Show cards that describe our products and tackle the user pain point to courage him to buy

- Gallery that shows our products (check wireframe for the design)
 
- Form allow user to send us his occasion date to remind him for placing an order.

### Contact Us

- shows our social media pages, phone numbers, and other communication channels.


### Checkout

- Fill Personal Info and Delivery info forms

- Ability to choose delivery date

- Show the Cart

- Ability to Edit the cart

- Safe Online Payment option

- Cash on Delivery payment option


### Refund Policy and Privacy Policy

- educate the customer about our policies


### Footer

- The Footer should present our secondary menu. [Check wireframe for clearer vision.](https://miro.com/app/board/o9J_l6EW_DY=/)

- All Pages will have the same Footer in Order to have consistent Design through our web app.



## Technical Requirements

The application will be created with the following overall architecture and methodologies.

1) React

2) ES6 Classes

3) Redux Store for Application State

4) Deployed API with Mongo storage for storing categories and products.

5) Superagent or Axios for performing API Requests

6) Material UI for layout and styling.

7) Test Driven Development, using Jest.

8) Deployment to a cloud provider.



## MVP Epics and user stories

### 1) Application Setup


In this first phase, our goal is to setup the basic scaffolding of the application with initial styling and basic behaviors. This initial build sets up the file structure and state management so that we can progressively build this application in a scalable manner.

#### User Stories

- As a user I want to have the same header on all the web pages in Order to have consistent Design through our web app.

- As a user I want the header to contain the main menu to ease my navigation between website pages.


- As a user I want to see dynamic hero images for the products, and I want to read small descriptions on the images and a button to navigate me to the important pages.

- As a user I want to see this hero image on all static pages on the website in order to have consistent Design through the web app.

- As a user I want a section in the home page that will educate me briefly about the store products with a button to redirect me on a specific page to learn in details about the products.

- As a user I want to see a section containing the product categories displayed in nice designed cards with category name and a picture for that category so I can easily browse products.

- As a user I want when I hover on the category card to see a brief description of the category and a button that will redirect me to the product page.


- As a user  i want to see a testimonials section to read previous customers feedback in order to feel comfortable and trust the product.

- As a user I want to swipe the testimonials to right and left to read more feedbacks.

- As a user I want to see the store success stories or success metrics to feel more comfortable with your product, and to see that the web app is successful  and secure for online payments.

- As a user, I want a clean, easy to use user interface so that I can shop the online store with confidence.



### Shopping Cart

In this Epic , we will be adding the “Add to Cart” feature to our application, which will allow our users to not only browse items in the store, but also select them and have them persist in their “shopping cart” for later purchase.

#### User Story

- As a user, I want to choose the product i want to buy and add it to my shopping cart.

- As a user, I want to see the products that I’ve added to my shopping cart.

- As a user, I want to change the quantity of items I intend to purchase in my shopping cart.

- As a user, I want to be able to remove an item from my shopping cart.

#### Business Flow

Check [Business flow diagram](https://miro.com/app/board/o9J_l6EW_DY=/) for clearer vision.

- User sees a list of categories.

- Chooses a category and sees the product.

- Clicks the “Add to Cart” button on any product.

- Clicks the “Cart” link in the header.

- Sees a list of all products in the cart.

- Clicks the delete button on an item and sees the item removed.

- Changes the quantity selector on an item and sees the cart total change.


### Live Data and Product page

In this Epic we will be connecting our Store to our API, to retrieve live data from our database so that our data is persistent and able to be separately managed.

and we we will be adding our Rose bouquets page.

#### User Stories

- As a user, I want to interact with live inventory so that I have confidence that the displayed products are in stock.

- As a user I want to filter the product by its size, box color and roses color.

- As a user, I want to see a full detailed view of the product I filtered  so that I can make a more informed choice about purchasing it.

- As a user I want to select my occasion date and see a real picture for the universe taken by nasa on that date.

- As a user I want to read a description about the picture.

- As a user i want to decide if i want to add the picture or both picture and description to my order.

- As a user I want to have the choice to add a message to the picture.

- As a user i want to see my message and a summary of my order rendered on the page to review it.

- As a user I want to edit or delete my message.

- As a user, I want to add the order to my cart and checkout for payment.

- As a user, I want to know that when I add an item to my cart, that it is removed from inventory so that no other users can purchase it. 



### Checkout Page

In this epic we will be adding our Checkout page.

#### user story


- As a user I want to fill my personal  Information  and the delivery information to be confident that the item will be delivered to the right address.

- As a user I want the chance to add notes to my order (like favorite delivery time, don’t ring the bell, etc …)

- As a user I want to specify the delivery date as I want.

- As a user, I want to view my full cart and initiate the checkout process so that I can purchase my items and have them delivered.

- As a user i want to pay online or Cash.

- As a user I want my payment information to be encrypted and secure when I pay online.

- As a user i want to receive an invoice and order confirmation email or sms message when i complete my order successfully.


### Discover Us Page

In this epic we will be adding our Discover us page.

#### User Stories 

- As a user I want to see beautiful cards describe the products and how it will tackle my pain points. So I will be aware and well educated about the product.

- As a user I want to fill a form to save my info and the occasion date to be reminded when it is close.

- As a user i want to see high quality nice pictures of the product to have a good visualization of what I will buy


## Developer stories

- As a developer I want the app to be fully responsive

- As a developer I want to follow MVC design pattern in backend development.

- As a developer I want to use mongoDB to improve data retrieval performance 

- As a developer I want to use NASA API to get the universe picture on specific date.


- As a developer I want to apply RESTful architecture .



## api-server

Build a REST API using Express, by creating a proper series of endpoints that perform CRUD operations on a Mongo Database, using the REST standard.

### Data Models

- Create three data models one for the store products, and one for our clients , and the last one for users filled our love form using Mongoose.

- Create a Collection Class that accepts a Mongoose Model into the constructor and assigns it as `this.model`

  - Each method should in turn call the appropriate Mongoose method for the model
  - create()
  - get() or read()
  - update()
  - delete()

#### Our Products Data Model Information

```
boxColor: Type: String, Required
roseColor: Type: String, Required
size: Type: Number, Required
image: Type: String
productDescription:String
price: Number
stock: Number

```

#### Our client Data Model

```

// Personal Info

userFullName: Type: String, Required
email: Type: String , Required
phoneNumber: Number, Required

// Delivery Info
receiverName:String
address: String ,Required
detailedAddress: String, Required
deliveryDate: Date
notes:String

// order info
boxSize:number 
boxColor:String
roseColor:String
orderPrice:Number
Qty:number
frameInfo:String
customMessage:String

//Payment Info:

paymentMethod: String

```

### Love Form Data Model

```
fullName: Type: String, Required
email: Type: String , Required
phoneNumber: Number, Required
occasionDate: Date , Required

```

### Routes

In the express server, create a router module for The Product model that you’ve created. Within the router module, create REST route handlers for each of the REST Methods that properly calls the correct CRUD method from the matching data model.

For the Client and Love form Models for now we only want to create a post request to let the client to complete the order and save it's data to our DB or to let the user send us his/her occasion data and contact information.


#### Add a Product (mainly used by the shop owner)

- CRUD Operation: Create

- REST Method: POST

- Path: /product

- Input: JSON Object in the Request Body

- Returns: The record that was added to the database.

  - You must generate an ID and attach it to the object.

  - You should verify that only the fields you define get saved as a record

#### Get All Records for the products

- CRUD Operation: Read

- REST Method: GET

- Path: /product

- Returns: An array of objects, each object being one entry from your database

#### Get Specific Product Record

- CRUD Operation: Read

- REST Method: GET

- Path: /product/1

- Returns: The object from the database, which has the id matching that which is in the path


#### Update A Product Record

- CRUD Operation: Update

- REST Method: PUT
Path: /product/1

- Input: JSON Object in the Request Body

- Returns: The object from the database, which has the id matching that which is in the path, with the updated/changed data
  - You should verify that only the fields you define get saved as a record


#### Delete A Product Record

- CRUD Operation: 

- REST Method: DELETE
Path: /product/1

- Returns: The record from the database as it exists after you delete it (i.e. null)




## auth-server (Stretch Goals for next version of the software after wee see the test results from the shadow button)


### technical requirements

- Node.js

- ES6 Classes and best practices

- ExpressJS Web Server, built modularly

  - “Auth” routes for handling the login and authentication system
     - POST `/signup` to create an account

     - POST `/signin` to login with Basic Auth
 
   - Middleware for handling 404 and 500 conditions

   - Middleware for handling Basic Auth (username + password) to be used on the /signin route only

       - i.e. `app.post('/signin', basicAuthentication, (req, res) => { ... })`

    - Middleware for handling Bearer (token) to be used on any other route in the server that requires a logged in user

      - i.e. `app.get('/privateRoute', tokenAuthentication, (req, res) => { ... })`


- User Persistence using a Mongo Database (NoSQL)
Mongoose Schemas (data models) to define and model data

- Test Driven Development, using Jest

  - Tests will be runnable locally

  - Tests will auto-execute (CI) in your repo using GitHub actions

  - Tests will use a 3rd party library called supergoose to:
     - “mock” the mongo running database

     - “mock” the running Express server.


### Users Data Model

```
username: Type: String, Required

password: Type: String, Required

email: Type: String , Required

fullname: Type: String

```

### User Stories

***1) As a user, I want to create a new account so that I may later login***

- Make a POST request to the `/signup` route with username and password.

- Server should accept a request body in either JSON or form/urlencoded formats.


- On a successful account creation, return a 201 status with the user object in the body.

- On any error, trigger your error handler with an appropriate error


Example:

1) Input:

```
 {
    "username":"omar",
    "password":"123123",
    "fullname":"omar ewies",
    "email":"omar@omar.com"
  }
  ```

2) Output

```
Body:

{
    "token": "ENCRYPTED.JWT.TOKEN",
    "user": {
        "__v": 0,
        "_id":
        "5ec44dcde458f14f77b3d8c6",
        "acl": [],
        "password":"$2b$10$Bw5p3Iq,
        "username": "omar"
    }
}
```


**2) As a user, I want to login to my account so that I may access protected information**

- Make a POST request to the `/signin` route

- Send a basic authentication header with a properly encoded username and password combination

- On a successful account login, return a 200 status with the user object in the body

- On any error, trigger your error handler with the message “Invalid Login”



**3) As a user, I want to obtain a token after I signin, so that I can re-authenticate**

Following a POST to `/signup` to create an account (or) Following a POST to `/signin` with basic authorization
Send a response to the client with the proper status code along with an object with the following properties

```
{
  user: {
    _id: 'ID FROM DB',
    username: 'omar'
  },
  token: 'JWT Token Here'
}
```



**4) As a user, I want to use my token to access routes that require a valid user**

The request must send an Authorization header, with the value of `Bearer TOKEN`
  - TOKEN is the token that you would have returned to the user after their signin.

- If the TOKEN is valid (if it represents an actual user)
  - The route should function as it normally would (sending a response)

- If not
  - Send the user an error message stating “Invalid Login”

**5) As the website owner, I want our token system to be as secure as possible so that our users can feel safe when logging in**

Ideas

   - Add an additional layer of encryption

   - Add support for the creation and usage of time sensitive (valid for 60 minutes) JWTs

   - Implement Sessions



**6) As a Developer, I want to make automated tests to be confident that my Code is working perfectly before deployment**

- POST to /signup to create a new user

- POST to /signin to login as a user (use basic auth)

- Need tests for auth middleware and the routes
  - Does the middleware function (send it a basic header)

  - Do the routes assert the requirements (signup/signin)

- This is going to require more “end to end” testing that you’ve done in the past
  - To test signin, your tests actually need to create a user first, then try and login, so there’s a dependency built in

- Ensure that you use supergoose to test your routes and your database




