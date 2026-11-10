# MLA Official Constituency Portal (Clone of https://mlapersonal.vercel.app/)

An exact 1:1 replica of the official digital portal for **Shri Bankim Ghosh, MLA**.

## 📁 Project Structure

```
├── index.html                           # Main Landing Page / Portal
├── about.html                           # Profile, Vision & Legislative Journey
├── development.html                     # Infrastructure & Development Projects
├── media.html                           # Press Releases, News & Gallery
├── reports.html                         # Constituency Audits & Performance Reports
├── connect.html                         # Citizen Grievance Redressal & Office Locations
├── noida-international-airport.html     # Dedicated Project Spotlight
├── privacy-policy.html                  # Privacy Policy
├── terms.html                           # Terms of Service
├── translator.js                        # Bilingual Toggle (English <-> Hindi)
└── images/                              # High-resolution assets
    ├── airport-infrastructure.jpg
    ├── industrial-zone.jpg
    ├── jan-chaupal.jpg
    ├── press-conference.jpg
    ├── project-inspection.jpg
    ├── bankim-ghosh-banner.jpg
    └── bankim-ghosh-portrait.jpg
```

---

## 🚀 How to Run Locally

### Option 1: Using Python
```bash
python -m http.server 3000
```
Then open [http://localhost:3000](http://localhost:3000) in your browser.

### Option 2: Using Node.js (`serve` or `live-server`)
```bash
npx serve .
```

### Option 3: Double click `index.html`
You can also open [index.html](file:///c:/Users/subha/OneDrive/Desktop/ml/index.html) directly in any modern web browser.

---

## 🌐 Deploy to Vercel

To host this website live on Vercel just like the original:

1. **Via Vercel CLI**:
   ```bash
   npx vercel
   ```
2. **Via GitHub**:
   - Create a repository on GitHub and push these files.
   - Go to [vercel.com](https://vercel.com) and click **"Add New Project"**.
   - Select your repository and click **"Deploy"** (no build settings required; it deploys instantly as a static website).

