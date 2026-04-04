# 🤝 FundMitra — Crowdfunding Platform (Frontend)

> *"Your trusted friend in every fundraiser — connecting people, ideas, and support when it matters most."*

---

## 📋 Project Overview

**FundMitra** is a frontend prototype of a community-driven crowdfunding web platform designed to connect campaign creators with donors who want to make a meaningful difference. The platform enables users to discover campaigns, create their own fundraisers, track progress, and contribute to causes — all through a clean, responsive, and intuitive interface.

This project was developed as part of a **Web Technologies Lab** assignment and covers the complete frontend implementation, including UI design, client-side logic, simulated data management, and multi-page navigation.

---

## 👥 Team Members

| Name | Roll Number |
|------|------------|
| Adapa Tanuja Naga Sarojini | 24A31A0566 |
| Komanapalli Sri Johnvi | 24A31A0584 |
| Ventapalli Suhas | 24A31A05BE |
| Paidikondala Arun Sai Sandeep | 24A31A05AT |

---

## 🛠️ Tech Stack

| Technology | Usage |
|-----------|-------|
| **HTML5** | Page structure and semantic markup |
| **CSS3** | Styling, layout, responsiveness |
| **Vanilla JavaScript (ES6+)** | Client-side interactivity and logic |
| **Google Fonts & Material Icons** | Typography and iconography |
| **LocalStorage API** | Simulated user session and data persistence |

> **Note:** This is a frontend-only project as per lab requirements. There is no backend server, database, or REST API integration. All data is simulated using a static `data.js` file and browser LocalStorage.

---

## 📁 Project Structure

```
FundMitra/
│
├── index.html              # Landing / Home page
├── login.html              # Login & Sign-up page
├── campaigns.html          # Browse all campaigns
├── campaigndetails.html    # Individual campaign detail view
├── dashboard.html          # User dashboard — manage campaigns
├── profile.html            # User profile page
│
├── css/
│   ├── global.css          # Shared styles (navbar, typography, layout)
│   ├── index.css           # Home page styles
│   ├── login.css           # Login / Sign-up styles
│   ├── campaigns.css       # Campaign listing styles
│   ├── campaigndetails.css # Campaign detail page styles
│   ├── dashboard.css       # Dashboard styles
│   ├── newcampaign.css     # Create campaign modal styles
│   ├── donation.css        # Donation flow styles
│   └── profile.css         # Profile page styles
│
├── js/
│   ├── data.js             # Static mock dataset (campaigns, users)
│   ├── home.js             # Home page interactions (FAQ accordion)
│   ├── login.js            # Auth simulation (sign-up, login, validation)
│   ├── campaigns.js        # Campaign listing, filtering, search
│   ├── campaigndetails.js  # Campaign detail view, comments, updates
│   ├── dashboard.js        # User dashboard, campaign creation/editing
│   ├── donation.js         # Donation flow and payment simulation
│   ├── newcampaign.js      # Create/edit campaign modal logic
│   └── profile.js          # User profile management
│
└── images/
    ├── logo1.png           # Primary FundMitra logo
    ├── logo2.png           # Alternate logo variant
    ├── hero-image.png      # Hero section illustration
    └── default-campaign-image.png  # Fallback campaign thumbnail
```

---

## ✨ Features

### 🏠 Home Page
- Hero section with platform tagline and CTA buttons
- FAQ accordion section explaining how FundMitra works
- Responsive navbar with navigation links and user state

### 🔐 Authentication (Simulated)
- Login and Sign-up tabs on a single page
- Multi-step sign-up with form validation (email format, password strength, phone number)
- Password visibility toggle
- Session management via LocalStorage (no backend required)

### 📢 Campaign Listing
- Browse all available campaigns with card-style layout
- Filter campaigns by **category** (Health, Education, Social, Emergency, etc.)
- **Search** functionality by title and description
- Progress bar showing funding percentage for each campaign

### 📄 Campaign Detail Page
- Full campaign description and creator information
- Live funding progress with backer count and days remaining
- **Recent Backers** section
- **Comments / Q&A** section for community interaction
- **Updates** timeline posted by campaign creator
- Donate button leading to the donation flow

### 💰 Donation Flow
- Simulated donation with amount entry and payment method selection
- Donation confirmation and acknowledgement

### 📊 User Dashboard
- View campaigns created by the logged-in user
- **Create New Campaign** via a modal form with fields for title, category, descriptions, goal amount, and image URL
- Edit and delete existing campaigns
- Visual campaign progress summary

### 👤 Profile Page
- View and edit user profile information

---

## 🚀 How to Run

Since this is a purely frontend project, no server or installation is needed.

1. **Download / Clone** the repository or extract the project zip.
2. **Open** `index.html` in any modern web browser (Chrome, Firefox, Edge recommended).
3. Navigate across pages using the navbar.

> 💡 **Tip:** For the best experience, open the project using VS Code's **Live Server** extension to avoid any relative path issues.

---

## 🔮 Future Scope

The current version is a frontend-only prototype. Below are planned enhancements for a full-stack production release:

### Backend & Database Integration
- Build a RESTful API using **Node.js / Express** or **Django / Flask**
- Integrate a relational database (**PostgreSQL / MySQL**) or NoSQL (**MongoDB**) to persist users, campaigns, and transactions
- Replace all mock `data.js` and LocalStorage logic with real API calls

### Real Authentication & Security
- Implement **JWT-based authentication** or **OAuth 2.0** (Google / GitHub login)
- Add email verification on sign-up and password reset via OTP
- Role-based access control (Admin, Campaign Creator, Donor)

### Payment Gateway Integration
- Integrate a real payment gateway such as **Razorpay**, **Stripe**, or **PayU**
- Support UPI, net banking, credit/debit cards
- Automated receipt generation and refund handling

### Campaign Verification System
- Admin panel for reviewing and approving campaigns before they go live
- Document upload support for campaign creators (ID proof, project documents)
- Flagging and reporting mechanism for suspicious campaigns

### Notifications & Communication
- Email and SMS notifications for donation milestones, campaign updates, and expiry
- In-app notification bell with real-time alerts
- Campaign creator-to-backer messaging

### Analytics & Reporting
- Donor dashboard showing donation history and impact summary
- Campaign creator analytics: daily donations, traffic sources, conversion rates
- Platform-wide stats visible to admins

### Mobile Application
- Develop a cross-platform mobile app using **React Native** or **Flutter**
- Push notifications for campaign activity
- Mobile-first donation flow with UPI deep-linking

### AI/ML Enhancements
- **Recommendation engine** to suggest campaigns based on user interests and donation history
- Fraud detection model to flag suspicious campaigns or donation patterns
- Sentiment analysis on campaign comments for moderation

### Accessibility & Internationalization
- WCAG 2.1 compliance for screen reader support and keyboard navigation
- Multi-language support (Telugu, Hindi, English) for broader reach across India
- Dark mode toggle

---

## 📌 Disclaimer

This project is developed solely for **educational purposes** as part of a Web Technologies Lab. All campaign data, user accounts, donation figures, and transactions displayed are entirely **simulated and fictional**. No real money is collected or processed.

---

## 📄 License

This project is submitted as an academic assignment. Redistribution or commercial use is not permitted without prior consent from the team.

---

*Developed with dedication by Team FundMitra*
