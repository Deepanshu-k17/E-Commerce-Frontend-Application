# Next.js E-commerce Website

A high-performance Next.js e-commerce platform with Redux Toolkit for state management, dynamic product filtering, pagination, and integrated Stripe payments. This project is built with Server-Side Rendering (SSR) and Static Site Generation (SSG) for optimized SEO and fast performance. It uses TailwindCSS for styling and includes dynamic charts for data visualization.


### Features
* Next.js: Utilized for server-side rendering (SSR) to fetch products, improving SEO and performance.
* TailwindCSS: For a fully responsive and modern UI/UX.
* Redux Toolkit: For efficient state management across the application.
* RTK Query: Simplifies data fetching and caching for API calls.
* Prisma: ORM for handling database operations with MongoDB.
* Express.js: Backend API development.
* Stripe: Integrated for secure payment processing.
* Authentication: User authentication and authorization system.
* Product Management: Sorting, filtering, and search functionalities to help users find the desired products easily.
* Fast, secure, and scalable architecture.     
* __Admin Dashboard__
  * Admin can see overall activity througout charts😊
  * Admin can add/edit/update/delete products to database
  * Admin can see Sales history
  * Admin can manage product for featured product
  * Admin can manage product for "Hot Offer"
  * Admin can track transactions/latest order
  * Admin can see most valuable customer        
* __User Dashboard__
  * Users can track their order
  * Users can edit their profile
  * Users can upload new profile picture 
  * Users can change password
  * Users can recover their forgotten password😊    

### Technologies Used
* __Frontend:__ Next.js, React, TailwindCSS   
* __State Management:__ Redux Toolkit   
* __Backend:__ Node.js, Express (Optional)    
* __Database:__ MongoDB (with Mongoose/Prisma for querying)   
* __Payments:__ Stripe    
* __Charts:__ Chart.js    
   
## Usage
* Browse products, filter by category, brand, etc.    
* Add items to the cart and proceed to checkout using Stripe.   
* Admin view includes charts to visualize sales, most popular products, etc.    

### Available pages
* Home page: https://gadget-galaxy-smoky.vercel.app/
* Products page: /product
* Single product page: /product/1
* Offered product page: /offer/1
* Cart page: /cart
* Login page: /sign-in
* Register page: /sign-up
* 404 page

### Features Overview
1. Product Display with SSR
Products are fetched using server-side rendering for better SEO and faster load times.
2. Sorting, Filtering, and Search
Users can sort products by price, popularity, etc.
Filter products based on categories, features, and other attributes.
Search for products using a custom search bar.
3. Redux Toolkit & RTK Query
Efficient state management with Redux Toolkit.
RTK Query for handling API calls and caching the results.
4. User Authentication
Sign up, log in, and access protected routes using JSON Web Tokens (JWT).
5. Stripe Integration
Seamless payment experience with Stripe integration.


### Screenshots
* Home page
![preview](public/preview/screencapture-gadget-galaxy.png)
* Product page
![preview](public/preview/screencapture-gadget-galaxy-product.png)
