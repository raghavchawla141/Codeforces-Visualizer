# 🔥 Codeforces Visualizer

---

## 🚀 Live Demo

Experience the visualizer live: [**Codeforces Visualizer**](https://cf-visualizer-rho.vercel.app/)

---

## ✨ Overview

Codeforces Visualizer is a sleek, intuitive web application designed to help competitive programmers and enthusiasts visualize their Codeforces journey and compare their performance with others. Built with modern web technologies, it provides comprehensive analytics and beautiful visualizations of your coding progress.

**Please Note:** This is an unofficial tool and is not affiliated with or endorsed by Codeforces. It utilizes the publicly available Codeforces API.

---

## 🎯 Key Highlights

* ⚡ **High Performance**: Optimized with `localStorage` caching and batch API requests
* 📱 **Fully Responsive**: Seamless experience across all devices
* 🎨 **Modern UI/UX**: Clean and intuitive interface built with Tailwind CSS
* 📊 **Rich Visualizations**: Interactive charts and graphs powered by Recharts
* 🔄 **Real-time Data**: Live data fetching from Codeforces API
* 🚀 **Fast Loading**: Built with Vite for lightning-fast development and production builds

---

## 🌟 Features

### 👤 Individual Profile Visualization

* **📈 Rating Analysis:**

  * Current and max rating with rank information
  * Interactive rating graph to track progress over time
  * Historical rating changes with contest-wise breakdown
* **📊 Activity Insights:**

  * Submission heatmap showing daily coding activity
  * Problems solved distribution by rating categories
  * Language usage statistics with pie charts
* **🏆 Performance Metrics:**

  * Verdict distribution (Accepted, Wrong Answer, TLE, etc.)
  * Tag-wise problem solving analysis
  * Contest participation history and performance

### 👥 Profile Comparison

* **⚔️ Head-to-Head Analysis:**

  * Side-by-side comparison of two Codeforces handles
  * Visual comparison bars for key statistics
  * Rating progression overlay graphs
* **📈 Detailed Comparisons:**

  * Problems solved by rating categories
  * Tag-wise problem distribution comparison
  * Contest duel table for common contests
  * Performance metrics analysis

---

## 💡 Performance Optimizations

* **📦 `localStorage` Caching** – Persistently caches API responses for 30 minutes to reduce redundant requests
* **🧠 Batch API Fetching** – Efficiently fetches data for multiple users in a single API call where supported
* **⚡ Fast Component Loads** – Modular, independently loaded components for minimal UI lag
* **🧪 Submission Cap** – Submissions limited to the last 2,000 entries per user for optimal performance and to stay within API limits

---

## 🛠️ Technologies Used

### Frontend Stack

* **[React](https://react.dev/)** – Modern UI library for building interactive interfaces
* **[Vite](https://vitejs.dev/)** – Next-generation frontend tooling for faster development
* **[Tailwind CSS](https://tailwindcss.com/)** – Utility-first CSS framework for rapid styling
* **[Recharts](https://recharts.org/)** – Powerful and customizable data visualization library

### Development & Deployment

* **[Vercel](https://vercel.com/)** – Seamless deployment and hosting
* **[Codeforces API](https://codeforces.com/api/help)** – Official API for fetching contest data
* **[pnpm](https://pnpm.io/)** – Fast, disk space efficient package manager

---

## 📦 Installation & Local Development

### Prerequisites

Ensure you have the following installed on your system:

* **[Node.js](https://nodejs.org/)** (v16.x or higher recommended)
* **[pnpm](https://pnpm.io/installation)** (Preferred package manager)

```bash
# Install pnpm globally if you haven't already
npm install -g pnpm
```

### 🚀 Quick Start

1. **Clone the repository:**

   ```bash
   git clone https://github.com/shashank2401/cf-visualizer.git
   cd cf-visualizer
   ```

2. **Install dependencies:**

   ```bash
   pnpm install
   ```

3. **Start the development server:**

   ```bash
   pnpm run dev
   ```

   🎉 Your app will be running at `http://localhost:5173/`

### 📝 Available Scripts

```bash
# Development
pnpm run dev          # Start development server
pnpm run build        # Build for production
pnpm run preview      # Preview production build locally
pnpm run lint         # Run ESLint for code quality
```

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**!

### 🔄 How to Contribute

1. **🍴 Fork the Project**
2. **🌿 Create your Feature Branch**

   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **💾 Commit your Changes**

   ```bash
   git commit -m 'feat: Add some AmazingFeature'
   ```
4. **🚀 Push to the Branch**

   ```bash
   git push origin feature/AmazingFeature
   ```
5. **📬 Open a Pull Request**

### 📋 Contribution Guidelines

* Follow the existing code style and conventions
* Write clear, descriptive commit messages
* Add comments for complex logic
* Test your changes thoroughly
* Update documentation if needed

### 🐛 Reporting Issues

Found a bug or have a feature request? Please [open an issue](https://github.com/shashank2401/cf-visualizer/issues) with:

* Clear description of the problem/feature
* Steps to reproduce (for bugs)
* Expected vs actual behavior
* Screenshots if applicable

---

## 🙏 Acknowledgments

* **[Codeforces](https://codeforces.com/)** for providing the comprehensive API
* **[Vercel](https://vercel.com/)** for seamless deployment and hosting
* The competitive programming community for inspiration and feedback

---

## 👨‍💻 Author

**Raghav Chawla**

---

<div align="center">

**⭐ Star this repository if it helped you visualize your Codeforces journey! ⭐**

Made with ❤️ for the competitive programming community

</div>
