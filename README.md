API Explorer Dashboard
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://github.com/public-apis/public-apis/workflows/GitHub%20Pages/badge.svg)](https://github.com/public-apis/public-apis/actions)
A beautiful, responsive dashboard for exploring thousands of public APIs. Features interactive charts, advanced filters, search, pagination, and detailed API modals. Built with HTML, Tailwind CSS, Chart.js, and vanilla JavaScript.
![Screenshot](screenshot.png)
*(Add a screenshot of the dashboard here)*
## ✨ Features
- **📊 Dashboard Stats**: Total APIs, categories, free APIs, HTTPS count
- **📈 Interactive Charts**: 
  - Top 10 categories (doughnut chart)
  - Authentication types (bar chart)
- **🔍 Advanced Search & Filters**:
  - Real-time search (name + description)
  - Category, Auth type, HTTPS, CORS filters
  - Clear filters button
- **🎴 API Directory**:
  - Responsive grid with hover effects
  - Pagination (12 per page)
  - Visual badges (Auth, HTTPS)
- **💫 UX Enhancements**:
  - Loading states & spinners
  - Error handling with mock data fallback
  - Copy-to-clipboard with toast
  - Keyboard shortcuts (ESC to close modal)
  - Last updated timestamp
  - Refresh all data button
- **📱 Fully Responsive**: Mobile-first design
- **🎨 Modern UI**: Dark theme, gradients, animations
## 🛠 Tech Stack
- **Frontend**: HTML5, Vanilla JavaScript (ES6+)
- **Styling**: Tailwind CSS (CDN), Custom CSS animations
- **Charts**: Chart.js
- **Icons**: Font Awesome
- **Data**: [Public APIs](https://github.com/public-apis/public-apis) + Mock fallback
- **Deployment**: GitHub Pages ready!
## 🚀 Quick Deployment to GitHub Pages
### Step 1: Fork or Create Repository
```
1. Go to GitHub.com and sign in
2. Create a new repository (e.g., "api-explorer-dashboard")
3. Upload `index.html` and `README.md`
```
### Step 2: Enable GitHub Pages
```
1. Go to repo Settings
2. Scroll to "Pages" in sidebar
3. Source: Deploy from "main" branch / root folder
4. Click "Save"
5. Wait 1-2 minutes
```
### Step 3: Access Your Live Site
```
Your site will be live at:
https://YOUR_USERNAME.github.io/api-explorer-dashboard/
```
![GitHub Pages Setup](https://docs.github.com/assets/cb-36840/images/help/pages/deploying-to-github-pages/deploying-to-github-pages-6.png)
## 📁 Local Development
1. Download `index.html`
2. Open directly in browser (`file://` or live server)
3. No build step required - fully static!
## 🔧 Customization
Edit `index.html` directly:
- Change `API_URL` for different data sources
- Modify Tailwind classes
- Update mock data in `generateMockData()`
- Add more filters/charts
## 📊 Data Source
Primary: [Public APIs GitHub](https://api.publicapis.org/entries)  
Fallback: Generated mock data (150+ APIs across 35 categories)
## 🤝 Contributing
1. Fork the repo
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add some amazing feature'`)
4. Push (`git push origin feature/amazing-feature`)
5. Open Pull Request
## 📄 License
This project is [MIT licensed](LICENSE).
---
**Built with ❤️ for developers exploring the API universe!** 🚀
*Data powered by [Public APIs](https://github.com/public-apis/public-apis)*
