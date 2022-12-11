---

---



[<- Back to FAQ](https://www.reddit.com/r/piracy/wiki/faq)

---

---

### ► Preliminary steps to avoid accidentally running a malware infected file

For software, the best places are going to be private trackers, as they tend to have staff members dedicated to checking the validity of torrents uploaded. rutracker is a large public tracker that is well-known for their music and software catalogue. If you're going to download software and you don't want to make the effort to join private trackers, rutracker is one of the best public tracker to use. Warezbb is a great board for software (if you can catch it when it's not down).

If you're going to download software/games, [definitely avoid the piratebay](https://www.reddit.com/r/Piracy/comments/cxbn33/psa_ransomware_all_current_vegas_pro_17_torrents/). They have an immense amount of fake torrents and it's just not worth the risk of wading through their crap heap.

If you're going to download other torrents that aren't software, you can at least take preliminary measures that you're not running a fake file, even if you download from TPB.

The following examples use video files as an example, and while it is wholly possible to include malware in anything, malware in files like video files, music files, aren't a likely scenario. Even then, they would have to target a specific program (ie. a specific video player) to attempt to exploit in order to tailor a video file with malware only meant to be able to run on such a video player. The main idea here is to use up-to-date programs in order to prevent being a victim of most of these exploits.

If you're looking for video, obviously an exe file is not what you're looking for, so that's an obvious candidate for the trash bin. Other attack vectors include intentionally bloated videos that simply contain messages like "download `x` codec to properly view this video". In the download folder there may be a link or executable to install the supposed "codecs", which will obviously be malware.

SFX files may also be used to spread malware, as they are "self extracting executables", but by all intents and purposes treated as executables themselves. Do not run software if you do not trust the source.

Pay close attention to the file icon to make sure that it's recognized as a video file instead of anything else. If you have file extensions hidden, files such as `NotAVirus.mp4.exe` will simply show as `NotAVirus.mp4`, but they'll show the executable icon because windows sees the real file extension. Make sure you [unhide file extensions.](https://support.winzip.com/hc/en-us/articles/115011457948-How-to-configure-Windows-to-show-file-extensions-and-hidden-files)

❗ Be on the lookout for RTL naming schemes that may make a filename of `filename.3pm.exe` be displayed as `filename.exe.mp3`: [Further Reading.](https://resources.infosecinstitute.com/spoof-using-right-to-left-override-rtlo-technique-2/)

Another attack vector includes windows shortcuts, which will provide (as an example) a supposed `videofile.avi` video file but it's actually shortcut to a batch/powershell other type of script, and won't show as such even with file extensions shown. The file icon may also be one similar to that of a video player's, but if you pay close attention to it, you'll notice an arrow in the corner that indicates it's a shortcut. Also note the `file type` column in file explorer showing `Shortcut`: <https://i.imgur.com/e0Cgeje.jpg>. In the screenshot, the tiny filesize is a giveaway, but these attack vectors typically 0-byte pad the file to inflate the filesize, in an attempt to make it look more convincing. [Some reading on this](https://blog.trendmicro.com/trendlabs-security-intelligence/rising-trend-attackers-using-lnk-files-download-malware/) [TrendMicro]. This type of download will never not be malware.

Use proper video players instead of the default windows media player: MPC, MPV, VLC.

Popular video file types will be avi, mp4, mkv. `wmv`, `wma` video/audio containers' specs allow for scripts, which windows media player can try to run.

Not very common, but `.scr` files are "screensaver setter" files that are actually just executables. Avoid these.

&nbsp;
