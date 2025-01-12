# Restaurant Review System

Welcome to the **Restaurant Review System**! This project is a comprehensive platform designed to allow users to discover restaurants, share their dining experiences, and make informed decisions based on authentic reviews. Built as part of our MSc final year project, it demonstrates our expertise in software engineering principles and modern development practices.

---

## 🌟 Features

- **User Registration and Authentication**: Secure account creation and login.
- **Restaurant Listings**: Explore restaurants by location, cuisine, or popularity.
- **Ratings and Reviews**: Submit detailed reviews, rate restaurants, and read feedback from other users.
- **Search and Filter**: Intuitive search and filtering options for personalized restaurant discovery.
- **Admin Dashboard**: Manage restaurant data and moderate reviews efficiently.
- **Interactive Map**: Locate restaurants using an integrated map.

---

## 💻 Technologies Used

### **Frontend**
- React.js
- Bootstrap / Tailwind CSS
- Axios

### **Backend**
- Node.js (Express.js)
- MongoDB (Database)
- JWT (Authentication)

### **Other Tools**
- Postman (API Testing)
- Docker (Containerization)
- Git & GitHub (Version Control)

---

## 🚀 Installation

Follow these steps to set up the project locally:

### Prerequisites
- Node.js installed (v16 or higher)
- MongoDB installed locally or access to a MongoDB Atlas cluster
- Docker (optional, for containerized setup)

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/restaurant-review-system.git
   cd restaurant-review-system
   ```

2. **Install Dependencies**:
   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the backend folder with the following:
   ```env
   PORT=5000
   MONGO_URI=your-mongodb-uri
   JWT_SECRET=your-jwt-secret
   ```

4. **Run the Application**:
   - **Backend**:
     ```bash
     cd backend
     npm start
     ```
   - **Frontend**:
     ```bash
     cd frontend
     npm start
     ```

5. **Access the Application**:
   Open your browser and navigate to `http://localhost:3000`.

---

## 📂 Project Structure

```
restaurant-review-system/
├── backend/          # Backend code (Node.js/Express)
├── frontend/         # Frontend code (React.js)
├── docs/             # Documentation and design artifacts
├── docker-compose.yml # Docker configuration (optional)
└── README.md         # Project documentation
```

---

## 📖 Documentation

Detailed documentation, including API specifications, database schema, and use case diagrams, is available in the `docs` folder. Key files include:
- `API_Documentation.md`
- `ER_Diagram.png`
- `Use_Case_Diagram.pdf`

---

## 🛠️ Future Enhancements

- **AI-Powered Recommendations**: Personalized suggestions based on user preferences.
- **Integration with Social Media**: Share reviews and ratings on popular platforms.
- **Mobile App**: Native Android/iOS applications for an enhanced user experience.
- **Real-time Notifications**: Alerts for new reviews, offers, and updates.

---
