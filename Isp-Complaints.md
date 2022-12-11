---

---



[◄◄ **Back to FAQ**](https://www.reddit.com/r/piracy/wiki/faq)

---

---

*The following is not meant to be an in-depth explanation of the logistics involved in relationships between internet service providers and copyright parties, but rather a simple overview of answers to common inquiries regarding piracy and the importance of privacy.*

---

# Copyright infringement complaints

### ► *Will I receive a letter/complaint from my ISP for downloading `x` or browsing a pirate site?*

Browsing a pirate website will not get you in any sort of trouble by your ISP.

In regards to downloading, it depends on the country in which you live, but this guide is mainly intended for USA/Canada-based users since that is reddit's primary userbase. In some countries, like Germany, you are likely to be hit with a sizeable fine if you are caught pirating, so stay away from torrents completely if you live there.

If you are downloading via torrents (ie. Torrenting, through the use of a bittorrent client or other torrent-based application like Popcorn Time, or Showbox -- To disable torrent functionality from Showbox, look through its settings), then yes, you will be caught. Being part of a torrent swarm at all means you are at risk of getting a copyright notice.

Otherwise, downloading through other means, such as direct downloads/DDL **(ie. downloading from cloud storage like google drive or mega.nz, or file hosts such as zippyshare, or other centralized downloads, irc, usenet, etc.)**, would not get you caught. DDL is a blanket term used for any sort of direct connection between you and a single other server. Basically, if the download is done via HTTP, FTP (either through your browser or a download manager), you will not be caught.

Downloading a `.torrent` file from a website does not classify as torrenting, as that occurs through an HTTP download. Browsing a torrent site also will not trigger complaints from your ISP. Continue reading below for an explanation.

&nbsp;

### ► *How does my ISP know what I am downloading and why is it only torrents that are the culprit for copyright infringement letters?*

ISPs are not the ones who monitor your downloading habits for the purpose of punishing you -- An ISP would not have any stake in trying to bust their users for acts of piracy on their own accord. If an ISP cared about your piracy habits, they would simply block access to pirate websites instead of constantly monitoring their users for acts of piracy. The blame lies with copyright trolls, parties that monitor the distribution of copyrighted material and use “mass copyright litigation to extract settlements from individuals”. The only type of piracy that these groups can monitor are torrents since the technology is inherently open -- a torrent tracker will broadcast the IPs of the peers who are present in that swarm to the other peers, as a means of reporting which pieces of the file(s) each peer has for the purpose of distribution (ie. user A has piece `x` and user B is missing piece `x`, therefore user A will now upload to user B). As a result, copyright trolls can easily join a swarm and log all of the IPs present in that swarm. These groups will then complain to the ISPs who own the IPs they logged, and in turn, the ISPs are expected forward the complaint to the account holder but in most cases, the ISP is not obligated to share the personal details of the account holder to the copyright protection group and will only forward their complaints and threaten to shut off your internet, while other times they merely serve as an educational warning. In some countries, like Germany, you are liable to be fined a hefty sum of money for copyright infringement.

When you download from a web server, on which the only peers involved are you and the server (as opposed to torrenting, where there are many peers), then only you and the server operator will know what is being downloaded if the server is SSL encrypted  (when visiting a webpage, SSL encryption is denoted by https in the URL, as opposed to just http). If your connection to the server is not SSL encrypted, then your ISP can easily know what is being downloaded. They won't do this, however, as they have no reason to -- ISPs are not responsible for monitoring the downloading of pirated material.

&nbsp;

### ► *Am I less likely to receive a copyright complaint from my ISP if I don't upload?*

The "uploading is illegal, downloading is not" reasoning most people give for why only torrents get you caught is a myth. Downloading copyrighted content is still illegal, though uploading (sharing) of copyrighted content is a more serious act. However, this doesn't mean that uploading is the sole culprit in receiving complaints from your ISP -- joining a torrent swarm at all will mean that your IP is liable to be logged and reported by copyright trolls. Even if uploading was the sole culprit for receiving copyright complaints, setting a ratio limit of 0 in your torrent client would do nothing to prevent copyright complaints, since torrents will naturally attempt to upload to other peers at any point during the download process and no proper torrent client (excludes Chinese clients like Xunlei Thunder) allows users to limit their upload speed to 0. If DDLs could be as easily monitored as torrent swarms, you would be getting copyright infringement complaints concerning their use as well.

&nbsp;

### ► *How can I avoid getting copyright infringement complaints?*

You have several options:

 1. **If you're going to download via torrents, use a VPN.** A VPN creates a secure network connection over a public network such as the internet and encrypts your traffic. Your ISP will continue to know that you are consuming bandwidth, but to their eyes, your traffic will be encrypted. Your real IP will be hidden, so any server/network you connect to will only see your VPN's assigned IP address. **A paid VPN is recommended, as there are no good free ones** -- such free VPNs will likely collect data from you, be too slow to bother with, or do not allow torrent traffic in the first place. Many VPNs can be as cheap as 3 USD/month, if you buy in bulk.

 VPNs are not infallible, however, as your connection to them may sometimes fail. That is why some VPN providers offer a 'killswitch' function, which will disable all network activity on your computer if your connection to the VPN drops. If your VPN provider does not offer such functionality, you may consider switching to a torrent client that offers an in-built killswitch, like qBittorrent [(Here is a guide on how to accomplish this)](https://www.ghacks.net/2016/03/23/qbittorrent-block-transfers-vpn-disconnect/).

 Note 1: Also keep in mind that some websites will throw a fit if you are connected to a VPN. Connecting to netflix will fail if you are behind a VPN; your banking institutions, including paypal, will raise a flag on your account and likely lock it due to suspicious login activity.

 Note 2: qBitorrent has a setting called anonymous mode. It can cause many connectivity issues, essentially killing your ability to connect to peers: [\[Reddit thread\] qBittorrent has a "Anonymous Mode" ... Is this at a beneficial if I'm already using a VPN?](https://web.archive.org/web/20140128050529/http://www.reddit.com/r/torrents/comments/1vqt9b/qbittorrent_has_a_anonymous_mode_which_as_i)

 Note 3: Many torrent clients offer a `force encryption` option. This does not hide your IP from the torrent swarm. It only attempts to mask your torrenting activity from your ISP, such that they do not become aware that you are transferring data through torrents. This setting aims to prevent ISPs from throttling your torrent transfers. Your IP will still be entered into the swarm, and any anti-piracy suit who chooses to enter the swarm can do so easily and log your IP. It is not a substitute for a VPN.

 2. **Rent a seedbox.** A seedbox is a remote server that is set up with torrenting in mind -- the server will handle all torrenting so your own IP will never have a chance of entering any torrent swarm. Once the server completes the torrent, you can download the content to your own computer through FTP or HTTP(S), both different types of direct downloads. It is extremely unlikely for your ISP to monitor your FTP transfers. Regardless, your seedbox provider should offer SSH access (your data transfers will be encrypted) if you are worried about your ISP snooping in on your data transfers.

 3. **Using a private tracker** in conjunction with either of the above solutions is also advised. Copyright trolls go after low hanging fruit such as public trackers (thepiratebay, extratorrent, rarbg), which have millions of daily users and are therefore the prime target. By using a private tracker you are diminishing the likelihood of receiving an infringement letter, however, it is still not impossible.

 4. **Download using DDL** (direct download) methods, such as google drive, mega, zippyshare, etc. DDL is a blanket term used for any sort of direct connection between you and a single other server. Such transfers could take the form of HTTP, ftp, etc.

 5. **Download from usenet**. Check the [/r/usenet wiki](/r/usenet/wiki) for more info. Usenet is especially great for Movie and TV content and many usenet providers will provide SSL-encrypted downloads, allowing for greater peace of mind.

For more information on VPNs, seedboxes, and private trackers, check out the following resources:

* [Discussion: Seedbox vs VPN?](https://www.reddit.com/r/TechnologyProTips/search?q=seedbox+vs+vpn&sort=relevance&t=all)

* <https://www.reddit.com/r/VPN/wiki/index>

* <https://www.reddit.com/r/seedboxes/>

* <http://seedboxgui.de/guides/what-is-a-seedbox/>

* <https://www.reddit.com/r/trackers/comments/51ay9n/frequently_asked_questions/>

&nbsp;

### ► *I just got a letter/email from my ISP about copyright infringement, what happens now?*

The repercussions for pirating content vary by country. What may just be a mere *educational warning* in one country, may lead to the suspension/termination of your internet service in another country. Your ISP may have outlined the repercussions in the letter/email you received. As an example, the UK-based ISPs, Sky and Virgin, deliver educational emails to copyright violators. Virgin is ambiguous about repurcissions whereas Sky has explicitly mentioned that violations will not result in service suspension. US-based ISPs are also likely to terminate your service if you get too many repeated complaints for copyright infringement -- [the number of warnings before termination of service is supposedly 6.](https://sg.news.yahoo.com/six-strikes-explained-us-readies-piracy-warning-system-145127585.html) For more information regarding repercussions, your letter/email most likely states it, if not, refer to your ISP's ToS.

Furthermore, you shouldn't worry about being prosecuted for downloading pirated material. When people speak of being prosecuted for distribution of copyrighted content, they refer to the parties that make the pirated material available to begin with, such as streaming/torrent/pirate site operators. There are cases where the average joe can get into legal trouble for distribution, and those are cases that are referred to as example cases. One such case would be streaming pirated material to your fanbase on twitch, where people know your face and likely know your full real name, and copyright holders would want to prosecute these personalities to make an example out of them. Simple, every-day acts of piracy are not prosecuted, as they do not have any worth to the copyright holders, example-wise or monetary-wise (they would lose more money in lawyer fees than they'd get from you in a settlement).

The typical response to a copyright infringement letter is to just ignore it, move on with your day and follow the above advice on preventing further notices. If your internet has been shut down by your ISP, call them and ask what you can do to restore service, but never admit fault.

**Again, keep in mind that different countries will have different laws regarding what the punishment should be. In certain countries, like Germany, you are likely to be hit with a sizable fine for copyright infringement. [Read this](https://www.reddit.com/r/Piracy/comments/fbf5so/fine_for_downloading_movie/) if you live in Germany and have received letter indicating that you will be fined.**

&nbsp;

### ► *I got caught pirating and my ISP has instructed me to delete the pirated material from my hard drive. Should I?*

No, you don't need to. Your ISP cannot tell what's on your hard drive or not. As long as you follow the above advice on preventing further copyright infringement notices, you should be all set.

&nbsp;

### ► *What VPN should I get?*

A paid VPN is recommended, as there are no good free ones that allow torrent traffic, not to mention that most will mine data from you for marketing purposes. You should seek a VPN that does not store connection and usage logs. Within this subreddit and Reddit as a whole, you will find aggressive VPN marketing tactics by nearly all top popular VPN services. Do your own research. You will often encounter the suggestion to visit [That One Privacy Site](https://thatoneprivacysite.net/vpn-section/). Do not rely blindly on the chart and look up each individual VPN’s ToS. Many VPNs offer trials and refunds, use these to your benefit when determining which VPN best suits your needs. Below are some good research material to start with:

* <https://torrentfreak.com/vpn-anonymous-review-160220/>

* <https://www.reddit.com/r/VPN/wiki/index>

* <https://www.reddit.com/r/Privacy/wiki/index>

&nbsp;

* <https://www.eff.org/issues/copyright-trolls>

* <http://help.bittorrent.com/customer/portal/articles/178790-the-basics-of-bittorrent>

&nbsp;

### ► Extra information on VPNs

* Popular VPN services aggressively market themselves on Reddit. Do not subscribe to a service just because Reddit deems it popular, cheap, or because it hits the front page. You are entrusting an entity with your personal data; do your own research. Keep in mind that VPN experiences are completely anecdotal. Someone's experience with a particular VPN may vary from location, servers, operating systems, downloads speeds, etc...

* With that said, below are some resources with which you may begin your research. Most if not all popular VPNs offer trials and/or immediate refunds. Use them to your advantage in your quest to find a VPN that works best for you. Don't forget to also read their ToS!

* [ThatOnePrivacySite VPN Chart](https://thatoneprivacysite.net/##simple-vpn-comparison/)

* [Choosing the best VPN for you](https://www.reddit.com/r/VPN/comments/4iho8e/that_one_privacy_guys_guide_to_choosing_the_best/?st=iu9u47u7&sh=459a76f2)

* [**Which VPN Services Keep You Anonymous in 2019?**](https://torrentfreak.com/which-vpn-services-keep-you-anonymous-in-2019/)

* [Which VPN Services Keep You Anonymous in 2018?](https://torrentfreak.com/vpn-services-keep-anonymous-2018/)

* [TorrentFreak 2016 VPN interview](https://torrentfreak.com/vpn-anonymous-review-160220/)

* [EEF Overview on what a VPN is and how to choose one](https://ssd.eff.org/en/module/choosing-vpn-thats-right-you)

* <https://www.reddit.com/r/VPN/wiki/index>

* <https://www.reddit.com/r/Privacy/wiki/index>

* Beware of free VPNs if you plan on using one for online purchases or to log into websites with sensitive data. Many free VPNs are able to provide their free services because they data mine, interpose ads in searches, etc...

* Beware of pirating VPNs. You wouldn't pirate a condom?

* [An alternative to purchasing your VPN is hosting your own](https://www.reddit.com/r/VPN/search?q=vps&restrict_sr=on). You will have much more flexibility and you can have your VPS hoster outside your country's copyright law jurisdiction.

&nbsp;

&nbsp;
