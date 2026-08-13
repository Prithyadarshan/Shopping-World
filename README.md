# Shopping-World

## Overview

Shopping World is a multi-page static shopping website developed using HTML and CSS. The project provides a simple e-commerce-style interface where users can browse different categories of products including clothing, jewellery, furniture, stationery, and groceries.

The website consists of a main home page and multiple dedicated collection pages. Each category provides product images, product names, prices, offers, and navigation options. The project demonstrates the fundamentals of webpage structure, navigation, image handling, tables, hyperlinks, buttons, and basic CSS styling.

## Features

* Multi-page shopping website
* Category-based product navigation
* Men's clothing collection
* Women's clothing collection
* Kids' clothing collection
* Gold jewellery collection
* Diamond jewellery collection
* Platinum collection
* Silver collection
* Furniture collection
* Stationery collection
* Grocery collection
* Product images and descriptions
* Product pricing information
* Special offers displayed on collection pages
* Add to Cart buttons
* Back to Home navigation
* Custom favicon
* Organized local image assets
* Simple and easy-to-understand interface

## Technologies Used

* HTML5
* CSS3
* Images and local assets
* HTML Tables
* Hyperlinks
* Buttons

## Project Structure

```text
SHOPPING_WORLD/
│
├── Index.html
│
├── MensCollections.html
├── WomensCollections.html
├── KidsCollections.html
│
├── GoldCollections.html
├── DiamondCollections.html
├── PlatinumCollections.html
├── SilverCollections.html
│
├── Furniture.html
├── Stationary.html
├── Grocery.html
│
├── assets/
│   ├── Clothing images
│   ├── Jewellery images
│   ├── Furniture images
│   ├── Stationery images
│   ├── Grocery images
│   ├── Collection banners
│   └── saravana-stores.avif
│
└── README.md
```

## Website Pages

### Home Page

`Index.html`

The home page acts as the main entry point of the website. It provides navigation to all major shopping categories.

The main sections include:

* Clothes
* Jewellery
* Furniture
* Stationery Items
* Grocery Items

Each section contains an image and an `OPEN` button that redirects users to the corresponding collection page.

## Clothing Collections

### Men's Collection

`MensCollections.html`

The men's section contains:

* Half Sleeve Shirts
* Full Sleeve Shirts
* T-Shirts
* Jeans
* Formal Pants
* Baggy Pants
* Cargo Pants

Each product includes an image, price, and Add to Cart button.

### Women's Collection

`WomensCollections.html`

The women's section contains:

* Saree
* Chudidar
* Frock
* T-Shirt

Each product is displayed with its image, price, and Add to Cart button.

### Kids' Collection

`KidsCollections.html`

The kids' section contains:

* Frock
* Shorts
* T-Shirts

The page also displays special offers for the collection.

## Jewellery Collections

### Gold Collection

`GoldCollections.html`

The gold collection contains:

* Necklace
* Bangles
* Bracelet
* Earrings

Product weight and price information are displayed along with the product images.

### Diamond Collection

`DiamondCollections.html`

The diamond collection contains:

* Ring
* Necklace
* Anklet
* Bracelet

The products include their respective prices and carat information.

### Platinum Collection

`PlatinumCollections.html`

The platinum collection contains:

* Necklace
* Ring
* Bangles
* Watch

Product weight and pricing information are provided for each item.

### Silver Collection

`SilverCollections.html`

The silver collection contains:

* Chain
* Baby Hip Chain
* Nose Pin
* Anklet

Each product includes its weight, price, and Add to Cart button.

## Furniture Collection

`Furniture.html`

The furniture section provides different home and furniture products including:

* Wardrobe
* Cot
* Dressing Table
* Wall Frame
* Desk Drawer
* Lamp
* Chair
* Door

Each product is displayed with an image and price.

## Stationery Collection

`Stationary.html`

The stationery section contains products designed mainly for students.

Products include:

* Eraser
* Exam Pad
* Dictionary
* Sharpener
* Notebooks
* Bags
* Writing Items
* Pencil Box

The page also displays special offers for the school-opening season.

## Grocery Collection

`Grocery.html`

The grocery section contains commonly used household products such as:

* Pulses
* Rice
* Nuts
* Detergent
* Oil
* Dairy Products
* Biscuits

Product prices and measurement information such as kilogram and litre are displayed where applicable.

## Navigation

The website uses HTML hyperlinks to connect the different pages.

The basic navigation flow is:

```text
                         SHOPPING WORLD
                               │
        ┌──────────────────────┼──────────────────────┐
        │                      │                      │
     CLOTHING               JEWELLERY              OTHERS
        │                      │                      │
   ┌────┼────┐          ┌──────┼──────┐        ┌─────┼─────┐
   │    │    │          │      │      │        │     │     │
  Men Women Kids       Gold Diamond Platinum Furniture
                       │                     Stationery
                     Silver                    Grocery
```

Every collection page contains a **Back to Home** button for returning to the main page.

## Product Display

Products are organized using HTML tables.

Each product generally contains:

```text
Product Name
      ↓
Product Image
      ↓
Product Price
      ↓
Additional Information
      ↓
Add to Cart Button
```

This provides a simple and organized way of presenting the products.

## Offers

Different collection pages display promotional offers, including:

* Men's clothing offers up to 70%
* Women's clothing offers up to 50%
* Kids' clothing offers between 60% and 75%
* Gold jewellery discounts
* Diamond discounts
* Platinum offers
* Silver promotional offers
* Furniture purchase offers
* Stationery offers
* Grocery discounts

## How to Run the Project

### Step 1

Download or clone the repository.

### Step 2

Open the project folder in a code editor such as Visual Studio Code.

### Step 3

Make sure the `assets` folder is present in the project directory.

### Step 4

Open:

```text
Index.html
```

in a web browser.

### Step 5

Navigate through the different categories using the available buttons and links.

### Optional

For a better development experience, the project can be opened using the **Live Server** extension in Visual Studio Code.

## Expected Output

The website opens with the Shopping World home page.

Users can:

1. View the main shopping categories.
2. Select a category using the `OPEN` button.
3. Browse the products available in that category.
4. View product images and prices.
5. View available offers.
6. Navigate back to the home page.

The current **Add to Cart** buttons are interface elements and do not implement actual cart functionality.

## Project Objectives

The main objectives of this project are:

* To understand the fundamentals of HTML5.
* To create a multi-page website.
* To practice webpage navigation.
* To organize products into different categories.
* To use images effectively in webpages.
* To understand HTML tables.
* To implement hyperlinks between webpages.
* To apply basic CSS styling.
* To understand local asset management.
* To develop an e-commerce-style static website.

## Learning Outcomes

Through this project, the following concepts are demonstrated:

* HTML document structure
* Headings and text formatting
* Images and alternative text
* Hyperlinks
* Buttons
* Tables
* Basic CSS styling
* Borders and padding
* Text alignment
* Relative file paths
* Multi-page website development
* Website asset organization
* Category-based navigation

## Future Enhancements

The current project is a static HTML and CSS website. It can be enhanced in the future by adding:

* Functional shopping cart
* Product search
* Product filtering
* Product sorting
* User registration and login
* Wishlist functionality
* Product quantity selection
* Checkout page
* Online payment integration
* Order management
* Product reviews and ratings
* Responsive design for mobile devices
* Backend integration
* Database connectivity
* Admin product management
* User account management

## Purpose of the Project

The purpose of this project is to demonstrate the fundamental concepts of front-end web development by creating a simple and organized shopping website.

The project provides practical experience in developing multiple interconnected HTML pages, displaying products using images and tables, creating navigation links, and applying basic CSS styling to improve the presentation of webpage content.

## Author

**PRITHYADARSHAN T**

Computer Science and Engineering (Artificial Intelligence & Machine Learning)

**GitHub:** https://github.com/prithyadarshan

**LinkedIn:** https://www.linkedin.com/in/prithyadarshan-thiyagarajan-379a4b2a3

