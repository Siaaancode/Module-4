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

This project is an e-commerce website specialising in pet-friendly houseplants, designed for plant lovers. The aim is to provide a convenient and accessible way for pet owners to discover and purchase houseplants that are considered non-toxic.

It will offer a carefully selected range of plants, with product information to help customers make informed purchasing decisions based on their homes environments, plant care requirements and pet ownership.

Customers will be able to browse and search for plants, manage a shopping basket, securely purchase and view order history.

The overall purpose is to make buying plants easier for pet owners, providing a specialist shopping experience that considers the users love for both plants and their pets.

# Website Strategy 
[Return to table of Contents](#table-of-contents)

The strategy of this project is to develop a user-friendly and intuitive e-commerce website specialising in pet-friendly plants, that provides the customers with a easy and effective way to search, buy and track thier purchases. The primary users of this application will be customers that are looking to purchase plants, understand plant care and what plants are safe for pets.

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

#### Bloom & Wild
https://www.bloomandwild.com/

1. What’s good?

- Clean design: The design is aesthetically pleasing and promotes a professional presence.
- Easy navigation: The navigation is intuitive and it's easy to find certain products.
- Product presentation: Products include images, names, prices, etc.
- Pet-friendly category: The website has a specific category for pet-friendly plants.
- Customer reviews: Ratings and reviews helps build customer confidence and reassurance about product quality.
- Delivery options: Customers can select delivery date.
- Customer support: Dedicated help centre provides information about orders, deliveries and product questions.

2. What’s bad?

- Busy navigation: There are too many product categories, it feels too cluttered and overwhelming.
- Large amount of content: The home page has several promotional sections, which makes it difficult to identify needed information.
- Limited focus on pet owners: Although it does have a pet friendly section, the websites main focus is plant and flowers in general.
- Product information could be more specialised: Could have more detailed information about individual plants.

3. Features I could use?

- Product categories
- Product cards
- Search functionality
- Customer accounts
- Product reviews
- Product care guides
- Pet-friendly categories

4. What could be improved?

- Simplify navigation: Reduce unnecessary categories and prioritise more important sections.
- Improve product filtering: Introduce filters to allow customers to sort products based on the personal requirements.
- Provide more detailed plant information: Include watering frequency, lighting requirements and difficulty levels.

#### plnts
https://plnts.com/en-gb

1. What’s good?

- Modern design: Appealing appearance, consistant colour palette, quality images and organised layout.
- Product variety: Large variety of different plants.
- Pet-friendly category: Customers can filter products to show plants identified as pet-friendly.
- Product filtering: Customers can filter plants by characteristics, room location, care requirements, etc.
- Prodict information: Individual products display useful information.
- Plant care guides: It provides useful information to help customers understand the plants maintenance and care requirements.
- Customer reviews: Products reviews and overall customer ratings help build trust.
- Delivery information: Website explains how the plant are packaged, shipped and prepared for delivery.
- Additional products: Customers can browse and purchase additional items such as pots, watering equiptment, etc.

2. What’s bad?

- Busy homepage: Numerious promotional sections, product collections and featured categories. Feels overcrowded and unnecessary.
- Complex navigation: The amount of caregories and subcategories could be overwhelming, particularly with customers who are unfamiliar with different plant varieties.
- Limited pet-specific focus: Although it does contain a pet-friendly section, it's very limited compared to the rest of the products.
- Potentially overwhelming plant information: Customers may find some of the plant terminology difficult to understand.
- Customer service: Some customer reviews mention difficulties receiving support.

3. Features I could use?

- Product filtering
- Pet-friendly products category
- Product cards
- Plant care guides
- Related products

4. What could be improved?

- Simplify the homepage: Limit amount of sections and prioritise important information.
- Improve pet-safety information: Provide more detailed information about which pets each plant is considered safe for.
- Make navigation more accessible: Use a simpler navigation structure.
- Improve product filtering: Introduce more specific filters, allowing customers to search by pet type, plant size, care requirements, etc.
- Provide beginner-friendly descriptions: Explain botanical terminology and include straightforward care instructions.

### Research Outcome

Through my research, I have identified a gap in the market for e-commerce websites that specialise exclusively in pet-friendly plants. Both of the competitors I researched offer pet-friendly plants as a subcategory within a much wider product range, rather than making it the primary focus of their business.

This has helped me identify an opportunity to develop a more specialised website that caters specifically to pet owners. By analysing the features and functionality used by these competitors, I have gained a clearer understanding of which elements I could incorporate into my own project, while identifying areas where I could improve the overall user experience and provide a more targeted shopping experience.

Top priorities for users based on research:

1. Easy and intuitive search and filter process
2. Product categories
3. Plant care guidance

# Website Scope 
[Return to table of Contents](#table-of-contents)

For this project, I used an Agile development approach, using GitHub Projects to organise, prioritise, and track the development of the web application’s features.

By identifying and analysing user stories, I was able to define the features that users need, want, and may benefit from, ensuring the application is developed in line with user requirements and expectations.

## MVP (minimum viable product)

Each user story has been labelled as either a must-have, should-have, or could-have. The must-have requirements are considered essential and non-negotiable, as they are fundamental to the core purpose of the application. The should-have requirements are important features that add significant value and enhance the overall functionality of the system. The could-have requirements are optional features that would improve the application further but are not essential for meeting the main objectives of the project.

## Features

### Must-have

- Add items to basket
- Browse products by category
- Account creation and log in
- Secure payments

### Should-have

- Adjust product quantities
- View basket total
- Search for products

### Could-have

- Save favourite products
- Filter search results
- View previous orders

## How user features support user stories:

Although responsiveness was not explicitly included as a user story, it is considered a fundamental requirement for any modern web application or program. The application has been designed to provide an accessible and user-friendly experience across a range of devices and screen sizes, ensuring all users can interact with the application effectively.

1. Add items to basket:

Allowing customers to add products to a shopping basket enables them to manage their selected items in one place and purchase multiple products in a single transaction.

2. Browse products by category:

This user story makes it easier for customers to find products by organising them into clear, intuitive categories, improving navigation and the overall shopping experience.

3. Create an account and log in:

Allows customers to create a personal account and securely access their information, making it easier to manage their details, track orders and access account-specific features.

4. Make secure payments:

Integrating Stripe allows customers to complete purchases securely using a trusted third-party payment provider, protecting sensitive payment information and providing confidence during checkout.

5. Adjust product quantities:

Allows customers to increase or decrease the quantity of individual products in their basket, giving them greater control over their purchases.

6. View basket total:

Displays the combined cost of all products in the shopping basket, allowing customers to review their spending before proceeding to checkout.

7. Search for products:

Provides customers with the ability to search for specific plants using keywords, making it quicker and easier to find products without browsing through every category.

8. Save favourite products:

Allows registered customers to save products to a favourites list so they can easily revisit products they are interested in purchasing at a later date.

9. Filter search results:

Allows customers to narrow down product listings using specific criteria, such as price, plant category, size and pet suitability, making it easier to find relevant products and providing a better user experience.

10. View previous orders:

Allows registered customers to view their previous purchases, providing a convenient way to review order information and keep track of their purchasing history.

# Website Structure 
[Return to table of Contents](#table-of-contents)

The website will be structured to provide an easy, intuitive, and consistent experience for customers.

## User Journey

### Homepage

The homepage will provide users with an immediate insight into the purpose of the website. From here, users can access almost every page of the website intuitively. It contains clear navigation options, promotions of products and other relevant information. These include:

1. Primary navigation bar for key links:
    - Logo linking to homepage
    - Search bar
    - Basket link
    - Signup / Login option

2. Secondary navigation bar for products:
    - New in
    - Indoor plants
    - Outdoor plants
    - Accessories

3. Hero banner:
    - Header
    - Paragraph
    - Image

4. Promoted product cards section:
    - Side filter bar
    - Sort by dropdown menu
    - Product cards including product image, name, description and price

5. Footer information:
    - Logo
    - Links to support, about and contact
    - Social media links

### All products page

The all products page will offer a location for users to view all the products on the website, in one conveinient place. This page will essentially be an extention of the home page with a heavier focus on product browsing.

Users will be able to filter through the products based on specific criteria of their own and add products to their basket on this page.

### Basket page

The basket page will be a conveinent place where users can view every item they have selected to purchase.

The basket page will be accessable through the primary navigation bar, from there users can view, edit and delete products they have previously added. They can also decide to continue shopping or proceed to payment to confirm their purchase.

There is also a section underneath to encourage users to look at more products they may like, with buttons under each section that allows users to easily add them onto their order.

1. Product list:
    - Item names
    - Item cost based on quantity
    - Buttons to add or decrease quantity

2. Final total section:
    - Items total cost
    - Tax cost
    - Delivery cost
    - Final total with above combined

3. Decorative image

4. Buttons:
    - Continue shopping
    - Proceed to payment

5. You may also like section:
    - Product cards to relevant or promotional products

### Individual products page

The individual product page will be presented when a user clicks on a specific product card. This is for users to get more information on a product they are interested in purchasing. If the user decides to purchase the item, a button is available for them to adjust the quantity and add it to their basket.

1. Key product information:
    - Product name
    - Product description
    - Image
    - Price
    - Add to basket button
    - Buttons to adjust quantity

2. Plant care and information section:
    - Icons with plant specific information like light requirements, etc.
    - Collection of additional plant image

3. You may also like section:
    - Product cards to relevant or promotional products

### Signup page

The signup page will allow users to create a profile within the website, making purchases easier and faster by auto-completed their key information. A link is available at the bottom for users that have already signed up and need to login instead.

1. Sign up form:
    - Username
    - First name
    - Last name
    - Phone number
    - Email
    - Address
    - Postcode
    - Password
    - Confirm password
    - Key information about secure password creation

2. Already have an account link

3. Button to create account

### Signup confirmation page

The sign up confirmation page gives users meaningful feedback that their account has successfully been created. This page appears after a successful signup form has been completed and offers users a choice between returning to the home page or going to their new profile page.

1. Confirmation header and paragraph

2. Buttons to redirect users to the home page or profile

### Login page

The login page is designed to allow users to log into their accounts after creation. After users have successfully logged in, they will be redirected back to the home page. The redirect is to the home page because users can access most of the pages they may be looking for from there.

1. Login header

2. Email and password input fields

3. Don't have an account link

4. Login button

### Profile page

The profile page will offer a selection of things for the users to view, change or delete.

Users will have the options to edit their profile information, delete their account or view their current and previous orders on this page.

1. Personal details dropdown:
    - Username
    - First name
    - Last name
    - Phone number
    - Email
    - Address

2. Orders dropdown
    - Order cards stating key information about previous purchases, for example order number, items purchased on order, total cost of order, delivery address and billing address.

3. Account options buttons:
    - Edit personal details
    - Delete profile

### Edit profile page

The edit profile page offers users the ability to change key information an their profile conveinently.

1. Key information input sections

2. Save button

### Delete profile page

The delete profile page offers users the ability to completely remove their accounts from the website database.

1. Delete profile header and paragraph to ensure the user wants to do so

2. Delete and return to profile buttons

### Checkout payment page

The checkout page will be the final stage of proccessing the order through payment. Stripe will be specifically used for this website to provide secure and reliable purchases for users.

On this page there will be a dropdown option, so users can have the oppertunity to check the items and total price in their basket one last time before payment and confirmation of their order. They can then proceed with the payment.

1. Order summery dropdown:
    - Dropdown will provide users with a list of the items they are purchasing 
    - The total price on the side will be visable regardless of dropdown usage

2. Stripe API integration

### Order successful confirmation page

The order successful confirmation page gives users meaningful feedback that their order has successfully been created. From here, users can choose between being directed back to the home page or profile page through the available buttons.

1. Confirmation header and paragraph with image

2. Buttons to redirect users to the home page or profile

### Error 404 page

The error 404 page will provide users with a clear message that they have found a page that doesn't exist or no longer exists. At the bottom, the user will be offered a link to return to the home page. They also have the option from the links within the navigation bar as well.

1. Informative header

2. Link back to home page

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