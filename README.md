# Skilltern — Find Your Internship 🎓

A clean, fully client-side internship listing platform built with **pure HTML, CSS, and JavaScript** — zero dependencies, zero build steps. Just open the file and go.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔍 **Live Search** | Search internships by **title or company name** in real-time |
| 📍 **Filter by Location** | Dropdown to narrow results by city |
| 💼 **Filter by Role** | Filter by role category (Development, Design, Marketing, etc.) |
| 💰 **Sort by Stipend** | Sort listings High→Low or Low→High |
| ✕ **Clear Filters** | One-click reset for all filters |
| 🔖 **Save Internships** | Bookmark internships for later review |
| ✅ **Track Applications** | Mark internships as Applied and view them in a dedicated tab |
| ⚙️ **Admin Panel** | Add or delete internship listings via a built-in form |
| 💾 **Persistent Storage** | All data (listings, saved, applied) stored in `localStorage` |
| 📱 **Responsive Design** | Fully mobile-friendly layout |

---

## 📸 Pages

- **Browse** — Search, filter, and apply to open internships
- **Saved** — View bookmarked internships
- **Applied** — Track internships you've applied to
- **Admin** — Post new listings or remove existing ones

---

## 🚀 Getting Started

No installation or server required.

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/skilltern.git
   ```

2. **Open the file**
   ```
   Just double-click skilltern.html — it opens directly in any browser.
   ```

That's it! ✅

---

## 🗂️ Project Structure

```
skilltern/
├── skilltern.html   # The entire app — HTML + CSS + JS in one file
├── README.md        # This file
└── .gitignore       # Git ignore rules
```

Since this is a single-file app, everything lives inside `skilltern.html`:
- **CSS** — inside `<style>` tags (CSS variables, responsive layout, animations)
- **HTML** — semantic markup for 4 pages (Browse, Saved, Applied, Admin)
- **JavaScript** — all logic in `<script>` tag (filtering, localStorage, rendering)

---

## 🛠️ Built With

- **HTML5** — semantic structure
- **CSS3** — CSS variables, Grid, Flexbox, keyframe animations
- **Vanilla JavaScript** — no frameworks or libraries
- **localStorage API** — client-side data persistence
- **Google Fonts** — [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) + [Outfit](https://fonts.google.com/specimen/Outfit)

---

## 🎨 Design Highlights

- Burnt-orange (`#d4541a`) accent with dark navy (`#1a1a2e`) background
- Card entrance animations with staggered `fadeUp` delay
- Hover lift effect on internship cards
- Toast notification system for user feedback
- Company logo initials generated dynamically from company name

---

## 📦 Seed Data

The app ships with 8 pre-loaded internships from Indian companies (Zomato, Swiggy, Paytm, Nykaa, Razorpay, etc.) so it works out of the box. Any changes made via the Admin panel are persisted to `localStorage`.

---

## 🔮 Possible Future Enhancements

- [ ] User authentication (login/signup)
- [ ] Backend API + database (Node.js + MongoDB)
- [ ] Internship detail / full description page
- [ ] Email notification on application
- [ ] Pagination or infinite scroll
- [ ] Dark / Light mode toggle

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Made with ❤️ — Skilltern helps students find the right internship opportunity.

