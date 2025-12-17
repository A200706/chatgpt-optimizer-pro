# Quick Installation Guide

## Prerequisites
- Windows 10 or 11
- Node.js 18+ ([download here](https://nodejs.org))
- ChatGPT Plus account

## Step 1: Clone Repository
```bash
git clone https://github.com/A200706/chatgpt-optimizer-pro.git
cd chatgpt-optimizer-pro
```

## Step 2: Install Dependencies
```bash
npm install
```

## Step 3: Run the App
```bash
npm start
```

## Step 4: Build Executable (Optional)
```bash
npm run build:exe
```
Your `.exe` will be in `dist/ChatGPT-Optimizer-Pro-1.0.0-setup.exe`

## Usage
- Press `Ctrl+Alt+G` to show/hide the window
- App runs in system tray
- All ChatGPT features work normally
- 60-80% faster than web browser

## Troubleshooting
- **"electron not found"**: Run `npm install` again
- **Build fails**: Run `npm cache clean --force` then `npm install`
- **Slow performance**: Update GPU drivers

## Uninstall
Run the uninstaller from Windows Settings → Apps
