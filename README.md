# Welcome to Tav's ABadAvatar V1.3
# DOWNLOAD V1 WITH THIS LINK:
https://mega.nz/file/1BsxlKxT#Z8slE4UAur7UtY8aD9RJZKrnTLJ6aNm1ROIBlvv4wHg

Welcome to my custom version of **ABadAvatar V1.3!**

This is the standard ABadAvatar setup with some extra tools, features, and quality-of-life improvements to make your experience easier without adding unnecessary bloatware.

The goal of this project is to give new Xbox 360 modders a strong starting point and make getting into Xbox 360 homebrew as simple as possible.

**PLEASE READ THE SETUP AND USAGE INSTRUCTIONS BELOW BEFORE GETTING STARTED.**

---

## What's Included?

Here are the extra features included in this version that are not part of the standard ABadAvatar V1.3 setup:

- **Homebrew Store** — An easy way to browse and download supported homebrew applications and tools.
- **Aurora Repo Browser** — Browse available repositories and discover additional content for Aurora.
- **ReLIVE** — A stealth-server plugin designed to provide additional Xbox Live connectivity features. A stealth server cannot guarantee protection from console or account bans.
- **AutoDNS** — Included to help manage DNS settings for the intended setup. Correct configuration is required before use.
- **Preloaded Skins and Themes** — A collection of Aurora themes and skins, ready to use.
- **Disc to GOD** — A tool for converting supported physical game discs into Games on Demand (GOD) format for use with compatible Xbox 360 homebrew dashboards.

The aim is to give you useful tools right from the start, without requiring you to hunt down everything separately.

---

## Important Information Before You Start

**Please read these points carefully.**

- **Keep the USB connected:** This setup relies on the USB containing the required ABadAvatar files and plugins. Do not remove it while the console is powered on and using the setup.
- **Designed for portability:** The USB is intended to make it easier to move your setup between compatible consoles. However, compatibility and additional configuration may vary between consoles.
- **Use a separate drive for your games:** This setup is designed to use a second USB drive for your legally obtained game backups and other game content. Keep those files separate from the main ABadAvatar USB.
- **Check compatibility before updating:** Do not update your console just because a newer dashboard is available. Dashboard versions can affect exploit compatibility. Confirm that your console's dashboard and avatar update requirements match the version supported by your ABadAvatar setup first.
- **Keep a backup:** Make a copy of the USB's files on your PC before making changes. This gives you a way to restore the setup if something goes wrong.
- **No ban protection is guaranteed:** Using ReLIVE, AutoDNS, or other network tools does not guarantee that your console or account will never be banned. Use online services at your own risk.

---

# Setup Instructions

This section covers the initial USB setup and the additional configuration options.

## 1. Main USB Setup (Required)

Follow these steps to prepare your ABadAvatar USB.

1. **Check your dashboard version.** Before updating your console, confirm that your current dashboard is compatible with this ABadAvatar release. Do not install a system update until you have verified compatibility.

2. **Check your avatar update.** If your console displays grey, ghost-like avatars on the profile selection screen, your avatar data may be missing or incomplete. You may need the appropriate avatar update for your dashboard version.

3. **Connect your USB to your PC.** Back up anything important on the drive first, as formatting will erase its contents.

4. **Format the USB as FAT32** using a suitable PC formatting tool.

5. **Safely eject the USB** from your PC.

6. **Connect the USB to your Xbox 360** and navigate to Settings → System → Storage.

7. Select your USB storage device, press **Y**, and choose the format option if prompted. This will erase the drive, so make sure you have backed up anything important.

8. Once formatting is complete, turn off the console and disconnect the USB.

9. Connect the USB to your PC again.

10. Download this repository from GitHub and extract the downloaded archive.

11. Open the extracted `TavsBadAvatar` folder.

12. Copy **everything inside the `TavsBadAvatar` folder** directly onto the root of the USB. Do not copy the entire `TavsBadAvatar` folder itself.

13. Safely eject the USB from your PC.

14. Connect the USB to your Xbox 360 and power on the console.

15. Allow the ABadAvatar exploit to run. You should see the chain-breaking animation. Wait for the animation to finish before interacting with the console.

If everything works correctly, your Xbox 360 should now be running the ABadAvatar setup.

**If the animation does not appear or the console freezes, do not assume the exploit worked.** Check your dashboard compatibility, USB formatting, and file placement before trying again.

---

## 2. AutoDNS Setup (Optional — Verify Before Use)

AutoDNS is included as part of this setup, but it may require additional network configuration to work as intended.

The purpose of the intended configuration is to manage how the console handles network connections during startup.

**Important:** Do not enter random DNS addresses or assume that an address supplied in an old guide is still valid. The address `192.0.2.1` is reserved for documentation and is not a normal public DNS server. Before using AutoDNS, obtain the correct DNS address and setup instructions from the documentation for the exact version included with this USB.

Once you have verified the correct configuration:

1. Power on your Xbox 360.
2. Open Settings → System → Network Settings.
3. Select your active network connection.
4. Choose Configure Network → DNS Settings → Manual.
5. Enter the verified primary and secondary DNS addresses supplied by the AutoDNS project.
6. Save your settings.

Your DNS settings should now be configured. However, this alone does not confirm that AutoDNS is working correctly.

**Do not rely on AutoDNS as a guarantee against bans or as proof that your console is safe to connect to Xbox Live.** Verify that the included version is compatible with your console and follow its own documentation before enabling online connectivity.

---

## 3. Starting the Setup

Once you have completed the required USB setup and any optional configuration you need:

1. Safely eject the USB from your PC.
2. Connect it to your Xbox 360.
3. Power on the console and allow the exploit to complete.
4. Wait for the console to finish loading.

**Do not sign into the Bad Avatar profile.** If the console asks you to select a profile and you do not have another profile available, press **B** to continue without signing in, unless the specific instructions for your setup tell you otherwise.

Keep the USB connected while using the setup.

---

## 4. Using Your Second USB Drive for Games

This setup is designed to keep the ABadAvatar files separate from your game library.

Use a second USB drive for your legally obtained game backups and other compatible game content.

This makes the main USB easier to maintain and lets you manage your games separately without disturbing the ABadAvatar files.

The exact folder structure and scan paths depend on the game format and the dashboard you are using. For Aurora, make sure your game folders are placed in the correct location and that the relevant path has been added to Aurora's content settings.

---

## 5. Aurora Themes and Skins

This USB includes a selection of Aurora themes and skins so you can customise the appearance of your dashboard.

To use them:

1. Launch Aurora.
2. Open the relevant theme or skin settings.
3. Browse the available themes.
4. Select the one you want to use and apply it.

The names and available options may vary depending on the skin pack and Aurora version installed.

---

## 6. Homebrew Store and Aurora Repo Browser

The Homebrew Store and Aurora Repo Browser are included to make it easier to discover additional tools and supported content.

Availability depends on the repositories, services, and software versions being used. Some sources may be offline or no longer maintained.

Only download software from sources you trust, and make sure it is compatible with your console and dashboard.

---

## 7. ReLIVE

ReLIVE is included as an additional network-related plugin.

Its functionality depends on the version installed, its configuration, and the services it relies on.

**Please remember:** No stealth server can guarantee that your console or account will not be banned. Connecting a modified console to online services carries risks, even when additional network tools are installed.

---

# Troubleshooting

### The chain-breaking animation does not appear
- Check that the USB is formatted correctly.
- Make sure the contents of `TavsBadAvatar` are in the root of the USB, not inside an extra folder.
- Confirm that your console's dashboard version is compatible with this release.
- Safely eject the USB from your PC before reconnecting it.

### My avatars appear as grey ghosts
Your console may be missing the appropriate avatar data. Check which avatar update is required for your dashboard version before installing anything.

### Aurora cannot find my games
Check the folder structure of your game files and make sure Aurora has been configured to scan the correct directory on your second USB drive.

### A repository or homebrew download does not work
The repository or service may be offline, outdated, or incompatible with your setup. Check the source and try again later if necessary.

### AutoDNS does not appear to work
Verify the DNS addresses and instructions for the exact AutoDNS version included. Check your network configuration and do not assume that changing DNS settings alone makes online connections safe.

---

# Final Notes

This project is intended to make getting started with Xbox 360 homebrew easier by bringing several useful tools together in one place.

If you are new to console modding, take your time, read the instructions, and keep a backup of your files before making changes.

**Have fun exploring your Xbox 360, and welcome to the homebrew community!**

— Tav
