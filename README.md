# Talaash Portal

**Talaash Portal** is a platform dedicated to reuniting missing individuals with their families through police assistance. It leverages a nationwide network, real-time updates, and verified reports to streamline the search process, offering hope and support to those in need.

## **Table of Contents**
- About
- Technologies Used
- Features
- Installation
- Usage
- API Endpoints
- Contributing
- License

## **About**
Talaash Portal is committed to providing solace, empowerment, and connection to individuals facing the distress of missing loved ones. Our mission is to create a safe and compassionate space where people can share experiences, seek advice, and find the support they need.

## **Technologies Used**
### **Frontend**
- **React**: UI development.
- **Vite**: Fast build tool.
- **Tailwind CSS**: Utility-first CSS framework.
- **DaisyUI**: Customizable UI components.
- **React Router**: Routing management.
- **React Query**: Data fetching and caching.
- **React Icons**: Icon library.
- **React Hot Toast**: Notifications.

### **Backend**
- **Node.js**: Server runtime.
- **Express**: Web framework.
- **MongoDB**: NoSQL database.
- **Mongoose**: ODM for MongoDB.
- **JWT**: Authentication.
- **Cloudinary**: Image and video management.
- **Bcrypt.js**: Password hashing.
- **Dotenv**: Environment variables.

## **Features**
- **User Authentication**: Sign up, login, logout.
- **Profile Management**: Update profile, cover images.
- **Post Management**: Create, delete, like/unlike, comment.
- **Notifications**: Likes, follows.
- **Follow System**: Follow/unfollow users.
- **Suggested Users**: Discover new connections.
- **Responsive Design**: Optimized for all devices.

## **Installation**
1. **Clone the repository**
2. **Install backend dependencies**
3. **Install frontend dependencies**
4. **Create a `.env` file** in the Portal directory and configure environment variables

## **Usage**
1. **Start the backend server**
2. **Start the frontend development server**
3. **Open browser** at `http://localhost:3000`

## **API Endpoints**
### **Auth Routes**
- `POST /api/auth/signup` - Register a new user
- `POST /api/auth/login` - Authenticate user
- `POST /api/auth/logout` - Logout
- `GET /api/auth/me` - Get authenticated user details

### **User Routes**
- `GET /api/users/profile/:username` - Get user profile
- `GET /api/users/suggested` - Get suggested users
- `POST /api/users/follow/:id` - Follow/unfollow user
- `POST /api/users/update` - Update user profile

### **Post Routes**
- `GET /api/posts/all` - Get all posts
- `GET /api/posts/following` - Get followed users' posts
- `GET /api/posts/likes/:id` - Get liked posts
- `GET /api/posts/user/:username` - Get user posts
- `POST /api/posts/create` - Create post
- `POST /api/posts/like/:id` - Like/unlike post
- `POST /api/posts/comment/:id` - Comment on post
- `DELETE /api/posts/:id` - Delete post

### **Notification Routes**
- `GET /api/notifications` - Fetch notifications
- `DELETE /api/notifications` - Clear notifications

## **Contributing**
We welcome contributions! Fork the repository and submit a pull request.

## **License**
This project is licensed under the **MIT License**.

