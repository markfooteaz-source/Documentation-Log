# Workplace Documentation Tracker - PWA

## 🚀 Quick Deploy (Easiest Method)

### Option 1: Netlify Drop (Recommended)
1. Go to https://app.netlify.com/drop
2. Drag and drop ALL THREE files into the window:
   - `workplace-documentation-app.html`
   - `manifest.json`
   - `service-worker.js`
3. Netlify will give you a URL (e.g., `your-app.netlify.app`)
4. Bookmark this URL on your phone
5. Open it in Safari (iOS) or Chrome (Android)
6. You'll see an "Install" prompt - tap it to add to home screen

### Option 2: GitHub Pages
1. Create a new GitHub repository
2. Upload all three files
3. Go to Settings → Pages
4. Select "main" branch and save
5. Your app will be at `https://yourusername.github.io/repo-name/workplace-documentation-app.html`

### Option 3: Vercel
1. Go to https://vercel.com
2. Sign up/login
3. Click "New Project"
4. Upload all three files
5. Deploy!

## 📱 Installing on Your Phone

### iPhone (Safari)
1. Open the app URL in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add"
5. The app icon will appear on your home screen

### Android (Chrome)
1. Open the app URL in Chrome
2. Tap the menu (three dots)
3. Tap "Add to Home Screen" or "Install app"
4. Tap "Add" or "Install"
5. The app icon will appear on your home screen

## 🔑 First Time Setup

1. Get your Claude API key from https://console.anthropic.com/settings/keys
2. Open the app
3. Paste your API key in the field at the top
4. Click "Save API Key"
5. Start documenting!

## ✨ Features

- **Voice Recording**: Record notes while driving
- **AI Processing**: Automatically extracts details from your notes
- **Offline Storage**: All data stored locally on your device
- **Search & Filter**: Find entries by person, date, category, tags
- **Email Integration**: Auto-email for follow-up items
- **Export**: Download all data as CSV
- **Works Offline**: After first load, works without internet (except AI processing)

## 🔒 Privacy & Security

- All data stored locally on YOUR device only
- API key stored in browser's local storage (encrypted by browser)
- No data sent to any server except Anthropic's API for AI processing
- No analytics, no tracking, no third parties

## 📝 Usage Tips

1. **While Driving**: Open app → Tap "Start Recording" → Talk → Tap "Stop Recording"
2. **Processing**: Tap "Process with AI" → Fill in clarification → Review → Save
3. **Follow-ups**: Select "Follow-up" category → Email draft auto-opens
4. **Search**: Use filters in "View Entries" tab to find specific documentation

## 🆘 Troubleshooting

**"Failed to fetch" error:**
- Make sure you deployed to a web host (not opening from local file)
- Check your API key is valid at https://console.anthropic.com

**Voice recording not working:**
- Use Safari on iPhone or Chrome on Android
- Grant microphone permissions when prompted

**Install prompt not showing:**
- App must be served over HTTPS (all the hosting options above provide this)
- Try accessing from Chrome (Android) or Safari (iOS)

## 📞 Support

For issues or questions, update the app or contact your IT department.

## 🔄 Updates

To update the app:
1. Replace the files on your hosting service with new versions
2. Clear your browser cache or reinstall the app
3. Changes will take effect immediately
