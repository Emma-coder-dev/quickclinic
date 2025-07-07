# 🚑QuickClinic

QuickClinic is a modern, full-stack web application that offers fast, reliable, and accessible medical consultations. It enables patients to book appointments, consult doctors remotely, and manage their healthcare from any device. Built with a responsive design, secure role-based access, and real-time email notifications, QuickClinic is designed to improve healthcare access, especially in underserved areas.



## 📱Live Project

- **Frontend**: [https://quickclinic-iota.vercel.app](https://quickclinic-iota.vercel.app)  
- **Pitch Deck**: [View on Gamma](https://gamma.app/docs/QuickClinic-b7s7g0ymbqb6duk)  
- **Email**: [kagenineema@gmail.com](mailto:kagenineema@gmail.com)



## Key Features

- Patient, Doctor, and Admin roles with JWT-secured login  
- Appointment booking and viewing system  
- Admin dashboard for user and doctor management  
- Email confirmation and notifications using Nodemailer  
- Dark mode support  
- Fully mobile-responsive UI  
- Deployed backend on Render  
- Deployed frontend on Vercel  
- Database hosted on MongoDB Atlas  



## Tech Stack

### Frontend

- HTML, CSS, JavaScript (or React)  
- Tailwind CSS or Bootstrap (if used)  
- Axios for API communication  
- Vercel for deployment  

### Backend

- Node.js & Express.js  
- MongoDB with Mongoose  
- JSON Web Tokens (JWT) for authentication  
- Nodemailer for email functionality  
- Render for backend deployment  

---

## Setup Instructions (Development)

```bash
# Step 1: Clone the Repository
git clone https://github.com/your-username/quickclinic.git
cd quickclinic

# Step 2: Install Backend Dependencies
npm install

# Step 3: Create a .env File
# Create a .env file in the root directory and add the following:
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email_address
EMAIL_PASS=your_app_password
FRONTEND_URL=http://localhost:3000

# Step 4: Start the Backend Server
npm run dev
# Visit: http://localhost:5000

# Step 5: (Optional) Setup Frontend
cd client
npm install
npm run dev

# In the client/.env file, add:
VITE_BACKEND_URL=http://localhost:5000
```



## Project Structure

```
quickclinic/
├── controllers/         # Logic for users, appointments, etc.
├── models/              # Mongoose schemas
├── routes/              # API endpoints
├── middleware/          # Auth and error handling
├── utils/               # Utility functions like sendEmail
├── config/              # DB connection and config files
├── server.js            # Main backend server file
├── .env                 # Local environment config
└── README.md            # Project documentation
```


## Deployment Summary

| Layer     | Platform       | Status      |
|-----------|----------------|-------------|
| Frontend  | Vercel         | ✅ Live      |
| Backend   | Render         | ✅ Running   |
| Database  | MongoDB Atlas  | ✅ Connected |



## Project Progress

- [x] Backend API deployed and stable  
- [x] MongoDB Atlas integration successful  
- [x] Role-based authentication implemented  
- [x] Appointment system and email notifications complete  
- [x] Frontend mobile-responsive and live  
- [ ] UI polishing and admin features in progress  


## Author

**Neema Kageni**  
✉️ Email: [kageni@gmail.com](mailto:kagenineema@gmail.com)
