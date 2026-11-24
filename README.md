A responsive blood donation web app. People can search for donors by blood group and pincode, register as a donor in four steps, and find blood banks and hospitals near their location.

Live demo: https://NOXWAL.github.io/Blood-Donation-App/

<div align="center">

# 🩸 Lifeline Blood Network

**Find blood fast. Become the donor someone is looking for.**

A responsive blood donation web app to search donors by blood group and pincode, register as a donor in four steps, and locate nearby blood banks and hospitals.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-b3122e?style=for-the-badge)](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)

</div>

---

## 📸 Preview

> Add a screenshot of your site here. Save it as `screenshot.png` in the repo and uncomment the line below.

<!-- ![Lifeline preview](screenshot.png) -->

---

## 📖 About

Every year, many patients wait for blood that a willing donor nearby could have given. Lifeline connects the two. A person in need can search for matching donors by blood group and location, and a healthy adult can register as a donor in about two minutes.

This is a front-end prototype built with plain HTML, CSS and JavaScript. It has no build step and no dependencies, so it opens straight in a browser and deploys to GitHub Pages as a single file.

## ✨ Features

| Area | What it does |
| --- | --- |
| **Emergency header** | Helpline strip with a highlighted number and a sticky navbar that collapses into a menu on phones. |
| **Hero section** | Two main actions, **Find Blood** and **Become a Donor**, plus a panel of example urgent requests. |
| **Live stat counter** | Registered donors, successful donations, lives impacted and donors available now, ticking every few seconds. |
| **Blood search** | Filter by blood group (A+, A-, B+, B-, AB+, AB-, O+, O-), pincode and availability. Results show donor name, blood group badge, distance, availability tag and a **Contact Donor** button. |
| **Nearby hospitals** | Enter an area, city or pincode to open live Google Maps results for blood banks, hospitals with a blood bank, and donation centres. |
| **Donor registration** | Four-step form: personal details, blood group and pincode, last donation date, review. Every step is validated. |
| **Eligibility checklist** | A modal that checks age 18 or above, weight 45 kg or above and no illness in the last 14 days before registration is confirmed. |
| **Design** | Crimson red and soft pink theme with dark grey text, automatic light and dark mode, full-screen animated GIF background and reduced-motion support. |

## 🛠️ Tech stack

- **HTML5, CSS3 and vanilla JavaScript** in a single `index.html`
- **Google Fonts:** Bricolage Grotesque and DM Sans
- **Google Maps search links** for the nearby hospitals feature
- No frameworks, no package manager, no build tools

## 🚀 Getting started

### Run locally

```bash
# 1. Clone the repository
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git

# 2. Go into the folder
cd YOUR-REPO-NAME

# 3. Open index.html in your browser (double-click it, or use a local server)
python3 -m http.server 8000
# then visit http://localhost:8000
```

### Deploy with GitHub Pages

1. Push `index.html` to the `main` branch.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/ (root)**, then click **Save**.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`.

## 📁 Project structure

```
.
├── index.html     # The whole app: markup, styles and scripts
├── README.md      # You are here
└── LICENSE        # MIT License
```

## 🔧 Customize

| What | Where to change it |
| --- | --- |
| Helpline number | Search for `1800-000-0000` in `index.html` and replace it with your real number. |
| Colors | Edit the CSS variables at the top of the `<style>` block (`--crimson`, `--pink`, `--ink`, and so on). |
| Sample donors | Edit the `DONORS` array in the `<script>` section. |
| Live counters | Edit the `data-count` values on the stat tiles. |
| Background GIF | Replace the base64 GIF inside the `.bgfx` rule, or point it at a file in your repo. |

## ⚠️ Important notes

- Donor names, phone numbers, distances, live counters and the helpline number are **sample data**. Replace them before using the site for real requests.
- Registration does **not** save anything yet. Connect it to a backend or database to store real donors.
- Donor contact details are personal data. Before going live, add consent, privacy and verification steps that follow the laws in your country.
- Always confirm blood availability directly with the hospital or blood bank.

## 🗺️ Roadmap

- [ ] Real donor database and API
- [ ] Mobile number verification (OTP) for donors
- [ ] "Use my current location" for nearby search
- [ ] Hindi and other regional languages
- [ ] Reminders when a donor becomes eligible again (3-month gap)
- [ ] Admin panel to manage donors and urgent requests

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push the branch: `git push origin feature/your-feature`
5. Open a pull request

## 📄 License

Released under the [MIT License](LICENSE).

## 👤 Author

GitHub: Uj1710glitch(https://github.com/Uj1710glitch)

---

<div align="center">

If this project helps you, give it a ⭐ and share it. One donation can save up to three lives.

</div>
