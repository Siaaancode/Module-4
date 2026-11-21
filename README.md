# Module 4 - Purrfect Plants

This project is my final submission for the Module 4 unit of my Web Development course at South Staffordshire College.

## Links to Github profile and site:

[Github repository page](https://github.com/Siaaancode/Module-4)

[Purrfect Plants Website]()

![Homepage image]()

# Table of Contents
1. [Project information](#project-description)
2. [Strategy](#website-strategy)
    - Project goals
    - Target Audience
    - Research

3. [User Stories](#user-stories-user-research)
4. [Scope](#website-scope)
    - MVP (minimum viable product)
    - Features
    - How user features support user stories

5. [Structure](#website-structure)
    - User Journey

7. [Skeleton](#website-skeleton)
    - Wireframes

9. [Surface](#website-surface)
    - Responsiveness
    - Design Choice
    - Colour Palette
    - Typography

10. [Technologies used](#technologies-used)
11. [Database Schema](#database-schema)
12. [Django Templates](#django-templates)
13. [ERD](#entity-relationship-diagram)
14. [Testing](#testing)
    - W3C Validators (HTML and CSS)
    - Lighthouse
    - JSLint
    - Jest
    - Automated Testing and Manual Testing
    - Testing User Stories

15. [Deployment](#deployment)
    - GitHub Pages
    - Run this project locally
    - Deploy this website with Heroku

16. [Bugs](#bugs-discovered)
17. [Project Evaluation](#project-evaluation)
    - Final screenshots of finished website

18. [Credits](#credits)
    - Content
    - Media 
    - Code

## Project Description 

This project is an e-commerce website specialising in cat-friendly houseplants, designed for plant lovers. The aim is to provide a convenient and accessible way for cat owners to discover and purchase houseplants that are considered non-toxic.

It will offer a carefully selected range of plants, with product information to help customers make informed purchasing decisions based on their homes environments, plant care requirements and pet ownership.

Customers will be able to browse and search for plants, manage a shopping basket, securely purchase and view order history.

The overall purpose is to make buying plants easier for cat owners, providing a specialist shopping experience that considers the users love for both plants and their pets.

# Website Strategy 
[Return to table of Contents](#table-of-contents)

The strategy of this project is to develop a user-friendly and intuitive e-commerce website specialising in pet-friendly plants, that provides the customers with a easy and effective way to search, buy and track thier purchases. The primary users of this application will be customers that are looking to purchase plants, while staff will be able to manage products, categories, customer orders and stock levels separatley through Django admin.

The website will feature a straightforward and accessible interface, allowing customers to browse products, view detailed plant information and make purchases with minimal difficulty. Customers will be able to explore different plant categories, view product descriptions and images, check availability and pricing, and add selected items to their shopping basket. Registered customers will also be able to create an account, manage their personal information and review their previous orders. An important aspect of the website will be providing clear information about plant safety, helping customers make informed purchasing decisions when selecting plants for pet-friendly environments.

Python will be used as the primary programming language to develop the application's functionality and e-commerce logic. Django will provide the web framework and tools required to build the application, manage user authentication and interact with the database. Together, these technologies will allow the system to store and manage customer accounts, product information, categories, shopping baskets and order details. The database will also support stock management and order processing, helping to ensure that product availability is accurately maintained and that customers can complete their purchases efficiently.

Stripe API will be integrated into the website to provide a secure and reliable payment processing system, allowing customers to pay for their purchases during checkout. Stripe Checkout will be used to handle the payment process, redirecting customers to a secure payment page where they can enter their payment details and complete their transactions. Django will communicate with the Stripe API to create checkout sessions using the products and quantities stored in the customer's basket.

## Project Goals

The main goals of this project:

1. Develop a user-friendly and accessible e-commerce website that allows customers to browse, search and purchase a range of pet-friendly plants with ease.

2. Implement a reliable e-commerce system using Django and a relational database to manage customer accounts, product information, shopping baskets, stock levels and customer orders.

3. Integrate Stripe to provide secure online payment processing, allowing customers to complete purchases confidently while ensuring successful transactions are recorded and orders are updated accordingly.

## Target Audience

1. Plant enthusiasts
2. Pet owners

## User Stories (User Research)

### Must-have

1. Add items to basket:

"As a customer, I want to be able to add products to my basket so that I can keep track of the items I intend to purchase in one convenient place."

2. Browse products by category:

"As a customer, I want to be able to browse products by category so that I can easily find plants based on characteristics such as size, type and care requirements."

3. Create an account and log in:

"As a customer, I want to be able to register for an account and log in so that I can conveniently return to the website and make future purchases without repeatedly entering my personal information."

4. Make secure payments:

"As a customer, I want to have access to quick, convenient and secure payment options so that I can complete my purchases confidently and without unnecessary complications."

### Should-have

1. Adjust product quantities:

"As a customer, I want to be able to increase or decrease the quantity of products in my basket so that I can easily manage how many of each item I wish to purchase."

2. View basket total:

"As a customer, I want to be able to see the running total of my basket while shopping so that I can monitor my spending, avoid overspending and make informed purchasing decisions."

3. Search for products:

"As a customer, I want to be able to search for specific products so that I can quickly find the items I'm looking for and make the shopping experience more efficient."

### Could-have

1. Save favourite products:

"As a customer, I want to be able to add products to a wishlist so that I can save items I'm interested in and easily find them again when I'm ready to purchase."

2. Filter search results:

"As a customer, I want to be able to filter products by price, size and plant type so that I can narrow down the available options and find products that suit my preferences."

3. View previous orders:

"As a customer, I want to be able to view my previous orders so that I can keep track of my purchases and easily identify products I may want to buy again."

## Research

For this project, I researched one web applications with similar functionality to better understand existing approaches to personal finance management. This research helped identify the features, design principles, and usability considerations that should be incorporated into my own application.

During this process, I evaluated the strengths and weaknesses of each application, noting features that worked well, areas that could be improved, and ideas that could be adapted for my own project. These findings informed the design decisions made throughout the development of Purrfect Plants.

### Websites

#### Website 1 - 
(LINK)

1. What’s good?

2. What’s bad?

3. Features I could use?

4. What could be improved?

### Research Outcome

......

Top priorities for users based on research:

# Website Scope 
[Return to table of Contents](#table-of-contents)

For this project, I used an Agile development approach, using GitHub Projects to organise, prioritise, and track the development of the web application’s features.

By identifying and analysing user stories, I was able to define the features that users need, want, and may benefit from, ensuring the application is developed in line with user requirements and expectations.

## MVP (minimum viable product)

Each user story has been labelled as either a must-have, should-have, or could-have. The must-have requirements are considered essential and non-negotiable, as they are fundamental to the core purpose of the application. The should-have requirements are important features that add significant value and enhance the overall functionality of the system. The could-have requirements are optional features that would improve the application further but are not essential for meeting the main objectives of the project.

## Features

### Must-have
......
### Should-have
......
### Could-have
......

## How user features support user stories:

......

# Website Structure 
[Return to table of Contents](#table-of-contents)

The homepage will ......

The basket page will ......

etc. ......

## User Journey

- home page
- product page
- individual product page
- Basket

etc ......

# Website Skeleton 
[Return to table of Contents](#table-of-contents)

## Wireframes

These wireframes were created during the planning stages of my project to establish an initial layout structure and generate ideas for the functionality to include. They helped to visualise the placement of key information and features, as well as supporting the development of an organised and clean interface. 

### Home page

(INSERT INFORMATION ABOUT THE HOME PAGE)
(IMAGE LINK)

### OTHER PAGES, ETC. ......

# Website Surface 
[Return to table of Contents](#table-of-contents)

......

## Responsiveness

......

## Design Choice

......

## Colour Palette

......

## Typography

......

# Technologies used 
[Return to table of Contents](#table-of-contents)

......

# Database Schema

......

# Django Templates

......

# ERD Entity Relationship Diagram

......


# Testing 
[Return to table of Contents](#table-of-contents)

## W3C Validators (HTML and CSS)

......

## Lighthouse

......

## JSLint

......

### All functions passed JSLint

......

## Jest

......

### Automated Testing and Manual Testing

......

## Testing User Stories

......

(SHOULD DO MULTIPLE FOR THESE TO FIND BUGS)
### Tested Scenario - Expected Result

......

### Actual Result

......

## Testing evaluation
## Final checks

W3C HTML validator - Passed
W3C CSS validator - Passed
DevTools Lighthouse - Passed
JSLint - Passed
Github Pages - Passed
Manual testing - Passed
etc. ......

## Test Checklist:
### User Journey:

......

# Deployment 
[Return to table of Contents](#table-of-contents)

## GitHub Pages

## How to run this project locally

......

## Steps to deploy this website with Heroku

......

# Bugs Discovered 
[Return to table of Contents](#table-of-contents)

### Fixed

......

### Not Fixed

......

# Project Evaluation 
[Return to table of Contents](#table-of-contents)

......

## Final screenshots of finished website
### Mobile and smaller screens (under 768px)

......

### Tablets and larger (768px and up)

......

### Laptops and larger (992px and up)

......

### Larger screens (1200px and up)

......

## Further improvements that could be made

......

# Credits 
[Return to table of Contents](#table-of-contents)

## Content

......

## Media 

......

## Code

......