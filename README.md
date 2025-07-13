# Team-Elite-Force-Odoo

problem statement 3 : ReWear – Community Clothing Exchange 

Team members:-
1.Shrey patel : shreypatel4307@gmail.com
2.Neeraj rathore : neerajrathore5821@gmail.com
3.om panchal : panchalom136@gmail.com 
4.shiv prajapati : shivkumarprajapati.23.cse@iite.indusuni.ac.in



# ReWear - Sustainable Fashion Exchange Platform

A complete web application for sustainable clothing exchange where users can swap unused clothes or redeem them through a point system.

## 🚀 Features

### User Features

- **User Authentication**: Login/Signup with localStorage-based session management
- **Guest Mode**: Browse items without creating an account
- **Product Browsing**: Browse clothing items by category with filtering
- **Item Details**: View detailed item information with image gallery
- **User Dashboard**: Manage listings, track purchases, and view impact
- **Point System**: Earn and redeem points for clothing items
- **Responsive Design**: Works on all devices

### Admin Features

- **Admin Panel**: Complete admin interface for managing users, orders, and listings
- **User Management**: View, edit, and delete user accounts
- **Order Management**: Track and manage all transactions
- **Listing Management**: Moderate and manage product listings

## 📁 File Structure

```
├── index.html              # Main login/signup page
├── mainlanding.html        # Landing page with product browsing
├── dashboard.html          # User dashboard
├── item-detail.html       # Individual item detail page
├── admin-login.html       # Admin login page
├── admin-panel.html       # Admin dashboard
└── README.md             # This file
```

## 🔧 How to Use

### For Users

1. **Start Here**: Open `index.html` in your browser
2. **Login/Signup**: Create an account or login with existing credentials
3. **Browse Items**: Navigate to the landing page to browse clothing items
4. **Filter by Category**: Use the category cards to filter products
5. **View Details**: Click on any item to view detailed information
6. **Access Dashboard**: Login to access your personal dashboard

### For Admins

1. **Admin Login**: Click the "Admin" link in the navigation or go to `admin-login.html`
2. **Credentials**: Use `admin` / `admin123` to login
3. **Manage Users**: View and manage user accounts
4. **Track Orders**: Monitor all transactions and orders
5. **Moderate Listings**: Manage product listings and approvals

## 🎨 Design Features

- **Eco-friendly Theme**: Green color scheme representing sustainability
- **Modern UI**: Clean, responsive design with smooth animations
- **Real Images**: High-quality clothing images from Unsplash
- **Interactive Elements**: Hover effects, smooth transitions, and loading animations
- **Mobile Responsive**: Optimized for all screen sizes

## 🔐 Authentication System

### User Authentication

- **LocalStorage-based**: Simple session management using browser storage
- **Guest Mode**: Browse without authentication
- **User Profiles**: Store user data, points, and activity

### Admin Authentication

- **Admin Credentials**: admin/admin123
- **Session Management**: Secure admin panel access
- **Role-based Access**: Separate admin and user interfaces

## 📊 Data Management

### Sample Data

The application includes sample data for:

- **Users**: 5 sample user accounts
- **Products**: 12+ clothing items with images
- **Orders**: Sample transaction data
- **Categories**: 10 clothing categories

### LocalStorage Structure

```javascript
// User Data
currentUser: {
  id: "USR001",
  name: "User Name",
  email: "user@email.com",
  points: 500,
  rating: 5.0,
  itemsUploaded: 0,
  itemsSwapped: 0,
  impact: 0
}

// Admin Data
adminLoggedIn: "true"
adminUser: {
  id: "ADMIN001",
  name: "Administrator",
  email: "admin@rewear.com"
}
```

## 🛠️ Technical Implementation

### Frontend Technologies

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with gradients and animations
- **JavaScript**: Interactive functionality and data management
- **Bootstrap**: Responsive grid system and components
- **Font Awesome**: Icons and visual elements

### Key Features

- **Responsive Design**: Mobile-first approach
- **Progressive Enhancement**: Works without JavaScript
- **Accessibility**: Proper ARIA labels and semantic HTML
- **Performance**: Optimized images and efficient code

## 🚀 Getting Started

1. **Download Files**: Save all HTML files to a folder
2. **Open in Browser**: Open `index.html` in any modern web browser
3. **No Server Required**: Works completely client-side
4. **Test Features**: Try login, signup, browsing, and admin functions

## 🔄 Workflow

### User Journey

1. **Landing** → Login/Signup or Continue as Guest
2. **Browse** → View items, filter by category
3. **Details** → Click items to see full information
4. **Dashboard** → Manage listings and track activity
5. **Logout** → End session and return to landing

### Admin Journey

1. **Admin Login** → Enter admin credentials
2. **Dashboard** → View users, orders, and listings
3. **Management** → Edit, delete, or approve items
4. **Logout** → Secure admin session termination

## 🎯 Future Enhancements

- **Backend Integration**: Connect to a real database
- **Payment System**: Implement actual payment processing
- **Real-time Chat**: Add messaging between users
- **Advanced Search**: Implement search and filtering
- **Mobile App**: Native mobile application
- **Analytics**: User behavior and platform analytics

## 📝 Notes

- All data is stored in browser localStorage
- Images are loaded from Unsplash CDN
- No external dependencies except CDN resources
- Works offline after initial load
- Cross-browser compatible

## 🤝 Contributing

This is a demonstration project. For production use, consider:

- Adding proper backend authentication
- Implementing secure data storage
- Adding input validation and sanitization
- Implementing proper error handling
- Adding comprehensive testing

---

**ReWear** - Making sustainable fashion accessible to everyone! 🌱👕
