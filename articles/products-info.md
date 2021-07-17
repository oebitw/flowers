# Rose Bouquet Page

Kindly note that this is a single-page web app where the user can handle all their needs on the same page without refreshing the page or being redirected to other product pages, we will use the power of react to create Rose eCommerce.

So this page here will handle all the products on the store, there will not be a specific page for each product.

The data will be changed by changing each element state, from the filtration that the user applies.


For the **initial state** of the elements check the list below:

1) Bouquet: Black Box

2) Size: 5 sets of Roses

3) Roses: Red Roses


## First Scenario

if the user entered the page from the link in the navBar or from the link in the Hero image, the following will be rendered:

1) The filters will be selected on the :

     - 5 Set of Roses

     - Black Box

     - Red Roses

2) Picture for five-set of red roses aligned perfectly in our black branded box.

3) Product Description for five-set of red roses aligned perfectly in our black branded box.

4) Product summary and Price for five-set of red roses aligned perfectly in our black branded box.

## Second Scenario

If the User Entered from the categories section on the home page, where the user selected the box color he/she is interested to buy.

note that the user didn't select the size of the box and the color of the roses so when the user enter the page the following will be rendered:

1) The filters will be selected on the : 
   - 5 Set of Roses 

   - The box color that the user selected on the home page 
   (Categories Section)

   - Red Roses

2) Picture for five-set of red roses aligned perfectly in the selected box.

3) Product Description for five-set of red roses aligned perfectly in the selected box.

4) Product summary and Price for five-set of red roses aligned perfectly in the selected box.


## DB and product stock status

Note that each time the user enters the product page we will send a query to our DB to get the product data and check if the product is in stock or not, our goal is to always show the user in-stock (available) products, let us go back to our scenarios again:

### First Scenario

if the user entered the page from the link in the navBar or from the link in the Hero image. (User didn't specify the box color he/she interested in)

we want to always show the user the available product so we will iterate until we find a product in stock and render it if the initial state products are unavailable, [**(check BPMN for better vision)**](https://miro.com/app/board/o9J_l6EW_DY=/)


### Second Scenario

If the user entered from the category section, the user  specified the product he/she wants to buy, so we want to show him/her the specific status of that product if it is in stock or out of stock.
(check BPMN for better vision)


## Software performance 

Note that in order to optimize software performance We choose red roses and black boxes to be our initial state because they are always in stock.

So practically the software will not reach the extreme cases to iterate and look for roses or boxes in the DB.

Time and space complexity for the software won't reach the ultimate cases.


Even if for any reason, we are out of stock. iterations for flowers and boxes we will prioritize and start first with the products that are always in stock:


For Roses:

1) Red ==> almost always in stock (95%)

2) White ==> almost always in stock (90%)

3) pink ==> 88% in stock and available

4) orange==>80% in stock and available

5) purple==> 74 % in stock and available


For Boxes:

1) Black Box ==> almost always in stock (95%)

2) White Box ==> almost always in stock (90%)

3) terquaz Box ==> 80% in stock and available