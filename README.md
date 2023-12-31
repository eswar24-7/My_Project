# e-commercial website using Node js

## Project Description
The project aims to create a robust and feature-rich online food ordering and delivery platform. This platform allows users to browse a wide variety of dishes from different cuisines, add them to their cart, and place orders for home delivery or pickup. The system also provides restaurant owners with tools to manage their menu, view and process incoming orders, and interact with customers.

**Note** : This is a basic e-com site just to display my backend knowledge. It has basic functionalities and many features will be improved further.

**HTML template is taken from https://html.design**

## Key Features
**1.Browse and Search**: Users can browse a diverse menu of dishes, categorized by cuisine. A search feature allows them to find specific dishes.

**2.Order Placement**: Users can add items to their cart, specify order details, and place orders.

**3.Shopping Cart**: A shopping cart system allows users to review and modify their orders before checkout.

**4.Payment Integration**: Integration with payment gateways allows secure and convenient online payments.

**5.Responsive Design**: The platform is designed to work seamlessly on various devices, including mobile phones and desktops.

## Technologies Used
**Frontend**: HTML, CSS, JavaScript, EJS (Embedded JavaScript), Bootstrap<br/>

**Backend**: Node.js, Express.js<br/>

The **"type": "module"** is an important feature introduced in ECMAScript 6 (ES6) for JavaScript modules. It is used to indicate that a JavaScript file should be treated as a module, which allows you to use ES6 module syntax for importing and exporting variables, functions, and classes.<br/>
I have used the following npm packages:
- express
- express-session
- ejs
- mysql
- lodash<br/>

You can view these in the dependencies list of **package.json** file<br/>

**Database**: MySQL<br/>
Hosted on https://www.freesqldatabase.com<br/>

**Payment Gateway**: PayPal (for payment processing)

## How to Run
- Clone this repository to your local machine.
- Install the required dependencies using npm install.
- Run the application using npm start.
- Access the application in your web browser at http://localhost:PORT (by default, PORT is 3000).
  
## Project Structure
- public : contains all static files inside css, images, js folders
- views : contains all ejs files inside pages and partials folders 
  - pages : contains all the web pages of our website
  - partials : header and footer which are common for all pages
- main **index.js** file which containes routes for rendering HTML pages.
