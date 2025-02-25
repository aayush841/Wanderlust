# Wanderlust - Hotel Booking Engine

## 📌 Overview
Wanderlust is a **feature-rich hotel booking platform** that provides users with a seamless rental experience. The application allows users to browse, book, and review hotels while ensuring a secure and responsive interface.

## 🚀 Features
- **User Authentication**: Secure login and registration using **PassportJS**.
- **Hotel Listings**: Browse available hotels with images and descriptions.
- **Reviews & Ratings**: Users can leave reviews and ratings for hotels.
- **Cloud Image Storage**: Integrated **Cloudinary** for efficient image storage.
- **RESTful API**: Backend powered by **Express.js & Node.js**.
- **MVC Architecture**: Ensures clean and maintainable code structure.
- **Responsive UI**: Built with **Bootstrap** for a mobile-friendly experience.
- **Error Handling**: Robust handling of API failures and user errors.

## 🛠️ Technologies Used
- **Frontend**: HTML, CSS, Bootstrap, JavaScript (EJS for templating)
- **Backend**: Node.js, Express.js, MongoDB, PassportJS
- **Database**: MongoDB with Mongoose ODM
- **Cloud Storage**: Cloudinary
- **Authentication**: PassportJS (Local Strategy, OAuth)


## 🚀 Installation & Setup
To set up and run Wanderlust locally, execute the following commands:


# 1️⃣ Clone the Repository
```sh
git clone https://github.com/aayush841/wanderlust.git  
cd wanderlust  
```

# 2️⃣ Install Dependencies  
```sh
npm install
```

# 3️⃣ Set Up Environment Variables  
```sh
touch .env  
echo "MONGO_URI=your_mongodb_connection_string" >> .env  
echo "CLOUDINARY_CLOUD_NAME=your_cloud_name" >> .env  
echo "CLOUDINARY_API_KEY=your_api_key" >> .env  
echo "CLOUDINARY_API_SECRET=your_api_secret" >> .env  
echo "SESSION_SECRET=your_session_secret" >> .env  
```

# 4️⃣ Start the Server 
```sh
nodemon app.js
``` 
