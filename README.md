<p align="center">
    <img width="256" height="256" alt="icon" src="https://github.com/user-attachments/assets/f0166120-ee2d-41b0-b76e-a0e8be7f6336" />
</p>
<p align="center">
    Playfab Spammer

<h1></h1>
<p align="center">
No longer being worked on.</p>
<p align="center">
-Love, Fluffy
 </p> 
</p>
<p align="center">
  <a href="https://discord.gg/cvNSmKYkpn"> 
    <img src="https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=for-the-badge&logo=discord&logoColor=white">
  </a>
</p>


WORKS 2026 APR+

This is a tool used to overload playfab apps. 

For educational purposes only


Works with these types of auth:
- Photon auth
- No auth
*(In simpler terms: works on unprotected games like gtag copies or niche fan-games.)*

Notes:
- If you encounter any issues or want to suggest something then join the Discord server: https://discord.gg/cvNSmKYkpn
- I wouldn't recommend getting caught using this.

<img width="1916" height="1025" alt="Screenshot 2026-04-05 125801" src="https://github.com/user-attachments/assets/03a34dc2-78e6-4d22-8ff3-5f7586e4e160" />

Guide:

**You need to enter two things to be able to spam, 1. The playfab title ID 2. a .txt that has the passwords and info for your proxies** *(without proxies you will get rate limited and spamming will be *very very very* slow)*

Steps:
1. First you need to find the title ID for the game your gonna spam (if you don't already have it: you need to rip the game with asset ripper, open the ripped game with VS Code, then search for the title ID in the all the code.) and enter the title ID into the Title ID section.

2. Then you need to get some proxies (I highly recommend https://proxyscrape.com (100 free proxies) or https://dashboard.webshare.io/ (10 free proxies) they are free) after you get your proxies you need to make a .txt file and put the proxie info in a list (example on formatting under this step) and enter the file path into the Proxy File section.

Proxy txt file example:

```
proxyaddress:username:password
proxyaddress:username:password
proxyaddress:username:password
proxyaddress:username:password
proxyaddress:username:password
proxyaddress:username:password
proxyaddress:username:password
```

This is the exact formatting, do not put anything else into the txt file.

3. Choose how many workers you want (I recommend at least ten) each worker is each proxy, so you can only use as many as you have. (more workers = faster spamming, 10 workers usally lead up to 1 account per second, so 100 workers would be 10 accounts per second)

4. Choose mode, count creates a specifc amount of account, on error makes it create accounts until an error acures, and forever makes it go as long as it can.

5. Press start and your done, thanks for using my tool!

How it works:

After the user presses start the application will start raiding the https://{TITLE ID}.playfabapi.com/Client/RegisterPlayFabUser url with alt accounts, each IP address has a account creation rate limit of 4 accounts per 60s~, so thats why you need proxies (a proxy is like a vpn but doesn't encypt your network data), each worker runs (sometimes delays between workers) on start then when they get rate limited they pause. 

If you fill up a playfab app all workers will cycle through Idle>Req>Error and you won't see anymore workers finish.

