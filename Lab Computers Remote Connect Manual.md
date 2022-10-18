## Remote Connect to University of Leeds Lab Computers

*Author: Yuelin Xin*

> #### About 
>
> The UoL Lab computers run on **Red Hat Linux 8**, they are equipped with all environments that you will need to complete your lab works and courseworks. 
>
> Every student has a home directory that is stored on a central server, so it might get slow if there are too many traffic (I was informed that the university IT department is working on this issue). You are only one user on a massive network, so be responsible for your own behaviour. You will **NOT** be given root access to your lab computer.
>
> To check the availability of the module environments, type in `module avail` in your lab computer terminal.

### Step 1

Download the **Pulse Secure** VPN client.

1. Windows

   Go to the Microsoft Store, search for application "Pulse Secure", then click "download".

   Alternatively, if you are too lazy to type, go to: [Pulse Secure - Microsoft Store](https://apps.microsoft.com/store/detail/9NBLGGH3B0BP?hl=en-us&gl=US).

2. Apple macOS

   Click on this link to download: [macOS](https://statics.cirrus.com/vpn/PulseSecure-9.1R14.0.dmg).

3. Linux

   Why bother? You already have a Linux machine, just configure it yourself you lazy dog.

### Step 2

Connect to the university VPN.

1. Windows

![img](https://it.leeds.ac.uk/sys_attachment.do?sys_id=4533d94e1b47811042c642ead34bcb39)

Configure your VPN to the above spec.

For lazy people, spec for copy:

> Name: UOLVPN
>
> Server URL: https://uolvpn.leeds.ac.uk/connect

Then click on "Connect", you will be prompted to login to your university account, the same old trick all over again... 



2. Apple macOS

<img width="752" alt="macos" src="https://user-images.githubusercontent.com/89094576/196455999-a0e04b0a-08cc-4021-b99c-1f492d10afa2.png">

The same trick with Windows, configure as above.

### Step 3

You are now connected to the university VPN, now open your browser and head to: https://feng-linux.leeds.ac.uk/

The website should auto-connect you to the university lab machines. If not, click on "Connect" on the splash screen.

### Step 4

Your tab page should look like this:

<img width="1682" alt="tabpage" src="https://user-images.githubusercontent.com/89094576/196456062-bf2845ea-0bd8-4223-8848-18bc2a613707.png">

Login to your account as usual and you are good to go!
