# Point of Sale Application - Billing App
## About
A billing application is used to create and manage orders for a store. It helps in inventory and customer management. This application deals with four main modules namely Users, Customers, Products, and Bills. Users can view information about each module and also download bills if required.

## Features
* Create Bills, Manage Bills, View Bills, and Print Bill in PDF format.
* Create Customer, Update Customer, Delete Customer, and View Customer Details including all bills made under the respective customer.
* Add Product, Update Customer, View Products, and Delete Product.

## Screenshots
### Home Page
![Home Page](https://user-images.githubusercontent.com/70807417/120587988-fbc12180-c453-11eb-9098-a1c69f540d2d.png)

### Login and Register Page
Users can create their account or login into account through the page shown below
![Login Page](https://user-images.githubusercontent.com/70807417/120588262-899d0c80-c454-11eb-9c86-8a775cc8efef.png)
![Register Page](https://user-images.githubusercontent.com/70807417/120588270-8dc92a00-c454-11eb-9df3-b3d5993ad010.png)

### Dashboard
Once the user logged in, they land to the dashboard page of the application.
![Dashboard](https://user-images.githubusercontent.com/70807417/120588301-991c5580-c454-11eb-90c9-866fd3cbca4f.png)
In the below image, there is a drawer on left of the page where the user can navigate between different modules of the application
![Drawer open](https://user-images.githubusercontent.com/70807417/120588331-a5081780-c454-11eb-9086-484b4c98d7d4.png)

### User Detail Page
![User Detail Page](https://user-images.githubusercontent.com/70807417/120588392-b94c1480-c454-11eb-9156-28093e59880b.png)

### Customers Page
Here the users can add and manage customers.
![Customer Page](https://user-images.githubusercontent.com/70807417/120588416-c5d06d00-c454-11eb-95fd-19ffa97da327.png)

### Customer Detail Page
The user can also view customer details with all the bills generated under the respective customers
![Customer Detail Page](https://user-images.githubusercontent.com/70807417/120588440-cff26b80-c454-11eb-802c-6bf9425b3cfe.png)

### Product Page
Here the users can add and manage products.
![Product Page without View](https://user-images.githubusercontent.com/70807417/120588474-e0a2e180-c454-11eb-9a77-4f44454dcc0a.png)

### Product Page with View detail
On click of view button of a product, its details are shown on right side of the page.
![Product Page](https://user-images.githubusercontent.com/70807417/120588495-eb5d7680-c454-11eb-86c6-e41aa49c9bcc.png)

### Bills Page
All the generated bills are displayed in the bills page.
![Bills Page](https://user-images.githubusercontent.com/70807417/120588562-07611800-c455-11eb-87b2-fd7ea413ee0f.png)

### Add Bill page
To generate a new bill, we will fill in the details of the customer and all the products here. Suppose you want to add a new customer, then you can click on the ADD NEW CUSTOMER button which is on top right of the page, where a modal pops up to fill in the details of the new customer and proceed with generating the bill.
![New Bill Page](https://user-images.githubusercontent.com/70807417/120588609-19db5180-c455-11eb-96c8-f638559f46e0.png)

### Invoice Page
Here user can download the bill in PDF format.
![Bill View Page](https://user-images.githubusercontent.com/70807417/120588675-36778980-c455-11eb-8b26-a338d8b20ea3.png)

### PDF format of Bill
![Bill in PDF](https://user-images.githubusercontent.com/70807417/120588734-51e29480-c455-11eb-898d-baf49a3c2d75.png)

## Libraries and Utilities
React, Redux, react-router-dom, react-redux, redux-thunk, react-google-charts, moment, axios, material UI, validator


steps to start the project on the local machine 

1. open cmd cd  mbs then again cd to billing-app then type npm start /port 3000 
2. open cmd cd  billing backend then type  node index.js /port 5000
   
   
