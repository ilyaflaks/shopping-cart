# shopping-cart
An app built with React and Strapi

### How to use
1) Follow the instructions on the [Strapi Quick Start Guide](https://docs.strapi.io/developer-docs/latest/getting-started/quick-start.html) only instead of the Restraunt Database create a "product" db
2) populate the product database so that navigating to http://localhost:1337/api/products returns the following: 
  { name: "Apples_:", country: "Italy", cost: 3, instock: 10 },
  { name: "Oranges:", country: "Spain", cost: 4, instock: 3 },
  { name: "Beans__:", country: "USA", cost: 2, instock: 5 },
  { name: "Cabbage:", country: "USA", cost: 1, instock: 8 },
3) if you don't have http-server installed open the command line
4) npm install -- global hhtp-server
5) cd into the folder with this project 
6) http-server -c-1
7) Navigate to http://localhost:8080/ in your browser
8) Add items to the cart by clicking "Add to Cart"
9) Replenish items by clicing "restock products" after making sure it says "products" in the inoput field



MIT License
