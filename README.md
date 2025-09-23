# Project Description 
Style Hub is a modern full-stack modern E-commerce website that allows the user to shop for products online and make purchases. It will have categories for men, women, electronics, and home. The overall Page structure should be like this: 

## Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL

# Site Map (Page Structure)

1. **Landing Page / Home**
   * Navbar 
   * Hero section (featured products / categories)
   * Highlights (bestsellers, trending, new arrivals)
   * Call-to-actions (Shop Now, Signup)
   * Newsletter subscription
   * Footer

2. **Authentication**
   * Login Page
   * Signup Page
   * Forgot Password

3. **Home**
   * Navbar -> Logo, Search bar, Language option, Cart, Profile
   * Hero Section
   * Contents with options (Featured Products, New Arrivals, Best Sellers)
   * Footer
   
4. **Categories Page**
   * Categories for men, women, and electronics
   * Products in each category
   * Footer

5. **Details Page**
   * Product Details
   * Add to Cart
   * Buy Now
   * Other related product items
   * Footer

6. **Checkout Page**
   * Cart Items
   * Checkout
   * Payment
   * Delivery 
   * Footer

7. **Profile Page**
   * User Profile
   * Order History
   * Wishlist
   * Address Book
   * Footer

8. **Documentation Page**
    * Terms of Service
    * Privacy Policy
    * Customer Service
    * About Us
    * Returns & Exchange
    * FAQs

# Project Structure

```
Front-end/
│
├── Auth/
│   ├── login.html
│   └── signup.html
│
├── Categories/
│   ├── Electronics.html
│   ├── Men.html
│   └── Women.html
│
├── Documentation/
│   ├── about.html
│   ├── customer-service.html
│   ├── faq.html
│   ├── privacy.html
│   ├── returns.html
│   └── terms.html
│
├── Checkout.html
├── Details.html
├── Home.html
├── Landing.html
├── Profile.html
├── styles.css
└── README.md
```