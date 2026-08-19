# SK Asraful Haque - Portfolio Website

A modern, responsive personal portfolio website for **SK Asraful Haque** (BCA Student at Swami Vivekananda University), built with HTML5, modern CSS, and JavaScript.

---

## 🚀 How to Deploy to Vercel via GitHub

### Option 1: Using the Vercel Dashboard (Recommended)

1. **Push your code to GitHub**:
   - If exported to GitHub or pushed from Git:
     ```bash
     git add .
     git commit -m "Configure Vercel deployment"
     git push origin main
     ```
2. **Import to Vercel**:
   - Go to [vercel.com](https://vercel.com) and log in.
   - Click **"Add New..."** > **"Project"**.
   - Select your GitHub repository (`portfolio-site` or `asrafulwithcode/portfolio-site`).
   - Framework Preset: **Other** / **None** (automatically detected as Static Site).
   - Root Directory: `./` (leave default).
   - Click **Deploy**.

Your website will be live in seconds with automatic HTTPS and continuous deployment whenever you push commits to GitHub!

---

## 💻 Local Development

To run the project locally on your machine:

```bash
# 1. Install dependencies
npm install

# 2. Start the local server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure

- `index.html` - Complete portfolio page (Hero, About, Skills, Projects, Experience, Education, Contact).
- `vercel.json` - Vercel deployment configuration & security headers.
- `.gitignore` - Git ignore rules for clean repository commits.
- `package.json` - Node.js scripts and configurations.
- `server.js` - Lightweight Express server for local and preview environments.
