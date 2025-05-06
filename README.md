# Rentify

**Rentify** is a full-stack MERN application that enables users to post products for rent and rent products from others. The platform features secure authentication (with OTP email verification), robust product management, and a seamless user experience for both renters and owners.

---

## 🚀 Features

- **User Authentication**
  - Secure registration and login with OTP email verification.
- **Profile Management**
  - Users can update their profile information.
- **Product Management**
  - Add new items for rent with photos and detailed descriptions.
  - Owners can delete their own items.
  - Owners can view and manage their list of posted items.
- **Product Browsing**
  - Browse all available products for rent.
  - Filter and search items by name and date.
- **Renting System**
  - Select rental dates using an intuitive date picker.
  - Rent products and manage your rental history.
- **Image Uploads**
  - Upload product images, stored securely with Cloudinary.
- **Responsive Design**
  - Optimized for both desktop and mobile devices.

---

## 🛠️ Tech Stack

### Frontend

- **React.js** – UI development
- **React Router DOM** – Client-side routing
- **Axios** – HTTP requests
- **React Datepicker** – Date selection
- **Jest & React Testing Library** – Testing

### Backend

- **Node.js & Express.js** – REST API server
- **MongoDB & Mongoose** – Database & ORM
- **Passport.js** – Authentication (Google OAuth)
- **Nodemailer** – Email OTP verification
- **Cloudinary** – Image storage
- **Multer** – File uploads
- **bcryptjs** – Password hashing
- **dotenv** – Environment variable management
- **CORS** – Cross-origin resource sharing

---

## 📦 Project Structure
```
rentify/
├── backend/ # Express.js API & MongoDB
└── frontend/ # React.js client 
```


---

## 📝 Installation & Setup

### Prerequisites

- [Node.js](https://nodejs.org/) (v16+ recommended)
- [MongoDB](https://www.mongodb.com/) (local or Atlas)
- [Cloudinary Account](https://cloudinary.com/) (for image uploads)
- [Google OAuth Credentials](https://console.developers.google.com/) (optional)

---

### 1. Clone the Repository

```
git clone https://github.com/anuragksng/Rentify.git
cd rentify
```


---

### 2. Backend Setup

```
cd backend
npm install
```


Create a `.env` file in `/backend` with the following:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```


Start the backend server:

```
npm start
```

Backend runs on `http://localhost:5000` by default.

---

### 3. Frontend Setup

```
cd ../frontend
npm install
```


Start the frontend server:

```
npm start
```
Frontend runs on `http://localhost:3000` by default.

---

## 🧪 Running Tests

Frontend tests (React Testing Library):

```
npm test
```

---

## 💡 Usage

1. **Register** with your email and verify via OTP.
2. **Login** to your account.
3. **Update your profile** information anytime.
4. **Add a new product** for rent with images and detailed description.
5. **Browse and search** for products by name or date.
6. **Filter items** to find what you need quickly.
7. **Rent a product** by selecting available dates.
8. **Manage your listings**: Owners can view, update, or delete their own items.
9. **View your rental history** and active rentals.

---

