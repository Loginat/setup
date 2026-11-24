---
layout: default
title: tailscale
---

# Getting Started with Tailscale: A Simple Guide

## What is Tailscale?

Tailscale is a free-to-start app that lets your devices (laptop, phone, tablet, home computer, servers) talk to each other safely over the internet, as if they were all on the same home network. No complicated settings are needed.

Your group of connected devices is called a **tailnet**. Think of it as a private club for your devices: only the ones you invite can get in.

---

## Before You Begin

You will need:

- A computer or phone connected to the internet
- An account with one of these services: **Google, Microsoft, Apple, or GitHub**. Tailscale uses one of these to sign you in, so you don't need to create a new password.
- About 5 minutes

---

## Part 1: Install Tailscale on Your Device

### On Windows

1. Go to **https://tailscale.com/download** in your web browser.
2. Click **Download Tailscale for Windows**.
3. Open the downloaded file and follow the on-screen prompts. Click **Yes** or **Next** when asked.
4. When it finishes, look for the Tailscale icon in the bottom-right corner of your screen (near the clock). Click it and choose **Log in**.
5. A web page will open. Choose your sign-in method (Google, Microsoft, Apple, or GitHub) and sign in.
6. Click **Connect** when asked to approve the device.

### On Mac

1. Open the **App Store** on your Mac and search for **Tailscale**, or go to **https://tailscale.com/download**.
2. Click **Get**, then **Install**.
3. Open the app. You'll see a small Tailscale icon at the top of your screen (the menu bar).
4. Click the icon and choose **Log in**.
5. Sign in with your Google, Microsoft, Apple, or GitHub account.
6. If your Mac asks for permission to add a VPN configuration, click **Allow**. This is normal and required for Tailscale to work.

---

## Part 2: Check That It's Working

1. Open the Tailscale app or click its icon.
2. You should see a **Connected** status or a toggle switch turned **on**.
3. You should also see your device's name in the list. This means it has joined your tailnet.

Once you install Tailscale on a second device and sign in with the **same account**, the two devices can see each other automatically.

---

## Part 3: Add a Server to Your Tailnet

A **server** is a computer that stays on and shares things with your other devices, such as files, a website, or an app. Adding it to your tailnet lets you reach it from anywhere, privately and securely, without exposing it to the public internet.

> **Tip:** The steps below are a general overview. For the exact instructions for your server, use the link below.
>
> **[the link](https://login.tailscale.com/admin/invite/UPaeQqRA9bLEW5QdtbJF11)**

### Step by step

1. **Get to your server.** Sit at the server or connect to it the way you normally do.
2. **Install Tailscale on the server.** Go to **https://tailscale.com/download** from the server and choose the option that matches its operating system (for example, Linux, Windows, or macOS).
3. **Start Tailscale.** Open the app, or if your server only has a text window (a "terminal"), follow the instructions on the download page for your system.
4. **Sign in.** Tailscale will show you a web link. Open it in any browser, sign in with **the same account you used in Part 1**, and approve the server.
5. **Confirm it joined.** Open the Tailscale app on your laptop or phone. You should now see your server in the list of devices.

### Reaching your server

After the server joins your tailnet, you can connect to it using the name shown in the Tailscale app (for example, `my-server`). Use that name wherever you would normally type the server's address.

---

## Troubleshooting

| Problem | What to try |
|---|---|
| I can't sign in | Make sure you're using the same sign-in method every time (for example, always Google). |
| My device says "Disconnected" | Open the Tailscale app and switch it on. |
| I can't see my other device | Check that both devices are signed in with the **same account** and both are turned on and online. |
| The server doesn't appear in my list | Make sure you approved the server on the sign-in web page, then refresh the device list. |

---

## Need More Help?

- Tailscale's official help center: **https://tailscale.com/kb**
- Contact me.
