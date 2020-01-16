Aw# Nintendo Switch VPN Guide for Matchmaking

So we finally have a nice guide on the internet that can help you connect your switch on a VPN network. The biggest advantage to VPN is the ability to change regional matchmaking in a game, and the perfect example of this is to join **Japanese lobbies** in Splatoon 2!

If you're curious of the source of this guide which is heavily recycled because I'm lazy, you can find it [here](https://docs.google.com/document/d/1QIemVhxG-YMkHfb1S3zjQzf1kRt0N1UJ1Jm1hjSQE8Q/edit). If you're curious what a VPN is, give this article a [read](https://www.howtogeek.com/133680/htg-explains-what-is-a-vpn).

**NOTE:** This guide assumes you're using Windows 10 with wifi. I don't know how to do it on Mac. Well without further ado, let's get started!


## Part I: Enable the Wireless Hosted Network
In a nutshell, the old hotspot method from settings doesn't work anymore, so we're going to use another type of hotspot built into Windows.

#### 1. First, right-click on the **Start button** then open Device Manager.
<p align="left">
  <img src="https://i.imgur.com/QwWznKU.png" alt="Start Button"/>
</p>

#### 2. Downgrade your wireless card to the lowest version.
<p align="left">
  <img src="https://i.imgur.com/DosTRIa.png" width="58%" height="58%" alt="wireless card"/>
</p>

#### 3. Open Command Prompt and check if the hosted network is enabled.

Enter the following command `netsh wlan show drivers` and if the hosted network support says **Yes**, we can continue! If not, you might be out of luck.

<p align="left">
  <img src="https://i.imgur.com/1A15gQt.png" width="75%" height="75%" alt="cmd"/>
</p>

## Part II: Install the VPN Gate
#### 1. Download [VPN Client by clicking here](https://goo.gl/Rejwd6)
<p align="left">
  <img src="https://i.imgur.com/XseCKqY.png" width="70%" height="70%" alt="vpngate"/>
</p>

#### 2. Extract and install VPN Client + Gate Plugin.

<p align="left">
  <img src="https://i.imgur.com/46yQyEG.png" alt="install-1">
  <img src="https://i.imgur.com/Q5R7wcI.png" alt="install-2"/>
</p>

#### 3. In the installation, select SoftEther VPN Client.

<p align="left">
  <img src="https://i.imgur.com/VmPB7JC.png" width="60%" height="60%" alt="install-3"/>
</p>

#### 4.	After installation, launch the "VPN client Manager" program, click Add "VPN Connection" and then create a virtual Client Adapter. Select Add VPN Connection again to add a new VPN.

<p align="left">
  <img src="https://i.imgur.com/AN1pTA2.png" alt="vpn-manager-1"/>
</p>

<p align="left">
  <img src="https://i.imgur.com/4ccr82p.png" width="69%" height="69%" alt="vpn-manager-2"/>
</p>  

#### 5. Go to: [VPNGate's website](http://www.vpngate.net/en/) and choose any one of the VPN connections by entering its *hostname address* and the *TCP port* to the VPN Client. Username and password are always "vpn". I set the setting name to "Japan VPN" this is optional.

<p align="left">
  <img src="https://i.imgur.com/QaHylUT.png" width="75%" height="75%" alt="vpn-server-1"/>
</p>

<p align="left">
  <img src="https://i.imgur.com/bke1sxk.png" width="75%" height="75%" alt="vpn-server-2"/>
</p>  

#### 6. Click OK. Right click your Added VPN and click Connect. 

<p align="left">
  <img src="https://i.imgur.com/JD2L7Lk.png?1" alt="vpn-connect"/>
</p>  

**NOTE:** If it doesn’t connect, try connecting again or try another VPN server with its correct hostname and TCP port at: http://www.vpngate.net/en/ 

## Part III: Share the VPN to Local Area Connection
#### 1. Go to **Change adapter options** in Network Settings.

<p align="left">
  <img src="https://i.imgur.com/cwP0Iom.png" width="69%" height="69%" alt="network-1"/>
</p>  

#### 2. Right-click on the VPN Client device and click properties.

<p align="left">
  <img src="https://i.imgur.com/gyuPGbE.png" width="80%" height="80%" alt="network-2"/>
</p>

#### 2. Go to the Sharing tab, check the first box, select "Local Area Connection" from the dropdown and then click OK.

<p align="left">
  <img src="https://i.imgur.com/CLkYQ0c.png" alt="network-3"/>
</p> 

Hey, I know the process is very long but we're almost there!

## Part IV: Install the Hosted Network Manager

#### 1.	Download and extract the Hosted Network Manager zip file [here](https://www.brainbytez.nl/wlan-hosted-network-manager/) then run as administrator.

<p align="left">
  <img src="https://i.imgur.com/ZMZutGy.png" alt="gui-1"/>
  <img src="https://i.imgur.com/w5bXeSm.png" alt="gui-2"/>
</p>  

#### 2. In the app, set a network name and pass, then turn it on.

<p align="left">
  <img src="https://i.imgur.com/2rWUMi8.png" alt="gui-connect"/>
</p>  


Great, we're done from the computer side of things!

Connect your Nintendo Switch to your computer’s hotspot (hosted network) and see if you can play JP lobbies and not disconnect! 

**NOTE:** Remember when you are not playing splatoon, turn off the “Japan VPN” in this case by right clicking it and select "Disconnect". If you want to leave it on, it’s up to you Mr./Mrs. Reader.

**TIP:** Not every VPN is great, but the best ones are those with the **least amount of sessions**, **fastest line quality**, and the most important of all, **least amount of ping**. Any other relatively close Asian countries will still let you play in JP lobbies, except for Russia. It will likely pair you up with EU instead, ~~and not because of the possible danger and miscellaneous territory.~~

## Q.A

### How do I know if my location changed successfully from the VPN program?
    You can check your IP location at http://www.vpngate.net/en/ and if it looks like you’re
    in a country that you expected, it means you’re gucci.

### What can I expect while playing in JP lobbies?
    Expect some lag and potential disconnects since free vpns aren’t the most reliable way to connect
    to other countries. You may want to experiment with other servers to find a good one for yourself.
    JP rank battles are also pretty hard, be careful what you’re putting yourself into.

### Wait placing your dock closest to your computer helps with the hotspot connection?
    Yes fam.

### Will there be more questions in the future?
    Yes Q.A is expected to be updated when needed.

### Where can I contact you?
    DM me on Discord if you have any questions @Yuya#0276
    or DM me on twitter: https://twitter.com/yahtzee_14.

## Credits
* Mecha and Xeno for being the first testers and for the Q&A ideas
* The one dude who helped me realized the previous VPN guide was outdated

