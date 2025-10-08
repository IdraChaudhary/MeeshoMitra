# Deployment Guide

## Quick Deployment

### Frontend (Vercel - Recommended)
1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Vercel will automatically detect React app
4. Click "Deploy" - your app will be live in 2 minutes

### Alternative: GitHub Pages
1. Go to your repo → Settings → Pages
2. Source: "Deploy from a branch"
3. Branch: `main` → `/ (root)`
4. Save - your site will be at: `username.github.io/MeeshoMitra`

## Environment Setup

### Required Environment Variables
Create `.env` file in root:
```env
VITE_APP_TITLE=Meesho Mitra
VITE_API_URL=your_backend_url
VITE_FIREBASE_CONFIG=your_firebase_config
Firebase Setup
Create project at Firebase Console

Enable Realtime Database

Copy config to your environment variables

Production Build
bash

Copy

Download
# Build the project
npm run build

# The build files will be in /dist folder
# Upload these to your hosting service
Custom Domain (Optional)
Buy domain from Namecheap/GoDaddy

In Vercel: Project Settings → Domains

Add your custom domain
