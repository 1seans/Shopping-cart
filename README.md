# This project is a simple example of a shopping cart using React.

## Installation
Clone the repository: git clone https://github.com/example/react-shopping-cart.git
Install dependencies: npm install
## Usage
Start the development server: npm start
Open your browser and navigate to http://localhost:3000
You should see a list of available items with buttons that indicate the number of items in stock
Clicking on an available item button adds it to the cart and removes it from the available items list
The shopping cart is displayed below the available items list and shows the items that have been added
You can add more items to the cart by clicking on the available item buttons
You can remove items from the cart by clicking on the cart item buttons
## Project Structure
The project is split into three files:

App.js: The main entry point of the application. It imports the ShoppingCart component and passes it an array of available items.
ShoppingCart.js: The main component of the application. It contains the state for the available items and the cart, and handles moving items between the two.
Cart.js: A child component of ShoppingCart that displays the items in the shopping cart.
Dependencies
The project uses the following dependencies:

React: A JavaScript library for building user interfaces
React Bootstrap: A set of React components for Bootstrap
Bootstrap: A popular CSS framework for building responsive, mobile-first sites
