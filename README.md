# Firewall-Alias-Lists
A series of Alias Lists I use for Network Optimization &amp; Security

PFsense & Opnsense allow for URL Tables, which contain a series of IPs, or destinations that can be imported from a list. These are a series of those lists I use. 

I am focusing on QOS/Wan Selection in a Multiwan environment, Firewalling, and App Identification This can help me build policy routing plans to segment traffic over different WANs to better balance connections depending on the quality of the WAN.

> Warning - Be very careful importing lists of IPs/URLs etc from sources you don't trust, understand, or sources you don't control. This repo is easily forked so you can choose to accept upstream content when you decide you want it. You've been warned!

PRs are welcomed, I am always trying to keep this up to date and relatively useful for what it's purpose is. 

These URLs txt lists below link to the raw content for each list, which can be added to various URl Table aliases of your choosing.

- Apps
  - [https://workspace.google.com/](https://raw.githubusercontent.com/alexwitherspoon/Firewall-Alias-Lists/main/apps/google-workspaces.txt)
  - [https://signal.org/](https://raw.githubusercontent.com/alexwitherspoon/Firewall-Alias-Lists/main/apps/signal.txt)
  - [https://slack.com/](https://raw.githubusercontent.com/alexwitherspoon/Firewall-Alias-Lists/main/apps/slack.txt)
  - [https://zoom.us/](https://raw.githubusercontent.com/alexwitherspoon/Firewall-Alias-Lists/main/apps/zoom.txt)

- Games
  - [All Servers - https://wargaming.net/](https://raw.githubusercontent.com/alexwitherspoon/Firewall-Alias-Lists/main/games/wargaming.txt)
  - [Game Servers - https://wargaming.net/](https://raw.githubusercontent.com/alexwitherspoon/Firewall-Alias-Lists/main/games/wargaming-game-servers.txt)
  - [Update Servers - https://wargaming.net/](https://raw.githubusercontent.com/alexwitherspoon/Firewall-Alias-Lists/main/games/wargaming-update-servers.txt)



- Services
  - [https://1.1.1.1/](https://raw.githubusercontent.com/alexwitherspoon/Firewall-Alias-Lists/main/services/dns-cloudflare.txt)
  - [https://apple.com](https://raw.githubusercontent.com/alexwitherspoon/Firewall-Alias-Lists/main/services/apple.com.txt)
  - [https://icloud.com](https://raw.githubusercontent.com/alexwitherspoon/Firewall-Alias-Lists/main/services/icloud.com.txt)
  - [https://developers.google.com/speed/public-dns](https://raw.githubusercontent.com/alexwitherspoon/Firewall-Alias-Lists/main/services/dns-google.txt)