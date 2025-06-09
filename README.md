# Product Store - MERN Stack Application 🛍️

A full-stack e-commerce product management application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) and styled with Chakra UI.

## 🌐 Live Demo

Check out the live application: [Product Store](https://productstore-uqd6.onrender.com/)

## 📸 Screenshots

![Product Store Homepage](https://asset.cloudinary.com/dsrglevcv/ecbd0a519ddd5b4a52bc39f51248eb72/)

## ✨ Features

- **Full CRUD Operations**: Create, Read, Update, and Delete products
- **RESTful API**: Built with Node.js and Express.js
- **Modern UI**: Clean and responsive interface using React.js and Chakra UI
- **Database Integration**: MongoDB for data persistence
- **Error Handling**: Comprehensive error handling for better user experience
- **Dark/Light Mode**: Toggle between dark and light themes
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Real-time Updates**: Instant UI updates after CRUD operations
- **Toast Notifications**: User-friendly success and error messages

## 🚀 Tech Stack

- **Frontend**: React.js, Chakra UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Deployment**: Render

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or higher)
- npm or yarn
- MongoDB (local installation or MongoDB Atlas account)
- Git

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/product-store.git
   cd product-store
   ```

2. **Install dependencies**
   ```bash
   # Install backend dependencies
   npm install

   # Install frontend dependencies
   cd client
   npm install
   cd ..
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the root directory and add the following:
   ```env
   MONGO_URI=your_mongodb_connection_string
   PORT=5000
   ```

   Replace `your_mongodb_connection_string` with your actual MongoDB connection string.

## 🏃‍♂️ Running the Application

### Development Mode

To run both frontend and backend concurrently:
```bash
npm run dev
```

### Production Mode

1. **Build the application**
   ```bash
   npm run build
   ```

2. **Start the application**
   ```bash
   npm run start
   ```

The application will be available at `http://localhost:5000`

## 📁 Project Structure

```
product-store/
├── client/                # Frontend React application
│   ├── public/           # Public assets
│   └── src/              # Source files
│       ├── components/   # React components
│       ├── pages/        # Page components
│       ├── hooks/        # Custom hooks
│       └── App.js        # Main App component
├── backend/              # Backend Express application
│   ├── config/          # Database configuration
│   ├── controllers/     # Route controllers
│   ├── models/          # MongoDB models
│   └── routes/          # API routes
├── .env                 # Environment variables
├── .gitignore          # Git ignore file
├── package.json        # Dependencies and scripts
└── README.md          # Project documentation
```

## 🔗 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/products` | Get all products |
| GET | `/api/products/:id` | Get a single product |
| POST | `/api/products` | Create a new product |
| PUT | `/api/products/:id` | Update a product |
| DELETE | `/api/products/:id` | Delete a product |

## 🎨 Key Features Explained

### Product Management
- Add new products with name, price, and image
- Edit existing product details
- Delete products with confirmation
- View all products in a responsive grid layout

### UI/UX Features
- Clean and modern interface with Chakra UI
- Dark/light mode toggle
- Loading states for better user experience
- Toast notifications for actions
- Responsive design for all devices

### Error Handling
- Comprehensive error messages
- Form validation
- Network error handling
- User-friendly error displays

## 🚀 Deployment

This application is deployed on Render. To deploy your own version:

1. Fork this repository
2. Create a new Web Service on Render
3. Connect your GitHub repository
4. Add environment variables in Render dashboard
5. Deploy!

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Your Name - [Your GitHub Profile](https://github.com/v-a-dinesh)

## 🙏 Acknowledgments

- React.js Documentation
- Chakra UI for the beautiful component library
- MongoDB for the database
- Render for hosting

---

Made with ❤️ by [DINESH V A]
