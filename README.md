# EndOfSem_Canteen
# Canteen Ordering System - Koranteng's Canteen
# OVERVIEW
Koranteng's Canteen is a responsive web application for a restaurant that provides interactive features that allows customers to do things such as:
- View the restaurant's menu.
- Allow customers to browse through various food offerings.
- Log in / Sign up to create accounts; Adding any dietary restrictions or allergies. As well edit their accounts after creating them.
- Earn and redeem loyalty points to gain discounts on future orders.
- Search and filter for specific meals they want.
- Customize their orders to add or remove anything they want as well as to view the nutritional facts about the menu.
- View and edit their cart, as well as view the sub-total/total for their orders.
- Track their orders after ordering it in different phases (Order Received, Preparing, Ready, Completed)
- View order history.

# Deployment link - Netlify
https://korantingscafe.netlify.app/menu

# Login Details
A customer can sign up with a new gmail account and log in using the same credentials but another customer can't sign up using the same gmail as they will get this error:

<img width="468" alt="Screenshot 2024-12-14 at 12 04 55 PM" src="https://github.com/user-attachments/assets/12f923af-34e4-49df-ad2a-1807e2cc85be" />

A previous customer can log in though:

<img width="460" alt="Screenshot 2024-12-14 at 12 09 50 PM" src="https://github.com/user-attachments/assets/de27b8fe-bf22-4d89-a318-9ba4a99e4068" />


# Feature Checklist
1. User Registration & Profile Management
- ✔ Implement a secure registration and login system.
- ✔ Store user preferences, including dietary restrictions and allergies.

3. Menu Display & Customization 
- ✔ Display menu items with options for customization (e.g., extra toppings).
- ✔ Each menu item must include details like item name, price, category, and nutritional
information.

5. Ordering System with Cart 
- ✔ Implement a cart where users can add items, view order totals, and place orders.
- ✔ Allow users to review and adjust their orders before confirming.

5. Order Tracking & Loyalty Program 
- ✔ Enable users to track their order status (e.g., Preparing, Ready for Pickup).
- ✔ Implement a loyalty system where users earn points for each order, redeemable for
discounts.

# Installation Instructions
Prerequisites:
Before running this project, make sure you have the following installed on your computer:
- Node.js (v14.0.0 or higher)
- npm (comes with Node.js)
- Git

# Step-by-Step Installation Instructions
1. Clone the Repository
git clone https://github.com/Katopoco/EndOfSem_Canteen.git

2. Navigate to Project Directory
cd EndOfSem_Canteen

3. Install Dependencies
npm install

4. Start the Development Server
npm run dev

5. Access the Application
http://localhost:5173

Optional: Troubleshooting Permission Issues
Should in-case you encounter permission issues when running npm run dev, try the following instructions:
1. Fix permissions for Vite
chmod +x node_modules/.bin/vite

2. Reinstall dependencies if needed
rm -rf node_modules package-lock.json
npm install

After this is resolved, you can start the installation instruction again.

# API Documentation
These are the screenshots of my API TESTING on Postman:
1. Authentication Endpoints
- Register Endpoint Screenshot

<img width="960" alt="registeration 1" src="https://github.com/user-attachments/assets/dde5661e-50b9-4d6d-a2f6-e864994d659c" />

- Login Endpoint Screenshot

<img width="960" alt="login" src="https://github.com/user-attachments/assets/e85640fb-99ed-4b53-91bc-cbccf5b164d1" />

- Create Order Endpoint Screenshot

<img width="958" alt="create order" src="https://github.com/user-attachments/assets/ee025ef0-b439-4350-8a7f-9c5df2fe6996" />

- Get Order Endpoint Screenshot

<img width="960" alt="get order" src="https://github.com/user-attachments/assets/4ad1e7bb-cccd-4d28-875d-0bea18eeaf3c" />

- Order Updates Endpoint Screenshot

<img width="958" alt="order update" src="https://github.com/user-attachments/assets/52c14c9b-9cfe-43fc-9fac-080bdcabb92a" />





















