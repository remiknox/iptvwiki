Posted by u/jcumb3r in r/IPTVGroupBuy on Wed Jan 01 2025 14:15:46 GMT+0

This is admittedly a bit of a niche post, but for the fellow geeks among us, I thought you may find this useful to get much faster VPN speeds for your IPTV devices if your router supports setting up a VPN Client.

u/mrrobvs and I were going back & forth yesterday about VPN speeds from the Shield Pros (which are poor). After that I realized my Unifi router is capable of setting up a client VPN from the router itself to a VPN provider and then selectively routing only specific clients (i.e. my Nvidia Shields) through that VPN. I know that many Asus routers support this as well, though VPN performance will vary depending on the horsepower of your router. Overall, getting this working was surprisingly simple.

# Setup

1. Download Wireguard config file from your VPN provider (look under a section like 'VPN for routers' or something like this from your provider). Wireguard is generally the fastest / lowest CPU-intensive protocol, so always use wireguard if it is available from your provider when speed is the primary concern.
2. In Unifi, you navigate to Networks -> Settings -> VPN -> VPN Client and create new connection. Upload the configuration file you downloaded in step one. (your router should have a similar config section)
3. After you create the VPN, Unifi helpfully asks you to 'add a policy-based route' to choose which devices are routed through the VPN.
4. Choose your IPTV devices from the list and then choose to send all of those through the new VPN you just created. (in other routers, you will need to have assigned static IP addresses to your IPTV players. Add those IP addresses to the config at this step. In Unifi, you just pick the devices by name)
5. I had to reboot my shields to pick up the new network info... but other than that, I was shocked that it 'just worked' with about 10 minutes of effort total.

# Results

|VPN Configuration|Download Speed|Upload Speed|
|---|---|---|
|Shield Speed: no VPN used|500 mbps|380 mbps|
|Wireguard VPN client running on Shield|160 mbps|100 mbps|
|Wireguard VPN client running on Unifi router|**340 mbps**|**200 mbps**|

Summary: if you have a router that can serve as your VPN client, try it out.   