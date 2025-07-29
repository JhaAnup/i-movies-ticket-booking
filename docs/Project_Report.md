# Movie Ticket Booking System  
**By Anup Kumar Jha**  

## 🎯 Project Overview  
A production-ready cinema booking platform featuring:  
- **User Portal**: Real-time seat selection • Secure payments • Feedback system  
- **Admin Dashboard**: Movie management • Revenue analytics • Showtime scheduling  
- **Tech Stack**:  
  ![MongoDB](https://img.shields.io/badge/MongoDB-6.0+-47A248?logo=mongodb&logoColor=white)  
  ![Express](https://img.shields.io/badge/Express-4.x-000000?logo=express&logoColor=white)  
  ![React](https://img.shields.io/badge/React-18.x-61DAFB?logo=react&logoColor=white)  
  ![Node.js](https://img.shields.io/badge/Node.js-20.x-339933?logo=nodedotjs&logoColor=white)  

---

## ✨ Key Features  
### User Experience  
- 🔐 JWT Authentication  
- 🎬 Interactive Seat Mapping with Real-Time Availability  
- 💳 Stripe/PayTM Payment Gateway  
- ⭐ Rating & Feedback System  

### Admin Capabilities  
- 🎥 Movie CRUD Operations  
- 🕒 Dynamic Showtime Management  
- 📊 Booking Analytics Dashboard  
- 📝 Feedback Moderation Tools  

---

## 🚀 Installation Guide  
### Prerequisites  
- Node.js v20+  
- MongoDB v6+  
- npm v9+  

### Setup  
```bash
# Clone and setup
git clone https://github.com/JhaAnup/i-movies-ticket-booking.git
cd i-movies-ticket-booking

# Backend Configuration
cd Backend
npm install
cp .env.example .env  # Set MONGODB_URI and JWT_SECRET
npm start  # Starts on port 5000

# Frontend Setup (in new terminal)
cd ../Frntend
npm install
npm run dev  # Starts Vite dev server
