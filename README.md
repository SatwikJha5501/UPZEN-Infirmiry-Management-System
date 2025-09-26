# UPZEN - Infirmary Management System for UPES

![UPZEN System](https://raw.githubusercontent.com/SatwikJha5501/UPZEN-Infirmiry-Management-System/refs/heads/main/Images/banner-2-img.png)

## 📋 Project Overview

UPZEN is a comprehensive web-based infirmary management system specifically designed for the University of Petroleum and Energy Studies (UPES). This platform streamlines healthcare services for students, staff, and faculty members by providing an efficient digital solution for appointment booking and medical service management.

## ✨ Key Features

### 🔐 User Authentication System
- **Secure Sign-In/Sign-Up** with SAP ID integration
- **Role-based access control** for different user types
- **Firebase Authentication** for secure user management
- **Password-protected accounts**

### 📅 Appointment Management
- **Easy Doctor Selection** from available medical staff
- **Flexible Scheduling** with intuitive date and time pickers
- **Phone Number Integration** for communication
- **Real-time Booking System** with instant confirmation

### 🏥 Healthcare Services Portal
- **Primary Health Care Services** for UPES community
- **24/7 Access** to infirmary information and resources
- **Health Awareness Posts** and medical updates
- **Emergency Contact Information** readily available

### 📱 Modern User Interface
- **Fully Responsive Design** for all devices
- **Cross-browser Compatibility**
- **Smooth Animations** and transitions
- **Professional Dark Theme** with blue accents

## 🛠 Technology Stack

### Frontend Technologies
- **HTML5** - Semantic structure and accessibility
- **CSS3** - Advanced styling with Flexbox/Grid layouts
- **JavaScript (ES6+)** - Client-side functionality
- **Font Awesome 6** - Modern icon library
- **Google Fonts (Poppins)** - Clean typography

### Backend & Database
- **Firebase Authentication** - Secure user management
- **Firebase Realtime Database** - Cloud data storage
- **Firebase Hosting** - Deployment platform

## 🚀 Installation & Setup

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code recommended)
- Firebase account

### Local Development Setup

1. **Clone the Repository**
```bash
git clone https://github.com/SatwikJha5501/UPZEN-Infirmiry-Management-System.git
cd UPZEN-Infirmiry-Management-System
```

2. **Set up Firebase Configuration**
   - Create a new Firebase project at [Firebase Console](https://console.firebase.google.com)
   - Enable Authentication and Realtime Database
   - Update the Firebase configuration in `signup.html`:

```javascript
const firebaseConfig = {
    apiKey: "your-api-key",
    authDomain: "your-project.firebaseapp.com",
    databaseURL: "https://your-project.firebaseio.com",
    projectId: "your-project-id",
    storageBucket: "your-project.appspot.com",
    messagingSenderId: "your-sender-id",
    appId: "your-app-id"
};
```

3. **Run the Application**
   - Open `index.html` in your web browser
   - Or use a local server for better functionality:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

## 📁 Project Structure

```
UPZEN-Infirmiry-Management-System/
│
├── index.html                 # Main landing page
├── login.html                 # User sign-in page
├── signup.html               # User registration page
├── booking.html              # Appointment booking page
│
├── CSS/
│   ├── LoginMain.css         # Login page styles
│   ├── SignInMain.css        # Signup page styles
│   ├── BookingMain.css       # Booking page styles
│   └── Main.css              # Main page styles
│
├── JavaScript/
│   ├── main.js               # Main JavaScript functionality
│   └── firebase-config.js    # Firebase configuration
│
├── Images/
│   ├── banner-2-img.png      # Main banner image
│   ├── search-icon.png       # Search icons
│   └── search-icon-dark.png  # Dark mode search icons
│
└── README.md                 # Project documentation
```

## 🎯 Core Functionality

### User Authentication
- **Secure Login**: SAP ID and password-based authentication
- **User Registration**: New user account creation with email verification
- **Session Management**: Persistent login sessions

### Appointment System
- **Doctor Selection**: Choose from available medical professionals
- **Date/Time Picking**: Flexible scheduling interface
- **Contact Integration**: Phone number collection for notifications
- **Instant Booking**: Real-time appointment confirmation

### Responsive Navigation
- **Mobile-Friendly**: Hamburger menu for small screens
- **Smooth Transitions**: CSS animations and effects
- **Search Functionality**: Dynamic search icon adaptation

## 💻 Usage Guide

### For Students/Staff
1. **Access the System**: Navigate to the main page
2. **Create Account**: Register with SAP ID and personal details
3. **Login**: Use credentials to access the dashboard
4. **Book Appointment**: Select doctor, date, and time
5. **Manage Bookings**: View and modify existing appointments

### For Administrators
1. **Access Admin Panel**: Special administrative login
2. **Manage Users**: Approve/disable user accounts
3. **Schedule Management**: Set doctor availability
4. **System Monitoring**: View usage statistics and reports

## 🔧 Customization

### Styling Modifications
The system uses CSS variables for easy customization:

```css
:root {
    --primary-color: #a1a1a0;
    --background-dark: rgb(32, 32, 32);
    --text-light: #ffffff;
}
```

### Adding New Features
1. **New Pages**: Create HTML files with corresponding CSS
2. **Functionality**: Add JavaScript modules in the JS folder
3. **Database**: Extend Firebase data structure as needed

## 🌐 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

## 📱 Mobile Responsiveness

The application is optimized for:
- **Desktop**: Full feature set with expanded navigation
- **Tablet**: Adapted layout with touch-friendly interfaces
- **Mobile**: Streamlined experience with mobile-first design

## 🔒 Security Features

- **Firebase Authentication**: Enterprise-grade security
- **Input Validation**: Client-side form validation
- **XSS Protection**: Sanitized user inputs
- **Secure Data Transmission**: HTTPS encryption

## 🚀 Deployment

### Firebase Hosting (Recommended)
```bash
# Install Firebase CLI
npm install -g firebase-tools

# Login to Firebase
firebase login

# Initialize project
firebase init

# Deploy to hosting
firebase deploy
```

### Alternative Hosting Options
- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **GitHub Pages**: Free static hosting

## 🐛 Troubleshooting

### Common Issues

1. **Firebase Connection Error**
   - Check internet connection
   - Verify Firebase configuration
   - Ensure Firebase services are enabled

2. **Authentication Problems**
   - Clear browser cache and cookies
   - Check if email is verified
   - Reset password if needed

3. **Styling Issues**
   - Hard refresh page (Ctrl+F5)
   - Check CSS file paths
   - Verify image file locations

### Debug Mode
Enable console logging for debugging:

```javascript
// Add to main.js for debugging
console.log('UPZEN System Initialized');
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Follow existing code style
- Test on multiple browsers
- Ensure mobile responsiveness
- Update documentation accordingly

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Development Team

- **Satwik Jha** - Project Lead & Full Stack Developer
- **Abhishek Rathour - Front End Developer

## 📞 Support & Contact

For support, email [satwikjha5501@gmail.com] or create an issue in the GitHub repository.

## 🔄 Version History

- **v1.0.0** (Current)
  - Initial release
  - Basic authentication system
  - Appointment booking functionality
  - Responsive design implementation

---

**UPZEN** - Transforming Healthcare Management at UPES through Digital Innovation 🚀
