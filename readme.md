![RoommateFinder Screenshot](https://i.postimg.cc/z3ZVcWr4/Screenshot-234.png)

---

# 🏠 RoommateFinder

## 🌐 Live Site

🔗 [https://roommatefinder0.netlify.app/](https://roommatefinder0.netlify.app/)

---

## 🚀 Project Overview

Roommate Finder is a platform that helps users find compatible roommates based on location, budget, lifestyle preferences, and interests.  
Users can create profiles, browse listings, add their own posts, and connect with potential roommates.

---

## ✨ Features

- 🔐 **User Authentication:** Email/password and Google OAuth login & registration.
- 🚧 **Protected Routes:** Add Listing, Details, Update, My Listings pages are accessible only when logged in.
- 📝 **CRUD Operations:** Users can create, view, update, and delete their roommate posts.
- ❤️ **Like Functionality:** Users can like posts multiple times except their own. Like count updates dynamically.
- 📞 **Contact Reveal:** Contact number is hidden by default and shown only after liking a post.
- 📱 **Responsive Design:** Fully responsive across mobile, tablet, and desktop devices.
- 🌗 **Dark/Light Mode Toggle:** Toggle between dark and light themes on the home page.
- 🎉 **Animations & UI Enhancements:** Uses React Awesome Reveal, React Simple Typewriter & SweetAlert2 for smooth UI and notifications.
- ⏳ **Loading States:** Loading spinners while fetching data.
- 🎨 **Clean & Unique Design:** Inspired by ThemeForest but fully customized for uniqueness.

---

## 🛠 Technologies Used

- React 19
- Vite
- Firebase Authentication
- MongoDB (Backend)
- React Router DOM v7
- Tailwind CSS + DaisyUI
- React Icons
- React Toastify
- SweetAlert2
- Swiper (Carousel)

---


## 🛠️ Run Locally

Follow these steps to set up **RoommateFinder** on your local machine:

```bash
# 1️⃣ Clone the repository
git clone https://github.com/JanayedHossain/RoommateFinder-Client.git

# 2️⃣ Install dependencies
npm install

# 3️⃣ Create a .env file in the root directory and add your environment variables
VITE_API_KEY=your_api_key
VITE_API_URL=your_api_url

# 4️⃣ Start the development server
npm run dev
