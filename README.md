# 🏦 Fortune Control – Financial Portal Web App

A full-stack web development project that offers real-time financial news and user authentication.

## 🔧 Features

- ✅ Firebase Authentication (Email + Google) *(keys removed for security)*
- ✅ User profile stored in Firestore
- ✅ Real-time business news via NewsAPI
- ✅ Responsive UI built with Bootstrap
- ✅ Dynamic routing and user data handling
- ✅ News by category: Tech, India, Real Estate, MF

## 🛠️ Technologies Used

- HTML5, CSS3, JavaScript (ES6)
- Firebase (Auth + Firestore)
- Bootstrap 5
- NewsAPI

## 📁 Project Structure

```
fortune-control/
├── index.html
├── login.html
├── dashboard.html
├── assets/
│   ├── logo.png
│   ├── search.png
│   ├── man.png
│   └── index.css
├── styles.css
└── [firebase-config.js] (removed for security)
```

> 🔒 **Note:** Firebase config keys have been removed for security reasons. You’ll need to add your own Firebase credentials in `firebase-config.js` to run this locally.

## 🚀 Setup Instructions

1. Clone the repo:
   ```
   git clone https://github.com/your-username/fortune-control.git
   ```

2. Create your own Firebase project and insert your config in `firebase-config.js`.

3. Replace the NewsAPI key with your own in `index.html`.

4. Open `index.html` in a browser to use the app.
