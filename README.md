Firebase Google Login & Dashboard Website
This project is a basic web application demonstrating Firebase Authentication with Google Sign-In integration. It features a public-facing website with Home, About Us, and Contact Us pages, along with a protected Dashboard section accessible only after user login.

Features
Google Sign-In authentication powered by Firebase Authentication.

Public main pages available before login:

Home Page

About Us

Contact Us

Protected pages accessible only after login:

Dashboard (Main page after login)

Events

Jobs

Other internal pages as needed

Redirects users to the Dashboard immediately after successful login.

Logout option (if implemented) to clear session and return to public pages.

Prerequisites
Node.js installed (optional, for local server)

A Firebase project with Authentication enabled:

Google Sign-In provider activated.

Firebase config object from your Firebase project settings.
Usage
Visit the Home page.

Click on the "Login with Google" button.

After successful authentication, you will be redirected to the Dashboard.

Navigate through protected pages like Events and Jobs.
Folder Structure
/ (root)
|- index.html            # Home page with Firebase authentication
|- dashboard.html        # Dashboard page accessible after login
|- events.html           # Events page (protected)
|- jobs.html             # Jobs page (protected)
|- about.html            # About Us page (public)
|- contact.html          # Contact Us page (public)
|- assets/               # Images, CSS, JS files

Dependencies
Firebase JavaScript SDK

Modern web browsers
Responsive, clean UI design with basic animations.

Easy integration and setup with Firebase.
