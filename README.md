# Marketplace Technical Foundation - Furniro E-Commerce  

## Day 1: Establishing the Marketplace Foundation  
Furniro E-Commerce is designed to deliver a seamless and efficient shopping experience.  

### Key Features  
- **Smooth Shopping Experience** – A user-friendly interface for hassle-free browsing and purchasing.  
- **Product Comparison** – Easily compare products to make informed buying decisions.  
- **Wishlist & Favorites** – Save liked products for future reference.  

## Day 2: Planning the Technical Architecture  

### Frontend Requirements  
- **Framework:** Next.js  
- **Core Pages:** Home, About, Product Listing, Cart, Checkout, Product Comparison, Blog, Contact  
- **Dynamic Product Pages:** `/product/[id]` for individual product details  

### Backend Requirements  
- **CMS:** Sanity CMS  
- **Data Management:**  
  - Product details  
  - Orders  
  - Customer information  
  - Delivery zones  
  - Shipment tracking  

### Third-Party Integrations  
- **Shipment Tracking:** ShipEngine  
- **Payment Processing:** Stripe  

## Day 3: API Integration and Data Migration  

On Day 3, we integrate Sanity CMS into our Next.js project, migrate data, and fetch it for display in the browser.  

### Step 1: Setting Up Sanity CMS  
1. **Open the Next.js Project** – Ensure you have a running Next.js project.  
2. **Install Sanity CMS** – Run the following command in your terminal to create a new Sanity project:  
   ```sh
   npm create sanity@latest -- --template clean --create-project "learning-sanity-project" --dataset production

## Day 4: Building Dynamic Frontend Components  

### Key Components  

- **Search Bar** – Implements dynamic routing for product search.  
- **Product Listing** – Fetches and displays products from Sanity.  
- **Product Detail** – Uses dynamic routing to show product details.  
- **Cart** – Manages cart operations using Redux.  
- **Wishlist** – Saves and manages liked products.  
- **Checkout Workflow** – Handles cart review, sign-in, and shipping details.  
- **Product Comparison** – Compares two products side by side.

## Day 5: Testing, Error Handling, and Backend Integration Refinement  

### Key Test Cases  
- **Product Listing** – Ensure products display correctly.  
- **Product Detail Page** – Validate dynamic product details.  
- **Add to Cart** – Test product addition functionality.  
- **Search Bar** – Verify accurate search results.  
- **Wishlist** – Ensure products can be added successfully.  
- **Product Comparison** – Validate comparison functionality.  

### Cross-Browser & Responsive Testing  
- **Edge Browser** – Ensure smooth functionality.  
- **Mobile & Tablet** – Validate perfect responsiveness.  
- **Performance Check** – Target website performance at **76%**.

## Day 6: Preparing for Deployment & Staging Environment  

### Deployment Overview  
- **GitHub Repository:** [Hackathon-Furniro-E-Commerce-Website](https://github.com/javed-ali92/Marketplace-Technical-Foundation-E-Commerce-Website)  
- **Staging Site URL:** [Furniro](https://hacathon-furniro.vercel.app/)  

### Deployment Steps  
1. **Configure Hosting** – Set up the project on Vercel.  
2. **Environment Variables** – Secure API keys and credentials.  
3. **CORS Configuration** – Allow Sanity data access.  
4. **Deploy to Staging** – Publish the website for testing.  

### Performance Testing Results  
- **Desktop Performance:** 76%  
- **Mobile Performance:** 61%

In just six days, we've established a strong base for a scalable and intuitive e-commerce platform. With ongoing improvements, the marketplace is ready to provide an outstanding shopping experience.  
