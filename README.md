## E-Commerce Platform
### Description
- The E-Commerce Platform is a full-stack web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to browse products, add items to the cart, and place orders, while administrators can manage products, orders, and users.
- This project demonstrates full-stack development, RESTful API creation, authentication and authorization, and a responsive user interface.

### Features
- User registration and login with JWT authentication
- Product listing, filtering, and search
- Add to cart and place orders
- Admin panel to manage products, orders, and users
- Role-based access control (Admin/User)
- Responsive UI using React.js and Tailwind CSS
- REST API built with Node.js and Express.js
- Persistent storage using MongoDB
- Password encryption using bcrypt

### Tech Stack
- Frontend: React.js, Redux, Tailwind CSS, Modular CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT
- Password Encryption: bcrypt
- File Handling: Multer & Cloudinary
- Frontend Bundler: Vite

### Installation
- Clone the repository
https://github.com/Alok-jena-tech/E-commerce.git

### Backend Setup
- cd backend
- npm install
- npm run dev

### Frontend Setup
- cd ../frontend
- npm install
- npm run dev

### Environment Variables
**Backend**

- PORT → Port number to run the server
- MONGO_URL → MongoDB connection string
- JWT_SECRET_KEY->Secret key for JWT authentication
- CLOUDINARY_CLOUD_NAME ->Cloudinary cloud name for image hosting
- CLOUDINARY_API_KEY ->Cloudinary API key
- CLOUDINARY_API_SECRET ->Cloudinary API secret

**Frontend**

- VITE_BACKEND_URL → Backend API URL
- VITE_PAYPAL_CLIENT_ID ->PayPal client ID for payment integration

## Usage

1. **Browse Products Without Login**  
   - Users can visit the site, explore products, and add items to the cart without creating an account.

2. **Proceed to Checkout**  
   - To place an order, users must login or register before making a payment.  
   - Users are prompted to provide a delivery address before proceeding to payment.

3. **Payment & Order Confirmation**  
   - After entering the delivery address, users can complete payment using PayPal integration.  
   - Once payment is successful, the order is confirmed, and the user is redirected to a confirmation page.

4. **Admin Dashboard (For Admin Users)**  
   - Admins can login to manage the platform.  
   - Features include adding, updating, or deleting products, viewing orders, and managing users.

5. **Cart Management**  
   - Users can add/remove products, view the cart, and update quantities both before and after login.

### Acknowledgements

- MongoDB – Database management
- Express.js – Backend APIs
- React.js – Frontend development
- Redux – State management in React
- JWT – Authentication
- bcrypt – Password encryption
- Vite – Frontend bundling
- Multer – File uploads
- Cloudinary – Image hosting and storage
- Tailwind CSS – Styling and responsive UI
