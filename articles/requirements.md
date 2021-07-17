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

- Refer to this [document](https://oebitw.github.io/flowers/articles/products-info) To have a solid idea about this page.

- Refer to the [wireframe and Business process flow](https://miro.com/app/board/o9J_l6EW_DY=/) for better and clearer vision.




### Discover Us 

- this page which will increase user awareness about our products.

- Show cards that discuss our products and tackle the user pain point to courage him to buy

- Gallery that shows our products (check wireframe for the design)
 
- Form allow user to send us his occasion date to remind him for placing an order.

### Contact Us

- shows our social media pages, phone numbers, and other communication channels.


### Checkout

- Fill Personal Info and Delivery info forms

-Ability to choose delivery date

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