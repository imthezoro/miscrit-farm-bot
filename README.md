# Miscrit Bot

## 🎮 Overview

Miscrit Bot is an automation tool designed to help players with farming, training, and capturing Miscrits in the Miscrit game. The bot automates repetitive tasks like finding Miscrits, battling, and training, allowing you to progress in the game more efficiently.

## ✨ Features

- 🤖 Auto-farming: Automatically finds and battles Miscrits
- 🧠 Auto-training: Trains your Miscrits after battles (with configurable probability)
- 💎 Platinum training: Option to use platinum for training
- 🖱️ User-friendly GUI: Easy-to-use interface with status monitoring and logging

## 🧰 Requirements

- 🪟 Windows operating system
- 🌐 The game open in your browser window

## 📦 Installation

###VIDEO GUIDE : https://youtu.be/_uAy6j7__yk

### 🛠️ Executable Version

- 📥 [Download the latest release ZIP file](https://drive.google.com/file/d/1c8Pj3EMRmELGzr2vUX3NnGFEXyb8yjmu/view?usp=sharing)
- 🗂️ Extract all files to a folder of your choice
- 📁 Make sure you have the correct folder structure (see below)
- ▶️ Run `MiscritBot.exe`
- The bot UI will open
- Select your image folder and options, then click **Start**
- Switch to the game window quickly when prompted

## 📁 Folder Structure

The bot requires a specific folder structure for storing game element images:

```
root/
├── audio/
│   └── beep.wav
├── find_miscrits/
│   ├── water_stage_1/
│   │   └── [miscrit1.png, miscrit2.png, ...]
│   ├── water_stage_2/
│   │   └── [miscrit1.png, miscrit2.png, ...]
│   └── nature/
│       └── [miscrit1.png, miscrit2.png, ...]
├── attack/
│   └── [attack1.png, attack2.png, ...]
├── capture/
│   ├── capture_half.png
│   ├── okay_captured.png
│   └── keep.png
├── train/
│   ├── close.png
│   ├── ready_to_train.png
│   ├── train_now.png
│   ├── train.png
│   ├── continue_for_ability.png
│   ├── rank_up_okay.png
│   └── add_bonus_stat.png
├── continue.png
├── close_2.png
└── person.png
```

## 🧑‍💻 How to Use

### 🛠️ Step 1: Setup

- Launch the Miscrit Bot application
- Click **"Browse"** and select your images folder containing all the required screenshots
- Select your preferred element folder from the dropdown:
  - `water_stage_1`: ✅ Fully supported
  - `water_stage_2`: ⚠️ Should work most of the time
  - `nature`: ❌ Not working properly

### ⚙️ Step 2: Configure Options

- **Plat Train**: Enable if you want to train Miscrits with platinum
- **Capture Enabled**: Currently disabled
- **Prob Train**: Set the probability (0.0–1.0) of training after each battle

### ▶️ Step 3: Run

- Click the **"Start"** button to begin automation
- Switch to your game window within 1 second when prompted
- The bot will automatically find and battle Miscrits
- Monitor progress in the log window
- Click **"Stop"** when you want to end the automation

### 🧪 Creating Your Own Image Files

To customize the bot for your specific game setup:

- Take screenshots of the elements you want the bot to recognize
- Crop the images to focus on the specific element
- Save as PNG files in the appropriate folders
- Use descriptive names to help with troubleshooting

Examples:

- Miscrit images: Screenshots of Miscrits in the game world
- Attack buttons: Screenshots of attack buttons during battle
- Continue, close, and other UI elements

### 📄 Log Files

The bot generates a log file (`game_log.txt`) that can help diagnose issues. Check this file if you encounter problems.

## 📌 Important Notes

### ✅ Supported Element Areas

- **water_stage_1**: Works reliably and is recommended for most users.
- **water_stage_2**: Should work most of the time, but not guaranteed.
- **nature**: Not fully supported yet — expect bugs or failure.

### 🎯 Attack Images

To ensure the bot fights efficiently:

- Place screenshots of the attack buttons your Miscrit uses in the `attack/` folder.
- Use an auto-healing Miscrit if possible — it helps the bot run longer without needing rest.

## 🚀 Boost Farming with Cheat Engine (Highly Recommended)

Want to speed up your farming? Use **Cheat Engine** to make the game run up to 5× faster. Here's how:

1. Download Cheat Engine from [cheatengine.org](https://www.cheatengine.org/downloads.php)
2. Launch Cheat Engine.
3. Click **"Select a process to open"** (just under the File menu).
4. Choose your browser process that’s running Miscrits.
5. Enable **Speedhack**.
6. Set the **multiplier to 5.0** and click **OK**.

The bot is optimized to work with 5× speed, giving you faster battles and quicker results.

### 🖥️ Game Display Requirements

- Your screen resolution **must be 1920x1080**
- The game **must be in fullscreen mode**
- ❗ Using a different resolution? You’ll need to re-capture and replace all image assets in your folders. This is tedious and **not recommended** unless absolutely necessary.

### ⚠️ Alpha Version Warning

- The bot is in early **alpha** — it's powerful but may occasionally crash or get stuck.
- 👀 **Keep an eye on it!** Always monitor your farming sessions.
- 🔁 If anything breaks, restart the bot or game and try again.

### 🐛 Reporting Issues

If you encounter any problems, report them here: [Bug Report Form](https://docs.google.com/forms/d/e/1FAIpQLSc_Hn2OrxSkrdkpUN4NT9jUqCptzRni7QbWpxD6XxxH8vjr2Q/viewform?usp=dialog)
Will be addresses asap.

---

🔍 This bot is intended for educational purposes only.
