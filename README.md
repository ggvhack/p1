# 🤝 CareConnect

> A community-driven welfare platform connecting volunteers, donors, and people in need — built with pure HTML, CSS & JavaScript.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-brightgreen?style=for-the-badge)](https://ggvhack.github.io/p1/)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://github.com/ggvhack/p1)
[![HTML](https://img.shields.io/badge/Built%20with-HTML%2FCSS%2FJS-orange?style=for-the-badge&logo=html5)](https://github.com/ggvhack/p1)

---

## 📖 About

**CareConnect** is a lightweight, front-end web application designed to foster community support and welfare. It allows users to register as volunteers or donors, share helping stories, make donations, track community contributions on a leaderboard, and access emergency guides — all without a backend server.

User sessions are managed through URL query parameters, making the app fully static and deployable on GitHub Pages.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔐 **Login / Register** | Simple onboarding with role selection (Volunteer / Donor) and city |
| 📰 **Feed** | Share and view community helping stories with content moderation |
| 💰 **Donation** | Track and submit donations to welfare causes |
| 🏆 **Leaderboard** | See top contributors in the community |
| 👤 **Profile** | View personal stats, role, and contribution history |
| 🚨 **Emergency Guide** | Quick-access emergency information and resources |

---

## 🚀 Live Demo

👉 [https://ggvhack.github.io/p1/](https://ggvhack.github.io/p1/)

**Try it with a sample user:**
```
https://ggvhack.github.io/p1/dashboard.html?name=Soumik+Debnath&email=soumik@example.com&role=volunteer&city=Bilaspur
```

---

## 🗂️ Project Structure

```
p1/
├── index.html          # Landing page
├── login.html          # Login & registration page
├── dashboard.html      # Main feed / home after login
├── donation.html       # Donation page
├── leaderboard.html    # Community leaderboard
├── profile.html        # User profile page
├── emergency.html      # Emergency guide & resources
└── README.md
```

---

## 🛠️ How It Works

CareConnect uses **URL query parameters** to pass user session data between pages. When a user logs in, their details (name, email, role, city) are appended to the URL and carried across navigation.

**Example URL:**
```
dashboard.html?name=John+Doe&email=john@example.com&role=volunteer&city=Kolkata
```

The app reads these parameters using JavaScript's `URLSearchParams` API to personalize the experience.

### Content Moderation
The feed only allows posts containing approved community-positive keywords such as:
`helping`, `aid`, `support`, `relief`, `care`, `donation`, `volunteer`, `welfare`, `community`, etc.

---

## 💻 Getting Started

### Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/ggvhack/p1.git
   cd p1
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   open index.html
   ```
   > No build tools or server required — it's pure HTML/CSS/JS!

### Deploy to GitHub Pages

1. Push your code to the `main` branch
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your site will be live at `https://<username>.github.io/<repo>/`

---

## 🎯 User Roles

| Role | Description |
|---|---|
| **Volunteer** | Community helper who shares stories and provides aid |
| **Donor** | Contributor who provides financial or material support |

---

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Commit: `git commit -m "Add your feature"`
5. Push: `git push origin feature/your-feature-name`
6. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**CareConnect team**  
Built with ❤️ for community welfare.

[![GitHub](https://img.shields.io/badge/GitHub-ggvhack-black?style=flat&logo=github)](https://github.com/ggvhack)
