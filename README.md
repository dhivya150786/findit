

#  FindIt — Lost & Found Web App

FindIt is a modern, user-friendly **Lost & Found web application** that helps users report, search, and recover lost items easily. It allows people to post lost or found items, connect with others, and increase the chances of recovering belongings.



##  Features

###  Authentication System

* User Signup & Login
* Password reset functionality
* Session management using localStorage

###  Lost & Found Posting

* Report **Lost Items**
* Report **Found Items**
* Add:

  * Item name
  * Category
  * Description
  * Location (manual + map)
  * Date & time
  * Contact details
  * Image upload

###  Location Support

* Interactive map using Leaflet.js
* Drop pin to mark exact location
* GPS-based location detection
* Google Maps integration

###  Search & Filters

* Search by:

  * Item name
  * Category
  * Location
* Filter posts dynamically
* “My Posts” toggle view

###  Dashboard & Stats

* Total items
* Lost items count
* Found items count
* Resolved items
* Categories tracked

###  Notifications

* Alerts when matching items are found
* Notification center UI

###  User Profile

* View user info
* Track personal posts
* Profile stats

###  UI/UX

* Modern dark theme
* Responsive design (mobile + desktop)
* Smooth animations & transitions

---

##  Technologies Used

* **HTML5**
* **CSS3 (Custom Styling)**
* **JavaScript (Vanilla JS)**
* **Leaflet.js (Maps)**
* **LocalStorage (Data Persistence)**

---

## Project Structure

```
FindIt/
│
├── index.html      # Main application file
├── README.md       # Project documentation
```

---

##  How to Run

1. Download or clone the repository
2. Open `index.html` in any browser
3. Start using the app 

> No server setup required (runs fully on frontend)

---

##  How It Works

* All data (users & posts) is stored in **browser localStorage**
* Users can:

  * Create account → Login
  * Post lost/found items
  * Search and connect with others
* Matching system suggests possible item matches



##  Limitations

* No backend (data stored locally in browser)
* No real authentication (basic frontend logic)
* Data is not shared across devices
* Social login buttons are UI-only (non-functional)

---

## 🔮 Future Improvements

* Backend integration (Node.js / Firebase)
* Real-time database
* Image storage (Cloudinary / Firebase Storage)
* Push notifications
* Chat system between users
* AI-based item matching

---

##  Author

**Dhivya U**


##  License

This project is open-source and available for learning purposes.

