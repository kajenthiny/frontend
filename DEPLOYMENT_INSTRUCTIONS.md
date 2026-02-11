# Deployment Instructions for Zenza Education

## Quick Deploy (No CLI Needed)

### Method 1: Drag & Drop (Fastest)
1. Visit https://vercel.com
2. Sign up/Login with GitHub, GitLab, or Bitbucket
3. Drag and drop your `dist` folder onto the deployment area
4. Wait 10-20 seconds
5. Get your live URL!

### Method 2: Connect GitHub Repository (Best for Updates)
1. Push your code to a GitHub repository
2. Go to https://vercel.com
3. Click "Add New Project"
4. Import your GitHub repository
5. Vercel auto-detects Vite settings
6. Click "Deploy"
7. Every future git push automatically updates your site!

### Method 3: CLI Deployment (Current Method)
You've already set this up! Just need to:
1. In your terminal, press ENTER when prompted
2. Login through the browser
3. Answer the questions (press ENTER to accept defaults)
4. Your site deploys automatically

## Build Your Project
Before deploying, always build:
```powershell
npm run build
```

This creates the optimized `dist` folder.

## Configuration Files Created
- ✅ `vercel.json` - Ensures React Router works on all routes

## Your Project Details
- **Framework**: React + Vite
- **Build Command**: `vite build`
- **Output Directory**: `dist`
- **Routes**: /, /AboutUs, /australia, /canada, /uk, /france, /contact

## After Deployment
Your site will be live at:
- Production: `https://your-project-name.vercel.app`
- You can add a custom domain later in Vercel settings

## Need Help?
- Vercel Docs: https://vercel.com/docs
- Vite Docs: https://vitejs.dev
