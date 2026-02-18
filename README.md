# Chinese Auction Client

This is a Chinese Auction Management System built with Angular. The application provides a seamless and interactive experience for users to browse prize packages, purchase tickets, and participate in raffles

This project is the frontend client built with Angular. It communicates with a REST API in the following link:
[Backend Repository](https://github.com/naama-git/chinese-auction-api.git))

## Key Features
### User Experience & Catalog

-  Dynamic Prize Catalog: Browse and filter prizes by categories and contributors with a interactive UI.

-  Advanced Shopping Cart: Manage ticket selections with a persistent cart system and a seamless checkout process.

-  Secure Authentication: User registration and login system for a personalized experience.

### Admin & Management

-  Full CRUD Management: Complete control over prizes, donors, categories, and ticket packages.

-  Role-Based Access Control (RBAC): Granular permissions for viewing sensitive data like orders and contributor lists.

- Automated Raffle Engine: Tools for conducting draws and generating instant winner announcements.

- Financial Analytics: Detailed reporting on raffle revenue, ticket sales, and prize distribution.


## Project Gallery
*Visual interface and user experience of the Chinese Auction platform.*

<details>
  <summary><b>Click to expand the full image gallery</b></summary>
  <br>

  ## User Interface (Client Side)
  
  ### Full Page Previews
  *Below are the main entry points for customers, displayed in full width for detailed inspection.*

  #### Main Landing Page
  <img src="screenshots/home_page.png" width="100%" alt="Full Home Page View">

  <br>

  #### Prizes Catalog
  <img src="screenshots/prizes_view_full.png" width="100%" alt="Full Prizes Catalog View">

  ---

  ### Authentication & System States
  | Sign In | Sign Up | Page Not Found (404) |
  | :---: | :---: | :---: |
  | <img src="screenshots/user_login.png" width="280"> | <img src="screenshots/user_signin.png" width="280"> | <img src="screenshots/not_found.png" width="280"> |

  <br>

  ### Checkout Flow
  *The step-by-step process of purchasing tickets and bundles.*

  | Step 1: Package Selection | Step 2: Information | Step 3: Success |
  | :---: | :---: | :---: |
  | <img src="screenshots/order_step1.png" width="250"> | <img src="screenshots/order_step2full.png" width="350"> | <img src="screenshots/order_step3.png" width="250"> |

  <br>

  **Additional User Views:**
  <div style="display: flex; overflow-x: auto; gap: 10px; padding-bottom: 10px;">
    <img src="screenshots/cart_view.png" width="300" alt="Shopping Cart">
    <img src="screenshots/prize_one_view.png" width="300" alt="Single Prize View">
    <img src="screenshots/packages_view.png" width="300" alt="Packages Overview">
  </div>

  ---

  ## Admin Dashboard (Management Side)
  
  ### Admin Inventory Control
  *Specialized management interface with administrative functions and advanced controls.*

  #### Prize Management (Admin View)
  <img src="screenshots/prizes_view_admin.png" width="100%" alt="Admin Prize Management Dashboard">

  <br>

  #### Donor Management (Full View)
  <img src="screenshots/donors_view_full.png" width="100%" alt="Full Donor Management">

  ---

  ### Admin Tools & Activity
  | Add New Donor | Orders Overview | Analytics Reports |
  | :---: | :---: | :---: |
  | <img src="screenshots/donor_add.png" width="280"> | <img src="screenshots/orders_view.png" width="280"> | <img src="screenshots/reports_view.png" width="280"> |

  <br>

  ### System Operations & Utilities
  *Internal administrative functions and status indicators.*
  <div style="display: flex; overflow-x: auto; gap: 10px; padding-bottom: 10px;">
    <img src="screenshots/total.gif" width="300" alt="Total Calculation Admin">
    <img src="screenshots/user_logout.gif" width="300" alt="Admin Logout Animation">
    <img src="screenshots/packages_admin.png" width="300" title="Admin Packages">
    <img src="screenshots/prize_add.png" width="300" title="Add Prize">
    <img src="screenshots/prize_delete.png" width="300" title="Delete Prize">
    <img src="screenshots/order_one_view.png" width="300" title="Order Details">
    
  </div>


</details>

##  Getting Started
Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Ensure you have the following installed:
- Node.js (Recommended: v18.13.0+ or v20.x)
- npm (comes with Node.js)
- Angular CLI: Install it globally using:
  
  ```
  $ npm install -g @angular/cli
  ```

### Installation
1. Clone the repository:
   ```
   $ git clone https://github.com/Lea2166/ChineseAuctionClient.git
   ```
   
2. Navigate to the project directory:
   ```
   $ cd ChineseAuctionClient
   ```

3. Install dependencies:
   ```
   $ npm install
   ```
### Running the application:
1. Start the developer server
   ```
   $ ng serve
   ```
2. Open your browser: Navigate to https://localhost:4200/. The application will automatically reload if you change any of the source files.
   




