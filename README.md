# 🏨 Eden Suite Client - Hotel Booking System Frontend

A modern, responsive React application for Eden Suite, a luxury hotel booking platform. Built with React, Vite, Tailwind CSS, and DaisyUI.

## 🌐 Live URL

- **Frontend Client:** [https://eden-suite-client.vercel.app/](https://eden-suite-client.vercel.app/)
- **Backend API:** [https://eden-suite-server.vercel.app](https://eden-suite-server.vercel.app) 

---

## 🎯 Overview

Eden Suite Client is a feature-rich, production-ready frontend application that provides a seamless hotel booking experience. Users can browse rooms, check availability, book stays, and read reviews.

### Key Highlights

- ✅ **Modern UI/UX** - Built with Tailwind CSS and DaisyUI
- ✅ **Room Booking** - Real-time availability and booking
- ✅ **Authentication** - Secure login and registration with Firebase
- ✅ **Responsive Design** - Mobile-first approach
- ✅ **Real-Time Reviews** - User testimonials and ratings
- ✅ **Interactive Maps** - Location visualization with Pigeon Maps
- ✅ **Secure Routes** - Protected routes for authenticated users

---

## 🚀 Features

### 🔐 Authentication

- **Login/Register** - Secure authentication with Email/Password and Social Login
- **Private Routes** - access control for booking and profile management

### 🏨 Room Management

- **Browse Rooms** - View a list of available rooms with price and details
- **Room Details** - Comprehensive information including images and amenities
- **Filter** - Filter rooms by price range

### 📅 Booking System

- **Book a Room** - effortless booking process
- **My Bookings** - View and manage personal bookings
- **Update Booking** - Modify dates or details of existing bookings

### 💬 Reviews

- **Testimonials** - Read what other guests depend say
- **Add Review** - Share your experience

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **React** | UI framework |
| **Vite** | Build tool |
| **Tailwind CSS** | Styling |
| **DaisyUI** | Component library |
| **Firebase** | Authentication |
| **React Router** | Routing |
| **Axios** | HTTP client |
| **React Datepicker** | Date selection |
| **Swiper** | Carousels |
| **SweetAlert2** | Alerts and notifications |
| **React Icons** | Iconography |

---

## 📁 Project Structure

```
Eden-Suite-Client/
├── src/
│   ├── components/       # Reusable components
│   ├── layouts/          # Layout components (Main, etc.)
│   ├── Pages/            # Page components
│   │   ├── Home.jsx
│   │   ├── Login.jsx
│   │   ├── Rooms.jsx
│   │   ├── MyBook.jsx
│   │   └── ...
│   ├── routes/           # Route definitions
│   ├── provider/         # Context providers (Auth, etc.)
│   ├── firebase/         # Firebase configuration
│   └── assets/           # Static assets
├── public/               # Static public files
└── ...
```

---

## ⚙️ Environment Variables

Create a `.env` file in the root directory:

```env
# API Configuration
VITE_URL=http://localhost:5000

# Firebase Configuration
VITE_apiKey=your_api_key
VITE_authDomain=your_auth_domain
VITE_projectId=your_project_id
VITE_storageBucket=your_storage_bucket
VITE_messagingSenderId=your_sender_id
VITE_appId=your_app_id
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Eden-Suite-Client.git
   cd Eden-Suite-Client
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

4. **Run development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

---

## 📄 License

This project is licensed under the ISC License.

---

## 👨‍💻 Author

**Farhad Hossen**
- GitHub: [@Farhad25906](https://github.com/Farhad25906)
- Email: farhadhossen2590@gmail.com