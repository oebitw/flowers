# About the Product

## Vision:

### Product Vision

Spreading love is our vision, No matter how far the distance between you and your loved one you can always can send them a luxurious customized bouquet of roses to express your feelings.



### Pain Points we will solve

1) Break Distances between loved ones, no matters where are you located, you can always show love and send roses easily.

2) Choose the delivery date and we will take care of the rest.

3) You are so busy that you might forgot the important memories dates ? save the dates on your profile and we will remind you to send a unique roses bouquet to your loved one.

4) Do you love her/him as big as the universe? customize your roses box with a picture of the  (universe) pictured on that specific date. 

"Note that the pictures are real taken from nasa API".

5) Looking for luxurious bouquet of high quality roses ? our  team that combines innovative and modern lines with a minimalist design approach, putting creativity and nobility in front of everything is here to serve you


### Why should you care about the product?

*A Rose speaks love silently in a language known only to the heart*

We work hard to design our lovely Roses branded bouquet to be customized for you to show your true feelings to your loved one.


---

## MVP Epics and user stories

### 1) Application Setup

starting the process of creating an e-Commerce app using React with Redux, coupled with the store API server.

In this first phase, our goal is to setup the basic scaffolding of the application with initial styling and basic behaviors. This initial build sets up the file structure and state management so that we can progressively build this application in a scalable manner.

#### User Stories

- As a user, I expect to see a list of available product categories in the store so that I can easily browse products.

- As a user, I want to choose a category and see a list of all available products matching that category.

- As a user, I want a clean, easy to use user interface so that I can shop the online store with confidence.

#### Testing 

Testing for the core behaviors (user stories) of the application is required


### Shopping Cart

In this Epic , we will be adding the “Add to Cart” feature to our application, which will allow our users to not only browse items in the store, but also select them and have them persist in their “shopping cart” for later purchase.

#### User Story

- As a user, I want to choose from products in the list and add them to my shopping cart.

- As a user, I want to see the products that I’ve added to my shopping cart so that.

- As a user, I want to change the quantity of items I intend to purchase in my shopping cart.

- As a user, I want to be able to remove an item from my shopping cart.

#### Application Flow

- User sees a list of categories.

- … Chooses a category and sees a list of products.

- … Clicks the “Add to Cart” button on any product.

- … Clicks the “Cart” link in the header.

- … Sees a list of all products in the cart.

- … Clicks the delete button on an item and sees the item removed.

- … Changes the quantity selector on an item and sees the cart total change.


### Connect to Api and fetch data from our server

In this Epic we will be connecting our Store to a our API so that our data is persistent and able to be separately managed.

#### User Stories

- As a user, I want to interact with live inventory so that I have confidence that the displayed products are in stock.

- As a user, I want to know to that when I add an item to my cart, that it is removed from inventory so that no other users can purchase it.


### Checkout & Detail Pages

In this epic we will be adding a two full page views to the application: Product Details and Checkout.

#### user story

- As a user, I want to see a full detail view of a product so that I can make a more informed choice about purchasing it.

- As a user, I want to view my full cart and initiate the checkout process so that I can purchase my items and have them delivered







## Developer stories

- As a developer I want the app to be fully responsive

- As a developer I want to follow MVC design pattern 

- As a developer I want to use mongoDB to improve data retrieval performance 

- As a developer I want to use NASA API to get the universe picture on specific date.

- As a developer I want to use

- As a developer I want to apply RESTful architecture .


### Stretch Goal will be listed on the product backlog for future development after mvp testing:

- As a user i want to receive an sms to confirm my order.

- As a user i want to sign-up using google O-auth and Facebook O-auth.





---


## Functional Requirements


- Display a list of our product categories
- Display a listing of products for each category, when the category is selected
- From the product listings:
   - Click to view a full detail page about the product
   - Add the product to your shopping cart
- Shopping cart (simple version) always visible on screen
- Full shopping cart and check out screen available from main navigation


- A user can create a profile
- A user can sign in to his profile
- A user can choose a roses box from selection of bouquets
- A user can choose delivery time and place.
- A user can save their memories date and get notified when the memory date is close.

- a user can add the order to the cart, edit it and delete it

- A user can checkout to online payment or can chose to pay cash on delivery.

## Non-Functional Requirements

- Security: For creating user accounts, the bcrypt hashing function allows us to build a password security platform that scales with computation power and always hashes every password with a salt.

Flexibility : the menu is shown in every page so the user can navigate easily between pages


### Data Flow:


