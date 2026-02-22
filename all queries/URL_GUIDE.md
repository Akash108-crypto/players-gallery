# 🌐 Player Auction System - URL Guide

After deploying to Netlify, replace `YOUR-SITE-NAME` with your actual Netlify URL.

## 📋 Complete URL Structure

### 🏠 Home Page
```
https://YOUR-SITE-NAME.netlify.app/index.html
```
**Purpose**: Main landing page with all options

---

## 👨‍💼 ADMIN URLs (Password Protected)

### 🎯 Conduct Auction
```
https://YOUR-SITE-NAME.netlify.app/player_auction.html
```
**Who**: Admin only
**Features**:
- Start auction
- Select random players
- Mark as SOLD/UNSOLD
- Assign to teams (A-F)
- Enter selling price
- View team rosters
- Remove players from teams

**Password**: `Akash@2001`

---

### ➕ Register Players
```
https://YOUR-SITE-NAME.netlify.app/player_registration.html
```
**Who**: Anyone can register
**Features**:
- Add new players
- Upload photos
- Set player type (Batter/Bowler/All-Rounder)
- Base price: ₹50,000

---

### 👁️ Players Gallery
```
https://YOUR-SITE-NAME.netlify.app/players_gallery.html
```
**Who**: Anyone can view
**Features**:
- View all registered players
- Search players
- Delete players (password protected)
- Auto-refresh option

---

## 📺 VIEWER URL (Public - No Admin Access)

### 🔴 Live Auction Viewer
```
https://YOUR-SITE-NAME.netlify.app/auction_viewer.html
```
**Who**: Everyone (spectators)
**Features**:
- ✅ Watch auction in real-time
- ✅ See team rosters update live
- ✅ Click teams to view player lists
- ✅ Download team lists
- ✅ Auto-refreshes every 3 seconds
- ❌ Cannot conduct auction
- ❌ Cannot register players
- ❌ View only mode

**Perfect for**: Friends, family, participants watching from anywhere

---

## 📱 How to Share

### Share with Admin Team:
```
🎯 Auction Control: https://YOUR-SITE-NAME.netlify.app/player_auction.html
Password: Akash@2001
```

### Share with Public (Viewers):
```
📺 Watch Live Auction: https://YOUR-SITE-NAME.netlify.app/auction_viewer.html
No password needed - Just watch!
```

### Share with Players:
```
➕ Register Here: https://YOUR-SITE-NAME.netlify.app/player_registration.html
```

---

## 🎮 Auction Rules (Visible to All)

- **Base Price**: ₹50,000 per player
- **Team Purse**: ₹50,00,000 per team
- **Teams**: 6 teams (A, B, C, D, E, F)
- **Players per Team**: 11 players (full squad)
- **Bid Increments**: +₹25K, +₹50K, +₹100K
- **Unsold Players**: Get second chance at the end

---

## 🔐 Security

- **Admin Password**: Required for auction control and player removal
- **Firebase Auth**: All data synced in real-time
- **View-Only Mode**: Viewers cannot modify anything
- **Password**: `Akash@2001` (change in code if needed)

---

## 📊 Real-Time Features

All viewers see updates instantly:
- ✅ Player sold → Shows in team roster
- ✅ Team purse → Updates live
- ✅ Player count → Updates automatically
- ✅ Team complete (11/11) → Shows green badge

---

## 🎯 Example Sharing Message

**For Viewers:**
```
🏏 Join us for the LIVE Player Auction!

📺 Watch Here: https://YOUR-SITE-NAME.netlify.app/auction_viewer.html

✅ See teams being built in real-time
✅ Watch your favorite players get sold
✅ View complete team rosters
✅ No login needed - just click and watch!

Starts at: [TIME]
```

**For Players:**
```
🏏 Register for the Player Auction!

➕ Register Here: https://YOUR-SITE-NAME.netlify.app/player_registration.html

📸 Upload your photo
⚡ Choose your type (Batter/Bowler/All-Rounder)
💰 Base price: ₹50,000

Registration closes: [DATE]
```

---

## 💡 Tips

1. **Test First**: Open viewer URL on your phone to test
2. **Share Early**: Send viewer URL before auction starts
3. **Admin Only**: Keep auction URL private
4. **Bookmark**: Save URLs for easy access
5. **Mobile Friendly**: All pages work on phones/tablets

---

## 🆘 Support

If viewers have issues:
1. Check internet connection
2. Refresh the page
3. Clear browser cache
4. Try different browser
5. Contact admin

---

## 🎉 You're All Set!

Deploy to Netlify and share the viewer URL with everyone! 🚀
