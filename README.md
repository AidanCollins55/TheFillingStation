# The Filling Station Website

Production-ready ASP.NET Core MVC website built for **The Filling Station**, a local bar/restaurant venue.  
Designed to be fast, mobile-friendly, and easy to maintain, with a clean public-facing experience.

🔗 **Live Site:** https://thefillingstationmt.com

---

## 🧩 Tech Stack

- **ASP.NET Core MVC (.NET 8)**
- **C#**
- **Razor Views**
- **SQLite** (lightweight persistence)
- **Bootstrap** (responsive UI)
- **GitHub Actions** (CI/CD)
- **Azure App Service** (hosting & SSL)

---

## ✨ Features

- Responsive public website
- Menu & informational pages
- Events / promotions support
- Image gallery
- SEO-friendly structure
- HTTPS with Azure-managed SSL
- Continuous deployment from GitHub

---

## 🚀 Deployment

This project is deployed using **GitHub → Azure App Service**:

- Pushes to `main` automatically trigger deployment
- Azure App Service handles hosting, HTTPS, and domain binding
- Production environment configured via Azure App Settings

---

## 🛠️ Local Development

1. Clone the repository
2. Open the solution in **Visual Studio 2022**
3. Restore NuGet packages
4. Run the project (`F5` or `dotnet run`)

> Note: Visual Studio artifacts (`.vs`, `bin`, `obj`) are intentionally ignored via `.gitignore`.

---

## 📁 Project Structure

