# Pizzazy


Pizzazy: A delicious online experience. I designed and developed an e-commerce platform for this pizza restaurant, featuring an interactive menu with a variety of options including pizza, sushi, and pasta. Simplifying the online ordering process and providing a seamless user experience was the key goal of this project

Live Version:

[Pizzazy](https://pizzazzy.vercel.app/)

## Contents

- [Getting Started with Create React App](#gettingStarted)
- [Available Scripts](#scripts)
- [Used Dependencies](#dependencies)
- [Goals](#goals)
- [Plan](#plan)


## Getting Started with Create React App <a id="gettingStarted"></a>

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

To get started you need to:

1. Clone the project
2. npm install
3. Install listed dependencies
4. Use available scripts, like npm start

## Available Scripts <a id="scripts"></a>

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Used Dependencies <a id="dependencies"></a>

- [React Icons](https://www.npmjs.com/package/react-icons)
- [React Router DOM](https://www.npmjs.com/package/react-router-dom)
- [React Alice Carousel](https://www.npmjs.com/package/react-alice-carousel)
- [Leaflet Maps](https://react-leaflet.js.org/docs/start-installation/)
- [React Paginate](https://www.npmjs.com/package/react-paginate)
- [uuid - Random id generator](https://www.npmjs.com/package/uuid)
- [Tilt](https://micku7zu.github.io/vanilla-tilt.js/)
- [React Lazy Load](https://www.npmjs.com/package/react-lazy-load-image-component)
- [Framer Motion](https://www.framer.com/motion/)

## Goals <a id="goals"></a>

The goal of this project is to learn React and become a bit closer to real life projects. Most of the projects I worked with are only small pieces that are not much useful on it's own. By doing this project I will have to think not only as a developer but as a business and a customer. I will be updating the project time to time and adding information on what I did, what I learned, change of the plans and etc. Let's dive into details of this project!

## Plan <a id="plan"></a>

When working on a big project it defininetly gets harder to have all the ideas and plans in your head. It helps a lot when you can simply write everything down and follow the to do list. In this section, I will be adding everything I want to be happening on the website, whether it's backend or frontend. Yes, eventually I will need backend as well.

## User Story <a id="userStory"></a>

As a user, I want to be able to add items to cart even if I am not logged in/registered. When navigating to the menu page, I want to see menu items that have pictures, name, ingredients, pricing.
I want to be able to sort the menu by categories, as well as be able to find something specific by writing it in the search bar. I want to be able to add items to cart, indicate the amount or delete the items from the cart. In the cart section, I want to be able to see how much I have to pay total and have the possibility to navigate to payments. Before paying, I want to add a special request to my order, like, "no spicy, please".

## To-Do <a id="todo"></a>

#### Landing Page

1. [x] Create main landing page
2. [x] Carousel to header container
3. [x] Animation effect on landing page for Services & Image Grid section
4. [x] Interactivity to food categories on landing page - e.g. Pizza, Drinks, Burgers, Pasta
5. [x] Contact Form validation on main page
6. [x] Let the visitor scroll to the top of the page with one click
7. [x] Email subscribtion section
8. [x] Add accepted payments
9. [x] Smooth component loading animation
10. [x] Email Form validation on main page
11. [x] Modal window for login button

#### Login Modal

- [x] Email & password input
- [x] Forgot password option
- [x] Link to registration form

#### Menu Page

1. [x] Sortable by categories - category navigation on the side
- [x] Pizza category
- [x] Sushi category
- [x] Drinks category
- [x] Pasta category
- [x] Sale category

2. [x] Search input available
Menu items have:
- [x] Pricing
- [x] Name
- [x] Ingredients
- [x] Image
- [x] Sizings (in case of pizza)
- [x] Add to cart button

5. [x] Add pagination

6. [x] Menu side-cotainer

#### A single item page

- [x] A single menu item page
A single menu item page should include:
- [x] An image
- [x] Name
- [x] Ingredients
- [x] Price
- [x] Ability to choose size (in case of pizza)

#### Cart

- [x] Cart page
- [x] Empty cart page
Cart page should include:
- [x] Added item
- [x] Amount of unique items (if the same item is added several, it shouldn't repeat)
- [x] Disable ability to change item attributes
- [x] Ability to add/remove items
- [x] Ability to remove all items
- [x] Total amount of items
- [x] Total price
- [x] Tax amount
- [x] Buttons to menu/order page

#### Order page

- [x] Choice between order and takeaway
- [x] Promo code input

#### Blog

1. [x] Grid of blog posts
2. [x] Each post contains

- [x] Name
- [x] Picture
- [x] Description
- [x] Date
- [x] Author

2. [x] Add pagination

#### Contact

1. [x] Contact form with validations

#### Other

1. [x] Create sub-pages:
- [x] Menu
- [x] Blog
- [x] About
- [x] Contact
- [x] Cart
- [x] Registration page
- [x] Forgot Password page

2. [x] Create database or simple object for Menu
3. [x] Scroll to top when navigating to another page
4. [x] Update meta title depending on the current page
5. [x] Responsive layout


