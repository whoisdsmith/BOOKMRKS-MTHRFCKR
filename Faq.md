---

---

[**◄◄ Back to Wiki Index**](https://www.reddit.com/r/Piracy/wiki/index)

---

---

# /r/Piracy FAQ - Frequently Asked Questions

### ► General questions

* Will I get in trouble for downloading `x` or browsing a pirate site? How to avoid getting in trouble when pirating in general?

 > [Guide on protecting yourself when downloading pirated content -- All about copyright infringement complaints and what to do if you've received one.](https://www.reddit.com/r/Piracy/wiki/faq/isp_complaints)

* Preliminary measures to take to avoid running malware-infected files (in regards to non-software)

 > [Browsing and downloading guide](https://www.reddit.com/r/Piracy/wiki/browsing_and_downloading_guide)

* [How do I download and activate windows 10 (including LTSC/LTSB)? How do I upgrade to windows 10 from a prior pirated windows version?](https://www.reddit.com/r/Piracy/wiki/guides/win10upgrade_activation)

 > Can I receive updates on my now-activated windows 10 PC as normal? **Yes**. Will it break the activation? **No**.

 >

 > I want to disable updates just in case, how do I do this? **Don't do this. You need security updates.**

* [How do I install and activate Office?](https://old.reddit.com/r/Piracy/wiki/guides/office_activation)

* [What is a private tracker and how do I get started? Benefits of private trackers, etc.](https://www.reddit.com/r/Piracy/wiki/guides/private_trackers)

* [What is usenet and how do I get started? - /r/usenet wiki](https://www.reddit.com/r/usenet/wiki/index)

* What is "The Scene" and where do they upload their releases? e.g. Groups such as (Movies & TV) SPARKS, AMIABLE, PSYCHD, ROVERS, GECKOS, VENUE, LOST, SHORTBREHD, etc. (Games) CODEX, SKIDROW, CPY, RELOADED, etc.

 > They upload to private FTPs. You will never have access to them.

 >

 > [Short, concise, and simplistic explanation of what "The Scene" is](https://www.reddit.com/r/Piracy/comments/32isgo/noobpirate_what_is_a_scene_cracktorrent/) - Reddit thread

 >

 > [What is the difference between "The Scene" and p2p?](https://www.reddit.com/r/Piracy/comments/b0c0ns/difference_between_the_scene_and_p2p/) - Reddit thread. Outdated, but the idea is the same.

 >

 > [Warez Scene](https://en.wikipedia.org/wiki/Warez_scene) - Wikipedia

* What are services like All-Debrid, premiumizeMe, real-debrid used for?

 > As a standalone service, they will download things for you for you to later download from them at full speed. They are useful for file hosts which limit your download speeds unless you subscribe to their service. It can be used with torrents too, so their servers will do the downloading to prevent your IP from ever hitting the torrent swarm (which is the cause of copyright infringement complaints). You then download the content from their servers directly.

 >

 > They keep the downloads in their servers for a while, for as long as people are trying to grab content from a particular link. So in conjunction with streaming apps that support real debrid, it works as a caching service, so that you can stream the popular links at full speed from real debrid as opposed to streaming directly from the slow file hosts.

* [How do you guys know if a virus warning is a false positive or not?](https://www.reddit.com/r/Piracy/comments/n62da6/how_do_you_guys_know_if_a_virus_warning_is_a/gx4whhz/) - Answer by /u/ilike2burn

&nbsp;

### ► Torrenting and VPN questions

* Is it recommended to use a VPN when downloading pirated material?

 > If you are torrenting, yes. Using a VPN is not necessary when downloading from DDL sites such as Google drive, mega, zippy share, etc. Some countries may have lax copyright laws so you may not need a VPN at all, even when torrenting. [Read more here.](https://www.reddit.com/r/Piracy/wiki/faq/isp_complaints)

* Which free VPN service is recommended for downloading torrents?

 > None. Free VPNs are likely to collect data from you for marketing purposes, be too slow to bother with, or do not allow torrent traffic in the first place. It's recommended to purchase a subscription of a VPN service - many can be as cheap as 3 USD/month, if you buy in bulk.

* How can I access websites that my ISP is blocking?

 > Try using proxies for popular sites listed under [Megathread > Tools](https://old.reddit.com/r/Piracy/wiki/megathread/tools#wiki_.25BA_pirate_site_proxies_.2F_unblockers). Alternatively, some ISPs simply do blocking at the DNS level, so you'll need to change your DNS settings in your router's configuration. Some DNS services you can use are [Cloudflare](https://developers.cloudflare.com/1.1.1.1/setting-up-1.1.1.1/), [openDNS](https://www.opendns.com/), [DNS-Watch](https://dns.watch/). Google how to change your DNS settings for your specific router model (or simply brand, as their WEB GUIs don't typically change all that much between revisions). Enter the IPs that your new chosen DNS service provided you.

 >

 > If changing your DNS service provider did not work, then you may use a VPN. [ProtonVPN](https://protonvpn.com/free-vpn) is a good, free, and privacy-oriented VPN service provider that you can use to access blocked sites.

* My torrent download speeds are hecking slow or stalled even though the torrent site is reporting a ton of seeders for that torrent. What do?

 > As a preliminary measure, check the website you got the torrent file from to see how many peers are in the swarm. If there is an equal or greater amount of peers than seeders, it's only natural that your download speeds will be slow - you'll have to wait it out. If your torrent is stalled, right click on it and choose to re-announce yourself to the swarm.

 >

 > Make sure DHT is enabled in your torrent client's settings, this will allow you to find more peers through the DHT network.

 >

 > Most importantly, make sure you are connectable. In your torrent client's settings, find the setting that lists the port for "incoming connections". Change the port number to one in [the range of 49152 - 65535](https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers#Dynamic,_private_or_ephemeral_ports). Visit this [site](https://www.canyouseeme.org/) and enter the port number you changed it to and it'll tell you if you are reachable or not. If it shows you are not reachable, you'll need to whitelist the port number in your [windows firewall settings](https://www.tomshardware.com/news/how-to-open-firewall-ports-in-windows-10,36451.html) and in your router settings. You'll need to google how to accomplish this, as it will depend on your router's model/brand.

 >

 > If you are using a VPN, make sure you are using a VPN service that allows port forwarding. If they allow port forwarding, they will allow you to enable port forwarding via their control panel, either on their website or directly through their app. Choose to open a port from their control panel, and then change your torrent client's port for incoming connections to match that same port number. That should be it - You won't need to mess with your firewall or router settings afterwards.

&nbsp;

### ► Downloading from websites

* How do I download video/audio from streaming websites? (Excludes Premium Youtube Videos, as these are protected by Widevine DRM. No public tools available to decrypt the streams.)

 > With [Youtube-DL](https://ytdl-org.github.io/youtube-dl/index.html) (open-source command-line tool). Alternatively, you can use [Youtube-DLG.](https://mrs0m30n3.github.io/youtube-dl-gui/), which is a GUI for Youtube-DL

 >

 > [JDownloader2](http://jdownloader.org/jdownloader2) also works well. Also allows you to add your login credentials in order to access premium-only content that your account has access to.

 >

 > [Internet Download Manager](https://www.internetdownloadmanager.com/download.html) will do the job as well, though it is a premium application. Also allows you to add your login credentials in order to access premium-only content that your account has access to. Use the free trial, then when the trial is nearing its end, simply reset the trial [with this.](https://github.com/J2TEAM/idm-trial-reset)

 >

 > You may also try out Video Download Helper extensions for your browser.

* How the heck do I use or install Youtube-DL?

 > [Guide](https://jcutrer.com/howto/how-to-install-youtube-dl-the-easy-way) on how to install it.

 >

 > [List of commands](https://www.ostechnix.com/youtube-dl-tutorial-with-examples-for-beginners/) available with Youtube-DL.

 >

 > [Example of use](https://streamable.com/p6152): type `cmd` into the navigation bar of windows explorer to open a terminal.

 > If you have a video that needs a login to access, youtube-dl supports adding your credentials and uses your login to grab the video stream. Example usage: `youtube-dl -u "myusername" -p "mypassword" "myvideoURL"`

 >

 > If using the `-u` and `-p` flags won't work for you, you can always input your cookies, which will contain your login session, for youtube-dl to use to download the content. Download the browser extension "cookies.txt", which will download your cookies (firefox link [here](https://addons.mozilla.org/en-US/firefox/addon/cookies-txt/), chrome link [here](https://chrome.google.com/webstore/detail/cookiestxt/njabckikapfpffapmjgojcnbfjonfjfg)). Then use the `--cookies` flag to pass in the downloaded cookies file to youtube-dl. Usage: `youtube-dl --cookies "/path/to/cookies" "myvideoURL"`

* How do I download from spotify?

 > You can't. There aren't any tools that can download the unencrypted spotify streams. The best method is to convert your Spotify playlist to a Deezer playlist, then download that via [Deemix](/r/Deemix). More sites/tools for music available in the [megathread](https://reddit.com/r/Piracy/wiki/megathread/music).

* How do I download from pan baidu?

 > <https://cs.rin.ru/forum/viewtopic.php?f=30&t=75480>

&nbsp;

### ► Movies & TV

* Why do file sizes of videos with the same resolution vary so much? Which release do I get? Which is better?

 > Video filesizes vary due to the varying levels of compression settings applied while encoding the video. More info: [Breakdown of video naming conventions, bitrate and quality. Also covered: converting mkv to mp4](https://www.reddit.com/r/Piracy/wiki/guides/video_quality_and_types_of_releases)

* How can I encode a video?

> To do quick and dirty encodes to lower the filesizes of your video library, check out [Tdarr](https://github.com/HaveAGitGat/Tdarr). To get more polished-looking encodes, you'll want to take a more manual approach. Check the [Wiki > Guides](https://www.reddit.com/r/piracy/wiki/guides) page for proper encoding guides.

* Why do some of my downloads have dull/darkened/washed out colors?

 > You downloaded a video with HDR metadata. You need an HDR-capable display to play it back properly, else you'll have to use a tone-mapping software such as madVR with a video player such as [MPC](https://github.com/clsid2/mpc-hc). [MPV](https://mpv.io/) includes tone-mapping by default.

* How long does it take for new movies to release on torrent sites in HD?

 > About 3 months following the theater date. Check <https://www.dvdsreleasedates.com/> for the digital release. The blu-ray/DVD follows 2 weeks later, but is usually leaked up to 2 weeks early from somewhere in the production chain, coinciding with the digital release. It is extremely rare for the digital to get leaked, so for all intents and purposes, the official digital release date ***is*** the pirate release date.

 >

 > Some movies get an official early release in South Korea (typically 1-1.5 months following the theater release), offered as pay-per-view in hotels in mini personal theaters where they get screencapped. These are referred to as "Korsubs", due to the hardcoded korean subtitles, though the quality can be pretty bad. Further reading: [\[Reddit Thread\] Where do KorSubbed rips come from?](https://www.reddit.com/r/Piracy/comments/dvznas/where_does_the_korsub_rips_come_from/)

>

> During the holiday season (Nov/Dec), [Screeners](https://en.wikipedia.org/wiki/Screener_\(promotional\)) get sent out to a select jury, which will be comprised of Academy members/critics, who are expected to review them and vote on the films that excel at specific categories. The recipients of these screeners will typically rip and send their copy of the screener to select pirate groups who will take charge in removing any and all embedded invisible watermarks in the video and release it publicly. These releases are also not very high quality.

 >

 > Other forms of early releases come in the shape of CAM or TELESYNC releases. These are not high quality at all -- the telesync releases usually appearing on torrent sites are mislabeled and are simply cams. These are simply theater screens recorded with a mobile camera and are of terrible quality. These types of recordings come with a good deal of risk, however, so people only bother with movies that are in high demand, such that they can make money selling access or by plastering advertisements on the recording. New cam releases are typically found on general trackers, such as [1337x.to](https://1337x.to/).

* How long does it take for TV episodes to become available to pirate?

 > Depends on the popularity, ease of access, workload of the first person who gets it, fucks he gives about it, etc.

 >

 > There is no way of telling when a show is released after it airs. Sometimes it's a couple hours or days, sometimes it's 5 minutes after it airs.

* Poem by /u/d3str0yer

&nbsp;

### ► Games

Also check out the [Steam Underground's FAQ](https://cs.rin.ru/forum/viewtopic.php?f=10&t=98158)

* Where do the groups **CODEX, CPY, SKIDROW, HOODLUM, RELOADED, SiMPLEX, DARKSiDERS, PLAZA**, etc release? Do they have a website?

 > The groups mentioned here are known as Scene groups. "The Scene" is an underground community of different groups who leak and share copyrighted material. They do not have public websites, so any website using their name to advertise themselves are likely only doing so for the purpose of spreading malware. There are other sites that post Scene releases, however. You may find them at the [Megathread > Games](https://old.reddit.com/r/Piracy/wiki/megathread/games) page.

* Where does EMPRESS release to?

 > EMPRESS releases to 1337x

* Is EMPRESS a Scene group?

 > No, EMPRESS is a P2P group. P2P is a blanket term used for basically any group or persons that are not part of the Scene - they will release via means of torrents, to message boards like cs.rin.ru, etc.

* Is `x` game cracked? When will it be cracked?

 > Nobody knows when a game will be cracked. Scene groups don't announce their intentions publicly. P2P groups like EMPRESS *may* announce their next crack, but it's more common for them to just stay silent until they decide to release their new crack. As a general rule, games with no special protection can easily be cracked on the same day of its official release, it all depends on whether it's a popular enough game to merit attention. Games with special DRM schemes like Denuvo require a high degree of knowledge and require laborious work to crack (can be several days to weeks of work), and game cracking groups that are willing to put that much time and effort into doing so are hard to come by. At the time of writing (Nov 2, 2020), there are currently 2 groups working on Denuvo cracks: CPY and EMPRESS. CODEX has previously released Denuvo cracks but it is not likely that they'll do so anymore. To check if a game has been cracked (especially Denuvo titles), check /r/CrackWatch's pinned thread for [Games with special DRM schemes](https://old.reddit.com/r/CrackWatch/comments/ieo7u4/crack_watch_games/) and their crack status.

* Can I request a game to be cracked?

 > The Scene doesn't take requests, they crack what they want when they want. If a game is a Steam game that is not protected by a special DRM like the games listed in /r/CrackWatch's pinned Games thread linked above, then you may request someone to share clean steam files at cs.rin.ru, which you may then crack yourself with a Steam Emulator like Mr. Goldberg's. Check the Steam Tools section at the [Megathread > Games](https://old.reddit.com/r/Piracy/wiki/megathread/games) page.

* Will I get banned from steam/origin/uplay/epic if i play a pirated game?

 > **No.** You will also not get banned from steam if you use the "Add a non-steam game to my library" function to add a pirated game.

* Are the game sites linked in the [megathread](https://www.reddit.com/r/Piracy/wiki/megathread) safe?

 > If you use general trackers that allow user uploading you'll have to be careful and are generally best avoided unless you can be sure the indexer is well-moderated. Also avoid using torrent aggregators/DHT crawlers (such as snowfl, torrentz2, btdig, etc.) to download games or other software. The reason for this is not because the sites intend to infect you with malware, but because their intent is to aggregate as many publicly available torrents as possible into one place. This can include torrents that have been posted to TPB or otherwise spread publicly via the DHT network.

>

> If you use the dedicated game websites listed in the `Games` section, then yes, they're safe. ^^^^But ^^^^that's ^^^^exactly ^^^^what ^^^^a ^^^^malware ^^^^distributor ^^^^would ^^^^say...

* My game downloads are being flagged as malware by my antivirus.

 > That is the nature of cracked files. Not to say that you should trust every loon in a youtube video that says "it's a false positive, go ahead and install", but the sites listed in the [megathread](https://www.reddit.com/r/Piracy/wiki/megathread) listed under the `Games` section are safe to use as proper game cracks will yield few generic detections. If you have an adblocker and used the proper download link, you should be good to go. Browsing pirate sites without an adblocker will just yield adverts posing as download buttons, which will yield virus-infected downloads, so make sure you're not just clicking on the most vibrant-looking link.

* Fitgirl is packed with ViRuSes!?

 > Read above, [fitgirl's site](http://fitgirl-repacks.site/) is safe to use.

* Fitgirl's repacks are taking a hecking long time to install. Why?

 > Fitgirl's repacks are extremely compressed, so they'll take a long time to decompress and will take several hours to install, even on a beefy system. They are intended for people with *very* slow or data-capped internet, in order to give them a chance to download a game in a timely manner or without blowing through their data cap. If you have a strong internet connection, you may try downloading the original release from which the repack was created (whether it's a Scene release, P2P, or GOG) or another repacker's repack in order to avoid the super long installation times.

* Why does the cracked game I just installed bring up the store page or crash with `missing .dll` error messages?

 > Either you didn't apply the crack files or your antivirus deleted the cracks. If you installed a scene release (CODEX, CPY, SKIDROW, HOODLUM, etc) or other non-Scene release like EMPRESS', read the section below for how to apply the crack. If you've applied the crack but you're still being prompted to buy the game, check your antivirus, as it may have quarantined the crack files. Set an exception for the game install directory and the original download directory. If you installed a repacked (like fitgirl, xatab, elamigos, dodi, etc), then the crack should have been applied automatically, check your antivirus quarantine/exclusion settings as previously stated.

* How do I install a pirated game and apply the crack?

 > If your download yielded a set of rar files in parts (in a sequence of `.r00`, `.r01`, `.r02`, etc.), then simply find the non-numbered `.rar` file, right click on it, and click `extract here`. Example image: <https://i.imgur.com/WhaFCSu.jpg>.

 > It will automatically extract and combine the data from all the other parts and yield an `.iso` file.

 >

 > Installing from the`.iso` file requires you to "mount" it onto your system as a virtual disc. Windows 10 has this functionality built-in. Just right click on the `.iso` file, select properties, then choose to change the program that handles `.iso` files. Choose Windows Explorer, then just click OK.

 >

 > After setting Windows Explorer as the default program for `.iso` files, simply double click on the `.iso` file to mount it. It will take you to the folder structure contained inside the `.iso` file, then just run the setup `.exe` file to install the game.

 >

 > Default installations for Scene releases are usually for the base game without a crack, so you'll need to take steps to patch the game files with the crack files post-installation. If you are installing a repack, then the crack files will be applied automatically during installation, no further steps needed. Otherwise, read below.

 >

 > Some Scene groups' installers may be one-click installs and will have a checkbox that says `move crack files to installation directory`, so make sure that box is checked before starting the installation - that's all there is to it, the game will be cracked once the installation finishes. Otherwise, read the `readme` file included in your download. It's usually an `.nfo` file, but they are just text files, just right click on it and choose edit to open it.

 >

 > The instructions contained within the `.nfo` will remain consistent between releases: the common method for games is to just copy and paste the crack files included with your download, to your game's installation folder which is by default `C:\Program Files` or `C:\Program Files (x86)`. The crack files may sometimes be contained in a non-descript folder, usually just named after the release group, eg. `CODEX`.

* Can I transfer the save files from my cracked game install to my soon-to-be-purchased game install?

 > In some cases, save files that are sourced from an older version of a game may not work on a newer version, and since pirated games tend to be running on the version that the game originally released on, this may be the case for you. Save files may also not transfer over cleanly between different releases by different groups. It may be the case that there is a save converter tool available at [cs.rin.ru](https://cs.rin.ru/forum/), so check there to see if there is one for your specific game.

 >

 > To find the save location of the save file, you only need to google it. Naturally, you will find answers regarding the purchased version of the game, but you only need to find the save file's name and file extension. Afterwards, just install [Everything](https://www.voidtools.com/), a file indexer and browser program, to instantly search through your entire filesystem (upon install, you may have to wait a bit for it to index all your files). Then just search for the file extension to see where the save file might be in your system (since pirated game installs may store save files elsewhere than the legitimate version). To search for a file extension, type `*.extension`, depending on what the extension is for your game's save files.

* How can I play co-cop (LAN-play) with a friend of mine?

 > If the game does not use Steam Connect to find LAN players, you can use software such as [ZeroTier](https://www.zerotier.com/) or [PlayHide](https://playhide.eu/) to set up a self-hosted VPN solution for your friend to join and be able to see you in the game's co-op listing.

&nbsp;
