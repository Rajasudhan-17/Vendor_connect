# Vendor_connect

# 📄 VendorConnect

**VendorConnect** is a feature-rich, responsive web platform that connects street vendors with customers for a seamless grocery and essentials shopping experience, including maps, reviews, and real-time cart management and serves as a source of information for the vendors to locate the nearby stores and knowing the prices of the products as this platform do not have any third party to increase the price for the profit. The vendors can purchase the products from the store through online or can find the suppliers and compare the prices and find the way to the shop through the map and buy them without delivery charge.

---

## 🌐 Real-Time Location & Personalization

- **Live Location Detection**  
  Uses browser geolocation API to detect and display the user’s current location.

- **Guest and Logged-in User Modes**  
  Users can browse as "Guest" or log in with default credentials for a personalized experience.

- **Persistent Sessions**  
  Stores login and cart information using `localStorage`.

---

## 🔍 Search, Filter & Sort System

- **Search Bar**  
  Live filtering of suppliers/products by keywords.

- **Category Filters**  
  Filter items by product type (e.g., Vegetables, Fruits, Grains, Dairy).

- **Smart Sorting**  
  Options like:
  - Nearest First
  - Highest Rated
  - Lowest Delivery Charges
  - Alphabetical Order

---

## 🛒 Supplier & Product Listings

- **Dynamic Supplier Cards**  
  Each supplier displays:
  - Trust Score
  - Location
  - Speciality
  - Established Year
  - Number of Reviews

- **Product Cards**  
  View product name, price, category, emoji icon, and quantity controls.

- **Add to Cart**  
  Button to add items directly to the cart with quantity selection.

---

## 📦 Cart & Checkout System

- **Interactive Cart Sidebar**  
  Updates in real time with subtotal, delivery charge, and final total.

- **Checkout Modal**  
  - Enter delivery address  
  - Choose payment method (COD, UPI, Card)  
  - Confirm and place order

---

## 🗺️ Map Integration & Routing

- **Leaflet.js Integration**  
  Visual display of vendor and user locations on a styled map.

- **Route Planner**  
  - Enable routing mode  
  - View distance and estimated time  
  - Clear or open route in Google Maps

- **Live Marker Animations**  
  Active vendor markers pulse to attract user focus.

---

## ⭐ Reviews & Ratings

- **Customer Reviews Display**  
  Each supplier card shows customer reviews with author, rating, and feedback.

- **Rate a Supplier**  
  - Submit star ratings  
  - Leave a written review

---

## 📜 Order History & Reordering

- **Order Timeline View**  
  Status tracking with stages: Confirmed → Processing → Shipped → Delivered

- **Order Summary Section**  
  - View items, prices, delivery address, payment method  
  - Reorder functionality

- **Stats Cards**  
  Display total orders, total spent, delivered orders, and active orders.

- **Search & Filter Orders**  
  Search by order ID or product, and filter by order status.

---

## 🔐 Default Login

- **Credentials (for demo purposes):**  
  - Email: `vendor@example.com`  
  - Password: `password123`
