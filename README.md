# Cardinal Conclave 2026 - PWA Guide

A Progressive Web App for the Section E-8 Order of the Arrow Cardinal Conclave, April 17-19, 2026 at Camp Durant, BSA.

## Features

✅ **Offline Support** - Works without internet connection  
✅ **App-Like Experience** - Installs to your home screen  
✅ **Complete Schedule** - All events for Friday, Saturday, and Sunday  
✅ **Camp Map & Locations** - Navigate Camp Durant with ease  
✅ **Lodge Information** - All 6 participating lodges and campsites  
✅ **Meal Times** - Never miss a meal with organized schedules  
✅ **Main Programs** - Quest, Shows, Cardnival, ICE, REC, OAX, and more  
✅ **Mobile Optimized** - Perfect for phones and tablets  

## Quick Start - GitHub Pages Hosting

Follow these steps to host your Conclave app on GitHub Pages (FREE):

### Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com)
2. Click "Sign up" 
3. Follow the prompts to create your free account

### Step 2: Create a New Repository
1. Once logged in, click the **"+"** icon in the top right
2. Select **"New repository"**
3. Repository name: `cardinal-conclave-2026` (or any name you like)
4. Description: `Section E-8 Cardinal Conclave 2026 Event Guide`
5. Choose **Public** (required for free GitHub Pages)
6. ✅ Check **"Add a README file"**
7. Click **"Create repository"**

### Step 3: Upload Your Files
1. On your repository page, click **"Add file"** → **"Upload files"**
2. Drag and drop ALL files from this folder:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - The entire `icons/` folder (with all PNG files inside)
3. Scroll down and click **"Commit changes"**

### Step 4: Enable GitHub Pages
1. In your repository, click **"Settings"** (top menu)
2. In the left sidebar, click **"Pages"**
3. Under "Source", select **"Deploy from a branch"**
4. Under "Branch", select **"main"** and **"/ (root)"**
5. Click **"Save"**
6. Wait 2-3 minutes for GitHub to build your site

### Step 5: Find Your URL
1. Go back to **Settings → Pages**
2. You'll see: **"Your site is live at https://YOUR-USERNAME.github.io/cardinal-conclave-2026/"**
3. Click the link to view your app!

### Step 6: Install on Your iPhone
1. Open the URL on your iPhone in **Safari**
2. Tap the **Share button** (square with arrow up)
3. Scroll down and tap **"Add to Home Screen"**
4. Name it "Conclave 2026"
5. Tap **"Add"**
6. Done! You now have an app icon on your home screen

## File Structure

```
cardinal-conclave-pwa/
├── index.html              # Main app file
├── manifest.json           # PWA configuration
├── service-worker.js       # Offline functionality
├── icons/                  # App icons for all devices
│   ├── icon-72.png
│   ├── icon-96.png
│   ├── icon-120.png
│   ├── icon-128.png
│   ├── icon-144.png
│   ├── icon-152.png
│   ├── icon-167.png
│   ├── icon-180.png
│   ├── icon-192.png
│   └── icon-512.png
└── README.md               # This file
```

## Updating Your App

To make changes to your app:

1. Edit the files on your computer
2. Go to your GitHub repository
3. Click **"Add file"** → **"Upload files"**
4. Upload the modified files (GitHub will ask if you want to replace them)
5. Click **"Commit changes"**
6. Wait 2-3 minutes for changes to go live

**For users:** When they open the app, it will prompt them to reload and get the latest version!

## Features Included

### Home Tab
- Welcome message and event overview
- Quick access buttons to all sections
- Main programs overview (Quest, Shows, Cardnival, ICE, REC, OAX, etc.)

### Schedule Tab
- Complete schedule for all 3 days
- Search functionality to find specific events
- Day selector for easy navigation
- Rain plan information where applicable
- Lodge-specific meal times

### Map Tab
- Camp Durant overview
- Key locations marked
- Offline accessible

### Locations Tab
- All major camp locations
- Descriptions and area information
- Important notes about check-in and services

### Info Tab
- All 6 participating lodges with campsites
- Meal schedule by lodge group
- What to bring checklist
- Spirit Award information
- Contact details

## Technical Details

### PWA Features
- **Service Worker**: Caches all resources for offline access
- **Web Manifest**: Provides app metadata for installation
- **Responsive Design**: Works on phones, tablets, and desktops
- **Offline Indicator**: Shows when you're offline
- **Install Prompt**: Suggests installation on first visit

### Browser Compatibility
- ✅ iOS Safari (iPhone/iPad)
- ✅ Android Chrome
- ✅ Desktop browsers (Chrome, Firefox, Edge, Safari)

### Offline Capabilities
Once installed, the app works completely offline:
- Full schedule access
- Location information
- Lodge details
- Everything except external links

## Troubleshooting

### "My changes aren't showing up"
- Wait 2-3 minutes after committing changes
- Clear your browser cache
- On iPhone: Close Safari completely and reopen

### "The install prompt doesn't appear"
- On **iPhone**: You must manually add to home screen (iOS doesn't support install prompts)
- On **Android**: Make sure you're using Chrome and haven't dismissed it before

### "I can't see my icons"
- Make sure you uploaded the entire `icons/` folder
- Check that all PNG files are in `icons/` directory on GitHub

### "It says my page isn't found"
- Make sure GitHub Pages is enabled in Settings → Pages
- Verify your repository is Public
- Wait a few minutes after enabling Pages

## Custom Domain (Optional)

Want a custom URL like `conclave2026.com` instead of `username.github.io`?

1. Buy a domain from any registrar (Namecheap, Google Domains, etc.)
2. In GitHub: Settings → Pages → Custom domain
3. Enter your domain and follow the verification steps
4. GitHub provides detailed instructions for DNS setup

## Support

- **Event Info**: Visit [e8.oa-scouting.org](https://e8.oa-scouting.org)
- **GitHub Help**: [docs.github.com/pages](https://docs.github.com/pages)
- **PWA Documentation**: [web.dev/progressive-web-apps](https://web.dev/progressive-web-apps/)

## Credits

Created for Section E-8 OA Cardinal Conclave 2026  
Hosted by Occoneechee Lodge #104  
Camp Durant, Occoneechee Scout Reservation

**Wimachtendienk Wingolauchsik Witahemui**  
*Brotherhood of Cheerful Service*

---

## License

This app is created for the Order of the Arrow Section E-8 Cardinal Conclave 2026.  
Feel free to modify and customize for your event needs.
