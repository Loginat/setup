# so, you're setting up tailscale to connect to the mc server

## **Process**
- Go to https://tailscale.com/
- Click on "Get Started!", it's in the top right corner under the black
- Make an account (just use the google sign in)
- Once you get to this menu, you're done making your account
- Go to https://tailscale.com/download/ and select your operating system. Unless your name is John Henri Cartelli, you're picking Windows.
- Download and run the file it gives you
- Once Tailscale has been installed on your PC, look in your system tray for the icon for Tailscale. Once you find it, click on it.
- The system tray is the stuff in the bottom right corner of your screen, where your clock and other stuff is
- Once you have verified Tailscale is running, click the link below to add the MC Server to your Tailnet
- https://login.tailscale.com/admin/invite/UPaeQqRA9bLEW5QdtbJF11
- After you add the machine to your Tailnet, verify that you are can connect to the MC Server by running the following command in your terminal
    - `ping 100.89.176.22`
- To access terminal on Windows, press 'ctrl+r' and enter 'cmd' into the resulting pop-up.
- To access terminal on Mac, press 'ctrl+alt+t'
If you see '64 bytes from 100.89.176.22', you're good.
    
## **FAQ**
- What if I don't see '64 bytes from 100.89.176.22'?
    - Talk to me
