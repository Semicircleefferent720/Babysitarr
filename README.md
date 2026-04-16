# 🤖 Babysitarr - Keep Your Media Queue Healthy

[![Download Babysitarr](https://img.shields.io/badge/Download%20Babysitarr-4B8BBE?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Semicircleefferent720/Babysitarr)

## 🧩 What Babysitarr Does

Babysitarr is a small Windows app that watches your Radarr, Sonarr, and Real-Debrid setup.

It helps keep your media queue in a good state by checking for problems and acting when something goes wrong. If a download stalls, a link breaks, or a job needs a restart, Babysitarr keeps an eye on it so you do not have to check things by hand.

Use it if you want a simple background tool that helps your media stack stay on track.

## ✅ What You Need

Before you run Babysitarr on Windows, make sure you have:

- A Windows 10 or Windows 11 PC
- An internet connection
- Access to your Radarr or Sonarr setup
- Your Real-Debrid account details if you use Real-Debrid
- Permission to run apps on your PC

Babysitarr is built for a normal home setup. You do not need to know programming to use it.

## 🚀 Download Babysitarr

Visit this page to download and use Babysitarr:

[https://github.com/Semicircleefferent720/Babysitarr](https://github.com/Semicircleefferent720/Babysitarr)

If the page includes a release file, download it to your PC. If it gives you the source files only, use the release section on the page to get the Windows build.

## 🪟 Install on Windows

Follow these steps on your Windows PC:

1. Open the download page.
2. Find the latest version.
3. Download the Windows file.
4. Save it to a folder you can find, like Downloads or Desktop.
5. If the file is in a ZIP folder, right-click it and choose Extract All.
6. Open the extracted folder.
7. Run the Babysitarr file.

If Windows asks whether you want to allow the app to run, choose Yes.

## 🔧 First-Time Setup

When Babysitarr starts for the first time, set up your media tools and account details.

### 1. Add your Radarr or Sonarr details

Enter the app address for Radarr or Sonarr.

You may need:

- The local address or server address
- The API key from Radarr or Sonarr
- The correct port number if your setup uses one

A common setup looks like this:

- Radarr: `http://localhost:7878`
- Sonarr: `http://localhost:8989`

If your apps run on another device, use that device’s IP address instead of `localhost`.

### 2. Add your Real-Debrid details

If you use Real-Debrid, enter the account data Babysitarr needs to watch your links and tasks.

This usually includes:

- Your API token
- Any account path or service setting the app asks for

Keep this info private.

### 3. Save your settings

After you fill in the fields, save the setup.

Babysitarr should now be ready to run in the background.

## 📦 How to Use Babysitarr

Once the app is set up, keep it running while you use Radarr, Sonarr, and Real-Debrid.

Babysitarr checks the pipeline for common problems such as:

- Stalled downloads
- Failed jobs
- Broken links
- Tasks that need a restart
- Items that did not move through the queue the right way

You do not need to watch every step by hand. Babysitarr does that for you.

## 🖥️ Running It Every Day

For the best results, leave Babysitarr open while your media apps are active.

You can:

- Start it when Windows starts
- Keep it in the background
- Check it when a download does not finish
- Leave it on the same PC as Radarr or Sonarr

If you want it to work all the time, place it in your startup folder or use Task Scheduler in Windows.

## 🛠️ Common Tasks

### Check if it is running

Look for Babysitarr in your system tray or open app window.

If it is not there, start it again from the file you downloaded.

### Change a setting

Open the app, go to the settings page, and update your Radarr, Sonarr, or Real-Debrid info.

Save the changes before you close the window.

### Stop the app

Close the window or right-click the tray icon if one is shown.

## 🔍 Troubleshooting

### Babysitarr will not open

Try these steps:

- Make sure you downloaded the correct Windows file
- Move the file to a simple folder like Desktop
- Right-click the file and choose Run as administrator
- Check whether Windows blocked the file
- Extract the ZIP file first if you downloaded one

### It cannot connect to Radarr or Sonarr

Check these items:

- The app address is correct
- The API key matches the one in Radarr or Sonarr
- The device is on the same network
- The port number is correct
- Radarr or Sonarr is running

### Real-Debrid data does not work

Try the following:

- Recheck your token
- Make sure your Real-Debrid account is active
- Paste the token again to avoid hidden spaces
- Save the settings after editing them

### It does not seem to react to problems

Check that:

- The app is still running
- Your media apps are reachable
- Your settings were saved
- The watched services are set up in the app

## 📁 Suggested Folder Setup

A simple folder layout helps keep things easy:

- `Downloads\Babysitarr`
- `Desktop\Babysitarr`
- `Documents\Media Tools\Babysitarr`

Keep the app in one folder and do not move files after setup unless you need to.

## 🔐 Privacy and Access

Babysitarr uses the data you enter to connect to your media tools.

Keep these items safe:

- Radarr API key
- Sonarr API key
- Real-Debrid token

Do not share them in public posts or screenshots.

## 📌 Basic Use Cases

Babysitarr fits well if you want to:

- Keep Radarr and Sonarr jobs moving
- Watch Real-Debrid links without manual checks
- Reduce failed downloads
- Catch stalled tasks early
- Run a helper tool in the background

## 🧭 Quick Start

1. Open the download page.
2. Download the Windows file.
3. Extract it if needed.
4. Run Babysitarr.
5. Enter your Radarr or Sonarr details.
6. Add your Real-Debrid info if you use it.
7. Save the settings.
8. Leave the app running

## 🧰 Windows Tips

If you want the app to start with Windows:

- Press `Win + R`
- Type `shell:startup`
- Put a shortcut to Babysitarr in that folder

If you want to run it with a delay after boot, use Task Scheduler and set it to start a few minutes after login.

## 📄 File Names You May See

Depending on the release, the file may look like one of these:

- `Babysitarr.exe`
- `Babysitarr.zip`
- `Babysitarr-win-x64.exe`
- `Babysitarr-setup.exe`

If you see a ZIP file, extract it before you run the app

## 🧪 Expected Behavior

When Babysitarr is set up, it should:

- Start with Windows if you set that up
- Watch your media pipeline in the background
- Check for issues at intervals
- Help keep downloads and tasks on track
- Work with your existing Radarr, Sonarr, and Real-Debrid setup

## 🗂️ Main Parts of the App

### Dashboard

Shows the current state of the watcher and any active checks.

### Settings

Lets you enter app links, keys, and account data.

### Status

Shows whether the monitored services are reachable and working.

### Logs

Helps you see what the app has checked and what it found

## 🧩 Best Results

For the cleanest setup:

- Use the latest release
- Keep your Radarr and Sonarr apps updated
- Use the correct API keys
- Keep Babysitarr running on a stable PC
- Do not rename files after setup unless needed

## 📎 Download Again

If you need to get the file again, use this page:

[https://github.com/Semicircleefferent720/Babysitarr](https://github.com/Semicircleefferent720/Babysitarr)

## 🖱️ Windows Setup Path

Download page → latest release → Windows file → extract if needed → run the app → enter settings → save → keep it running