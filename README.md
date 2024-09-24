A Pseudo Store Online Application.

Project Description:
The project I will be analyzing is a simple e-commerce website that retrieves and displays a list of products using the Fake Store API. 
Users can navigate the web app to view products, add items to their shopping cart, and update their cart contents by incrementing amounts or removing items. 
Users can also search for products, and observe their cart in a sticky sidebar, before checking out.

For this project, I applied HTML, CSS, and JavaScript to create a clean design and simple user interactivity. 

Functions:

1. Display Products   
The web application displays products from the Fake Store API, title, description, price, and an image along with an "Add to Cart" button to each product using a grid view on the page.

2. Add to Cart   
Users can add any product to their shopping cart using the "Add to Cart" button. Once an item is added to the cart, the cart value is updated to reflect the latest items in the cart and the newest dollar value.
  
3. Remove Items from Cart    
There is a cart section where users can delete products from their cart by clicking the "Remove" button next to each item in the checkout page.
Once an item is removed from the cart, the cart value is updated immediately.
   
4. Change Quantity:      
Users have the ability to increase or decrease the number of items in the cart by pressing the "+" or "-" buttons.
The product total value will also update appropriately, mimicking conventional shopping cart interfaces!
 
5. Search:     
This web application has a search bar at the top so that users can search for products by name using the search bar located at the top.
The page will only display product lists that match the search for the user. This gives users a funnel viewpoint of product selection on the website.

6. Local Storage:      
The cart data is stored in the local storage of the browser, therefore, the user would be able to have the items in their cart persist after refreshing or closing the website.
This feature is user-friendly while providing an understanding that the user of other websites cart modifications to remain persistent until the user clears the cart.

Project Structure:

HTML:
The HTML file delineates the website layout. The notable parts of the HTML file are:

Header: This includes the search bar and a location for potentially a logo or site title.
Main content: This is where the product list will be displayed dynamically as well as the sticky cart that will be a sidebar.
Footer: Basic footer information for the site.

CSS:
The CSS file provides the styling to the entirety of the site to be visually appealing, comfortable, and user-friendly. Notable styles are:

Responsive grid layout: All products are displayed cleanly and in an organized layout.
Hover Effects and Transitions: Helps interaction on the users' side, making the site feel modern and interactive.
Sticky Cart: Still visible even when in the product list and when scrolling through the list.
Custom Scrollbar: Polished and consistent design for the cart's scrollbar.

JavaScript:

The JavaScript file controls the dynamic functionality of the site. Notable functions are:

Fetching products: Uses the Fake Store API to fetch the products and render them on the page.
Add to Cart: Manages adding items to the cart, as well as changing and managing the display of the cart.
Delete and Adjust Quantities: Re-delete items and change quantities of the items.
Search Functionality: Searching or filtering the product list based on the users input to the search bar.
Local Storage: Local saves the cart data so it maintains cart persistence between the pages. 
