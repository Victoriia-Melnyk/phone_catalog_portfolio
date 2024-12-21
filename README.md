# **E-Commerce Web Application 🛒**

This is a fully responsive e-commerce web application that allows users to browse, search, and purchase products online. The assortment of products includes mobile phones, tablets and accessories. The application includes features like product slider and swiper, filtering and sorting products, shopping cart management, and category browsing.

---

## **Technologies Used** 🛠️

- **React.js**: A JavaScript library for building user interfaces, enabling a modular and component-driven architecture.
- **React Router** - For navigation and routing management.
- **React Bootstrap** - Prebuilt responsive components and styles.
- **TypeScript**: Used for type safety and better code maintainability.
- **Sass (SCSS) module stylesheet**: Modular and maintainable styling.
- **API Integration**: API calls to fetch products.
- **React Context API**: Global state management for the themes, favourites and cart data.
- **Classnames** - Dynamic className handling.
- **URLSearchParams** - Query parameter management for filtering and sorting.
- **useParams** - React-Router hook that returns a dynamic parameter of the URL.
- **Media Queries** - Responsive design through breakpoints for different devices.
- **Mixins** - Reusable blocks of styles included in different parts of the stylesheet.

---

## **Features** ✨

### **1. Responsive Header with Navigation**

- The header is fully responsive, providing distinct layouts for desktop and mobile views.
- A mobile-friendly menu button is included for easy access to navigation on smaller screens.
- Includes interactive **Favourites and Cart icons** that display real-time item counters, showing the number of items in the cart or saved as favourites.
- Includes **Dark Mode Toggle Button** - users can easily toggle between light and dark modes using a dedicated button in the header.

### **2. Product Slider for Tablet and Desktop**

- Auto-rotating banner slider for displaying promotional images.
- Supports manual navigation buttons and indicators.

### **3. Mobile-Friendly Swiper**

- A responsive image slider optimized for mobile devices, offering smooth navigation and an engaging visual experience.
- Includes clickable pagination dots that indicate the current slide and allow users to jump directly to any slide.

### **4. Browsing products by Category**

- "Shop by category" section with phones, tablets, and accessories.
- Displays the product count for each category.

### **5. Sorting and Filtering**

- Dropdown menus allowing users to sort products by:

  - Newest
  - Alphabetical Order
  - Cheapest

- Allows selection of the number of products displayed per page.

### **6. Easy access to the Product details page**

- Clicking on a product image or name in other parts of the app (e.g., sliders or lists) navigates directly to this details page.
- Displays detailed information about the selected product, including specifications, pricing, and available options like colors and capacities.
- Includes an image gallery that lets users preview different product angles by clicking on thumbnails.
- Offers Add-to-Cart and Add-to-Favourites buttons for seamless shopping and saving preferences.

### **7. Shopping Cart**

- Add and remove products to/from the cart.
- Displays the total price of products in the cart.
- Checkout modal with an option to clear the cart.

### **8. Save items to Favourites**

- Shows a list of favorite products saved by the user for quick access.
- Integrates the ProductsList component to render product cards, each clickable for detailed views, with options to add items to the cart or remove them from favourites.

### **9. Responsive Design**

- Optimized for different screen sizes and devices.

---

## **Preview** 🎉

- **[Live Demo](https://victoriia-melnyk.github.io/phone_catalog_portfolio/)**

---

## **Mockups** 📐

- **[Design Mockup Light mode](https://www.figma.com/design/ID8Ex2rnJO4fRl1UFvZGvR/Phone-catalog-light?node-id=0-1&t=tjydxXRO8zdTqld6-1)**
- **[Design Mockup Night mode](https://www.figma.com/design/k7KKUbfEqAopHNcPEdViYe/Phone-catalog-dark?node-id=0-1&t=CsMrNC12tKiKQbgZ-1)**

---

## **Getting Started** 🚀

Before running this project, make sure you have the following installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) (Version **16.14.0** or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

## **Installation Instructions**

1. **Clone the Repository in your terminal**:

```bash
git clone https://github.com/Victoriia-Melnyk/phone_catalog_portfolio.git
```

2. **Open the cloned project in your IDE (e.g., VSCode)**

3. **Install Dependencies:**

Using npm:

```bash
npm install
```

Or, if you prefer yarn:

```bash
yarn install
```

4. **Start the Development Server:**

Using npm:

```bash
npm start
```

Or with yarn:

```bash
yarn start
```

After running this command, the project will automatically open in your default browser.
