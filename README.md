# Candy Avenue - Webshop Group Project
_Thumnbnail to be added_
## 📌 Overview
Candy Avenue is a responsive candy webshop built as part of a JavaScript course, where we expanded into TypeScript to structured data and type safety.

The application allows users to browse a variety of candy products, filter them by category, view detailed product information, and manage favorites and cart items. The project was developed over 3 weeks in a team of four.

## 🚀 Features
- 🛍️ Browse all products
- 🍭 Filter products by category (e.g. chocolate, licorice)
- 🔎 Product details page for each item
- ❤️ Add/remove favorites (stored in localStorage)
- 🧾 View and update cart items (increase/decrease quantity)
- 🆕 Products marked as "new" are displayed first
- 📋 Checkout form autofills on focus
- ✅ Confirmation of simulated purchase and redirection to landing page
- 📱 Fully responsive, mobile-first design

## 🛠️ Tech Stack
- **TypeScript**
- **SCSS** for styling
- **Vite** for development and build tooling
- **JSON** as a local data source

## 🧠 My Contributions
I was primarily repsonsible for the product experience, and the creation and structure of the product data, including:

### 📦 Data & Structure
- Designed and structured the entire JSON file
- Defined how product data is organized and accessed throughout the application

### 🧩 Product Functionality
- Built the **Products page** and **Product Details page**
- Implemented dynamic rendering of products using fetched JSON data
- Handled logic for displaying "new" products first

### 🔎 Filtering System
- Implemented filtering using URL query parameters
  - Example: *?category=licorice*
- Enabled dynamic rendering based on selected category
- Reused the same system for multiple filtering scenarios

### ❤️ Favorites System
- Designed and implemented full favorites functionality
- Stored favorites in localStorage
- Built logic for:
  - Adding/removing favorites
  - Persisting data between sessions
  - Rendering favorited items dynamically
- Implemented filtering via query parameters:
  - Example: *?isFavorite=true*

### 🎨 Design
- Created the **initial** UI design in Figma for a previous course
- Designed all candy products with a vintage and nostalgic theme
- Contributed to overall UI/UX decisions over several pages

## 👥 Team Collaboration
- Group of 4 developers
- Collaborated using Git and GitHub Projects
- Other team members focused on:
  - Cart functionality
  - Checkout page
  - Landing page implementaion

A key part of the project was learning to:
- Work with others' code
- Structure a shared codebase
- Collaborate effectively using version control
- Applying agile methodologies in practice

## 🎨 Design & UX
- Mobile-first approach
- Fully responsive across devices
- Visual style inspired by vintage candy packaging, specifically 50's
- Custom-designed candy assets to match the nostalgic, vintage theme

## 📚 Challenges & Learning

### Challenges
- Working collaboratively in a shared codebase
- Reading and understanding other developers' code
- Using **fetch** to retrieve and work with JSON  (new concept at the time)
- Using URL query parameters for the first time (also a new concept at the time)

### Key Learnings
- Structuring and managing application data with TypeScript
- Implementing dynamic UI based on URL parameters
- Persisting user data using localStorage
- Building scalable filtering logic

## 🌱 Future Improvements
- Implement full search functionality
- Improve UI consistency (especially landing page)
- Add backend/database instead of static JSON
- Enhance accessibility

## 📸 Screenshots
_To be added_

## 📎 Project Context
This project was developed as part of a JavaScript course, where we transitioned into TypeScript to deepen our understanding of typed data and scalable frontend architecture.
