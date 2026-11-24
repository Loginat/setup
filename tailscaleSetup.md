---
layout: default
title: tailscale
---

# so, you're setting up tailscale to connect to the mc server

## **Process**
- Go to [tailscale.com](https://tailscale.com/)
- Click on "Get Started!", it's in the top right corner under the black
- Make an account (just use the google sign in)
- Once you get to this menu, you're done making your account
- Go to [tailscale.com/download](https://tailscale.com/download/) and select your operating system. This guide assume you're using Windows lowk, if you're using Mac ask me whenever you have questions. If you use Linux, you should be able to do this w/o a guide.
    - If you're having issues with this step, please refer to [this link](https://tailscale.com/docs/install/windows) before asking me.
- Once Tailscale has been installed on your PC, look in your system tray for the icon for Tailscale. Once you find it, click on it.
    - The system tray is the stuff in the bottom right corner of your screen, where your clock and other stuff is
- Once you have verified Tailscale is running, click the link below to add the MC Server to your Tailnet
    - [MC Server Tailnet](https://login.tailscale.com/admin/invite/UPaeQqRA9bLEW5QdtbJF11)
- After you add the machine to your Tailnet, verify that you are can connect to the MC Server by running the following command in your terminal
    - `ping 100.89.176.22`
- To access terminal on Windows, press 'ctrl+r' and enter 'cmd' into the resulting pop-up.
- To access terminal on Mac, press 'ctrl+alt+t'
- If you see `64 bytes from 100.89.176.22`, you're good.
    
## **FAQ**
- What if I don't see `64 bytes from 100.89.176.22`?
    - Talk to me
- Any other questions
    - Talk to me
