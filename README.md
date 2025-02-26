Paradise Nursery Shopping Application
Welcome to the Paradise Nursery Shopping Application project! This project is the culmination of a React course, designed to build a fully functional and interactive front-end application for a nursery shopping experience.

Features
Landing Page

A visually engaging entry point.
Includes:
Company name.
A paragraph about the company.
Background image.
A "Get Started" button linking to the product listing page.
Product Listing Page

Browse a collection of houseplants categorized by shared features (e.g., air purifying or aromatic).
Includes:
Company name and logo (with navigation to the landing page).
Tagline.
Shopping cart icon showing the number of items.
Cards for each plant, displaying:
Thumbnail image.
Name, price, and brief description.
An "Add to Cart" button that updates dynamically to "Added to Cart".
Shopping Cart Page

Review, modify, and finalize your shopping list.
Includes:
Cards for each plant in the cart.
Features for modifying the quantity (increase or decrease buttons).
Delete option to remove items.
Subtotals per plant and a grand total for all items.
Checkout button.
User Interactions and Behavior
Adding an item to the cart:
Disables the "Add to Cart" button and updates the cart icon in the header.
Removing all items of a type from the cart:
Re-enables the "Add to Cart" button on the product listing page.
Updates the cart icon.
Dynamic updates:
Total cost and item count dynamically reflect user actions.
Technologies Used
React: Front-end framework for building user interfaces.
TypeScript: Typed superset of JavaScript for improved code quality and maintainability.
CSS: Styles for creating an appealing user interface.
Additional libraries or tools as needed.
Project Structure
Landing Page: Introduces users to the company and application.
Product Listing Page: Allows users to explore available plants and add them to their cart.
Shopping Cart Page: Provides a comprehensive view of selected items with options to modify and finalize the cart.
Setup Instructions
Clone the repository:
git clone https://github.com/your-username/paradise-nursery.git
Navigate to the project directory:
cd paradise-nursery
Install dependencies:
npm install
Run the development server:
npm start
The application will be available at http://localhost:3000/.

How to Use
Start at the landing page to learn about Paradise Nursery.
Click "Get Started" to browse the product listing.
Add plants to your cart by clicking "Add to Cart".
Navigate to the shopping cart page to review and adjust your items.
Proceed to checkout to finalize your order.
