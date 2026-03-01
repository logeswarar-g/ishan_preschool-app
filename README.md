# Ishan Preschool and Academy - APK Builder

## 🚀 How to Get Your Free APK Using GitHub (Step-by-Step)

---

### STEP 1: Create GitHub Account
1. Go to **https://github.com** 
2. Click "Sign Up" and create a free account

---

### STEP 2: Create New Repository
1. Click the **"+"** button (top right) → "New repository"
2. Name it: `ishan-academy`
3. Set it to **Public**
4. Click **"Create repository"**

---

### STEP 3: Upload ALL These Files
Upload the files keeping the EXACT same folder structure:

```
.github/
  workflows/
    build-apk.yml        ← IMPORTANT!
android/
  app/
    build.gradle
    src/
      main/
        AndroidManifest.xml
        assets/www/
          index.html
          manifest.json
          sw.js
        java/com/ishanpreschool/app/
          MainActivity.java
        res/values/
          styles.xml
  build.gradle
  gradle/wrapper/
    gradle-wrapper.properties
  settings.gradle
```

**How to upload:**
- In your GitHub repo, click "Add file" → "Upload files"
- Drag and drop all files (maintaining folder structure)
- Click "Commit changes"

---

### STEP 4: Wait for APK to Build (Automatic!)
1. Click the **"Actions"** tab in your GitHub repo
2. You will see "Build APK" running automatically
3. Wait ~5-10 minutes for it to finish
4. When done, click on the completed run
5. Scroll down to **"Artifacts"**
6. Download **"Ishan-Academy-APK"**
7. Unzip it → you have your **APK file!** 🎉

---

### STEP 5: Install on Android Phone
1. Send the APK to your phone (WhatsApp, email, Google Drive)
2. On your phone: Settings → Security → Enable "Unknown Sources" or "Install unknown apps"
3. Open the APK file and install!

---

## ⚠️ Important Notes
- **Data is stored locally** on each device (localStorage)
- The APK is a **debug APK** — perfect for personal/school use
- For Play Store publishing, you need a $25 Google account (one-time)
- The app works 100% offline once installed!

---

## 🔄 To Update Your App Later
1. Edit `android/app/src/main/assets/www/index.html`
2. Push changes to GitHub
3. GitHub automatically builds a new APK
4. Download and reinstall!
