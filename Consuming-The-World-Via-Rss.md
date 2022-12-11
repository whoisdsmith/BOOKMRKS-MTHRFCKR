# consuming-the-world-via-rss

This is supposed to provide a quick overview over some options one has with news feeds.

**Github**  
Releases  
[https://github.com/owner/repo/releases.atom](https://github.com/owner/repo/releases.atom)  
Tags  
[https://github.com/owner/repo/tags.atom](https://github.com/owner/repo/tags.atom)  
Commits  
[https://github.com/owner/repo/commits/branch.atom](https://github.com/owner/repo/commits/branch.atom)

[https://www.githubstatus.com/history.rss](https://www.githubstatus.com/history.rss) (incident report history)  
[https://github.com/security-advisories](https://github.com/security-advisories) (security advisories)

**Hacker News**  
[https://edavis.github.io/hnrss/](https://edavis.github.io/hnrss/)  
[https://github.com/polyrabbit/hacker-news-digest](https://github.com/polyrabbit/hacker-news-digest) ([http://hackernews.betacat.io/feed](http://hackernews.betacat.io/feed))  
[https://news.ycombinator.com/rss](https://news.ycombinator.com/rss)  
with article contents: [https://morss.it/https://news.ycombinator.com/rss](https://morss.it/https://news.ycombinator.com/rss)

**TwitchRSS** (check RSSBox for alternative)  
[https://twitchrss.appspot.com/vod/channelname](https://twitchrss.appspot.com/vod/channelname) (Appends " - LIVE" if a live broadcast)  
[https://twitchrss.appspot.com/vodonly/channelname](https://twitchrss.appspot.com/vodonly/channelname) (Only shows vods)  
[https://github.com/lzeke0/TwitchRSS](https://github.com/lzeke0/TwitchRSS)  
Note: If the channel has vod archival disabled, the feed will remain empty  
or  
[https://github.com/m3taas/stfg](https://github.com/m3taas/stfg) (turn twitch follow list into feeds)

**YouTube**  
[https://www.youtube.com/feeds/videos.xml?channel\_id=ChannelID](https://www.youtube.com/feeds/videos.xml?channel_id=ChannelID)  
[https://invidious.instance/feed/channel/ChannelID](https://invidious.instance/feed/channel/ChannelID)  
[https://invidious.instance/feed/playlist/PlaylistID](https://invidious.instance/feed/playlist/PlaylistID)

Youtube as podcast  
[https://github.com/alnixon/youtube-dl-podcast](https://github.com/alnixon/youtube-dl-podcast) (shell script)  
[https://github.com/mlichwa/YT-Podcaster](https://github.com/mlichwa/YT-Podcaster) (php app)  
[https://github.com/frou/yt2pod](https://github.com/frou/yt2pod)  
[https://github.com/podify-org/podify](https://github.com/podify-org/podify) ([https://www.podify.org/](https://www.podify.org/))  
[https://github.com/BurnsCommaLucas/youtube-dl-podcast](https://github.com/BurnsCommaLucas/youtube-dl-podcast) (requires API key)  
[https://github.com/i3arnon/YouCast](https://github.com/i3arnon/YouCast)  
[https://github.com/mxpv/podsync](https://github.com/mxpv/podsync)  
[https://www.podnoms.com/](https://www.podnoms.com/) (requires registration)  
[https://listenbox.app/](https://listenbox.app/) (demo: [https://listenbox.app/i/gbG5sTFjmMA](https://listenbox.app/i/gbG5sTFjmMA)) (requires registration, does not update for free)

**BitChute**  
[https://www.bitchute.com/feeds/rss/channel/ChannelName/](https://www.bitchute.com/feeds/rss/channel/ChannelName/)

**Soundcloud / iTunes**  
[https://getrssfeed.com/](https://getrssfeed.com/)  
e.g. [https://soundcloud.com/user-98066669](https://soundcloud.com/user-98066669) -&gt; [https://feeds.soundcloud.com/users/soundcloud:users:261098918/sounds.rss](https://feeds.soundcloud.com/users/soundcloud:users:261098918/sounds.rss)

iTunes only  
[http://picklemonkey.net/feedflipper-home/](http://picklemonkey.net/feedflipper-home/)  
[https://podshows.fr/itunesrss](https://podshows.fr/itunesrss)  
[https://github.com/gromnitsky/itunesrss](https://github.com/gromnitsky/itunesrss) (demo: [http://gromnitsky.users.sourceforge.net/js/itunesrss/](http://gromnitsky.users.sourceforge.net/js/itunesrss/))  
or  
take the iTunes ID  
[https://itunes.apple.com/podcast/id967692038](https://itunes.apple.com/podcast/id967692038) -&gt; 967692038  
[https://itunes.apple.com/lookup?id=967692038&amp;entity=podcast](https://itunes.apple.com/lookup?id=967692038&entity=podcast) (returns json metadata; 'feedUrl' for feed)  
as a bookmarklet: [https://github.com/djm/uncover-itunes-rss-bookmarklet](https://github.com/djm/uncover-itunes-rss-bookmarklet)

[https://www.apple.com/rss/](https://www.apple.com/rss/)  
[https://rss.itunes.apple.com/](https://rss.itunes.apple.com/) ([https://affiliate.itunes.apple.com/resources/blog/introduction-rss-feed-generator/](https://affiliate.itunes.apple.com/resources/blog/introduction-rss-feed-generator/))

**Spotify**  
[https://github.com/timdorr/spotifeed](https://github.com/timdorr/spotifeed) (demo: [https://spotifeed.timdorr.com/](https://spotifeed.timdorr.com/))

**Reddit**  
[https://www.reddit.com/.rss](https://www.reddit.com/.rss)  
[https://www.reddit.com/r/subreddit.rss](https://www.reddit.com/r/subreddit.rss)  
[https://www.reddit.com/user/user.rss](https://www.reddit.com/user/user.rss)  
([https://old.reddit.com/r/pathogendavid/comments/tv8m9/pathogendavids\_guide\_to\_rss\_and\_reddit/](https://old.reddit.com/r/pathogendavid/comments/tv8m9/pathogendavids_guide_to_rss_and_reddit/))

[https://reddit-top-rss.herokuapp.com/](https://reddit-top-rss.herokuapp.com/) (for specific subreddits with score thresholds)  
[https://github.com/johnwarne/reddit-top-rss](https://github.com/johnwarne/reddit-top-rss)

[https://inline-reddit.com/feed/?subreddit=crackwatch/new](https://inline-reddit.com/feed/?subreddit=crackwatch/new)  
[https://inline-reddit.com/feed/?multireddit=security&amp;user=goretsky](https://inline-reddit.com/feed/?multireddit=security&user=goretsky)  
([https://hg.icculus.org/icculus/inline-reddit/](https://hg.icculus.org/icculus/inline-reddit/))

[https://reddit.0qz.fun/r/subreddit.json](https://reddit.0qz.fun/r/subreddit.json)

**Telegram**  
\- [https://tg.i-c-a.su/](https://tg.i-c-a.su/) (supports media downloads)  
&nbsp;- [https://tg.i-c-a.su/json/channelname](https://tg.i-c-a.su/json/channelname)  
&nbsp;- [https://tg.i-c-a.su/rss/channelname](https://tg.i-c-a.su/rss/channelname)

**Tumblr**  
[https://nasa.tumblr.com/rss](https://nasa.tumblr.com/rss)

**Facebook**  
[https://github.com/irfancharania/fb-feed-gen](https://github.com/irfancharania/fb-feed-gen)

**WebOas.is** (ElkArte)  
[https://weboas.is/forum/index.php?action=.xml;type=atom;limit=10;board=20.0](https://weboas.is/forum/index.php?action=.xml;type=atom;limit=10;board=20.0)

**Mastodon**  
[https://Mastodon.Instance/users/userhandle.rss](https://mastodon.instance/users/userhandle.rss)  
or  
[https://Mastodon.Instance/@userhandle.rss](https://mastodon.instance/@userhandle.rss)

**Stack Exchange**  
Specific question  
[https://stackoverflow.com/feeds/question/15869473](https://stackoverflow.com/feeds/question/15869473)  
Recent Questions  
[https://stackoverflow.com/feeds/](https://stackoverflow.com/feeds/)  
https://\*.stackexchange.com/feeds/featured (/hot, /week, /month)  
SE Site Directory  
[https://stackexchange.com/feeds/sites](https://stackexchange.com/feeds/sites)

**"A Directory of RSS Feeds of Popular Social Sites"**  
[https://www.labnol.org/internet/rss-feeds-directory/21242/](https://www.labnol.org/internet/rss-feeds-directory/21242/)

**Tools**

**Torrent Trackers**  
[https://github.com/Jackett/Jackett](https://github.com/Jackett/Jackett)

**RSSBox**  
[https://rssbox.herokuapp.com/](https://rssbox.herokuapp.com/)

Allows generation of Atom feeds for  
\- Twitter (All posts, excluding retweets and replies, with media)  
\- Youtube (uses feed provided by Youtube)  
\- Vimeo  
\- Instagram (all posts, only videos/photos, downloads of posts)  
\- Periscope  
\- SoundCloud (play, download)  
\- Mixcloud  
\- Twitch (only Highlights, open in vlc://, download link with ffmpeg, irc-chat access)  
\- speedrun.com  
\- ustream (download)  
\- imgur (all, only animated/pictures/albums)  
\- svt play

It can be self-hosted on Heroku, with Elastic Beanstalk, Kubernetes or your regular Docker image.  
[https://github.com/stefansundin/rssbox](https://github.com/stefansundin/rssbox)

**RSS-Bridge**  
[https://github.com/RSS-Bridge/rss-bridge](https://github.com/RSS-Bridge/rss-bridge)

Allows generation of Atom/RSS feeds for  
\- Bandcamp: last release from bandcamp for a tag  
\- Cryptome: most recent documents from Cryptome.org  
\- DansTonChat: most recent quotes from danstonchat.com  
\- DuckDuckGo: most recent results from DuckDuckGo.com  
\- Facebook: latest posts on a page or profile on Facebook  
\- FlickrExplore: latest interesting images from Flickr  
\- GoogleSearch: most recent results from Google Search  
\- Identi.ca: Identica user timeline (Should be compatible with other Pump.io instances)  
\- Instagram: most recent photos from an Instagram user  
\- OpenClassrooms: lastest tutorials from fr.openclassrooms.com  
\- Pinterest: most recent photos from user or search  
\- ScmbBridge: newest stories from secouchermoinsbete.fr  
\- ThePirateBay: returns the newest indexed torrents (with keywords)  
\- Twitter: keyword/hashtag search or user timeline  
\- Wikipedia: highlighted articles from Wikipedia in English, German, French or Esperanto  
\- YouTube: YouTube user channel, playlist or search  
And other "bridges" (xenforo, private trackers, wordpress, etc.):  
[https://github.com/RSS-Bridge/rss-bridge/tree/master/bridges](https://github.com/RSS-Bridge/rss-bridge/tree/master/bridges)  
Creating your own:  
[https://github.com/RSS-Bridge/rss-bridge/wiki/How-to-create-a-new-Bridge](https://github.com/RSS-Bridge/rss-bridge/wiki/How-to-create-a-new-Bridge)  
[https://github.com/RSS-Bridge/rss-bridge/wiki/BridgeAbstract](https://github.com/RSS-Bridge/rss-bridge/wiki/BridgeAbstract)  
Example:  
[https://github.com/RSS-Bridge/rss-bridge/blob/master/bridges/TwitchBridge.php](https://github.com/RSS-Bridge/rss-bridge/blob/master/bridges/TwitchBridge.php)

It supports multiple output formats:  
\- Atom  
\- HTML  
\- JSON  
\- Mrss  
\- plaintext  
And a format API to create custom ones:  
[https://github.com/RSS-Bridge/rss-bridge/wiki/How-to-create-a-new-Format](https://github.com/RSS-Bridge/rss-bridge/wiki/How-to-create-a-new-Format)  
[https://github.com/RSS-Bridge/rss-bridge/wiki/FormatInterface](https://github.com/RSS-Bridge/rss-bridge/wiki/FormatInterface)  
[https://github.com/RSS-Bridge/rss-bridge/wiki/FormatAbstract](https://github.com/RSS-Bridge/rss-bridge/wiki/FormatAbstract)  
Example:  
[https://github.com/RSS-Bridge/rss-bridge/blob/master/formats/HtmlFormat.php](https://github.com/RSS-Bridge/rss-bridge/blob/master/formats/HtmlFormat.php)

It can be self-hosted on Heroku, Scalingo or a regular Docker image.  
[https://github.com/RSS-Bridge/rss-bridge/wiki/Requirements](https://github.com/RSS-Bridge/rss-bridge/wiki/Requirements)  
[https://github.com/RSS-Bridge/rss-bridge/wiki/Installation](https://github.com/RSS-Bridge/rss-bridge/wiki/Installation)

Some websites hosting a public instance:  
[https://rss-bridge.snopyta.org/](https://rss-bridge.snopyta.org/) (247/247 bridges enabled)  
[https://sebsauvage.net/rss-bridge/](https://sebsauvage.net/rss-bridge/) (185/185 bridges enabled)  
[https://rss-bridge.lamop.fr/](https://rss-bridge.lamop.fr/)  
[https://wtf.roflcopter.fr/rss-bridge/](https://wtf.roflcopter.fr/rss-bridge/)  
[http://rssbridge.chamallow.com/](http://rssbridge.chamallow.com/)  
[https://rss.bka.li/](https://rss.bka.li/)  
[https://feed.eugenemolotov.ru/](https://feed.eugenemolotov.ru/)  
[https://college.kre.dp.ua/rss/](https://college.kre.dp.ua/rss/)  
List: [https://github.com/RSS-Bridge/rss-bridge/wiki/Public-hosts](https://github.com/RSS-Bridge/rss-bridge/wiki/Public-hosts)

Note: Like other website scrapers, such as searx, bridges like GoogleSearch may return HTTP 429 errors.

**RSSHub**  
[https://github.com/DIYgod/RSSHub](https://github.com/DIYgod/RSSHub)

Allows generation of Atom feeds for  
\- social media  
&nbsp;- Disqus  
&nbsp;- Mastodon  
&nbsp;- pixiv  
&nbsp;- Telegram  
&nbsp;- Twitter (following, timeline)  
&nbsp;- Youtube  
&nbsp;- etc. ([https://docs.rsshub.app/en/social-media.html](https://docs.rsshub.app/en/social-media.html))  
\- new media  
&nbsp;- Engadget  
&nbsp;- iDownloadBlog  
&nbsp;- Nautilus  
&nbsp;- The Verge  
&nbsp;- World Health Organization | WHO  
&nbsp;- etc. ([https://docs.rsshub.app/en/new-media.html](https://docs.rsshub.app/en/new-media.html))  
\- programming  
&nbsp;- GitHub  
&nbsp;- GitLab  
&nbsp;- Hacker News  
&nbsp;- Linux Patchwork  
&nbsp;- LWN.net  
&nbsp;- etc. ([https://docs.rsshub.app/en/programming.html](https://docs.rsshub.app/en/programming.html))  
\- etc. ([https://docs.rsshub.app/en/](https://docs.rsshub.app/en/))

Examples:  
[https://rsshub.app/twitter/user/noconviolence](https://rsshub.app/twitter/user/noconviolence)  
[https://rsshub.app/telegram/channel/DeezloaderRemix](https://rsshub.app/telegram/channel/DeezloaderRemix)  
[https://rsshub.app/github/repos/the-eye-team](https://rsshub.app/github/repos/the-eye-team)  
[https://rsshub.app/github/pull/busyloop/lolcat](https://rsshub.app/github/pull/busyloop/lolcat)

**Self-hosted Feed readers**  
[https://github.com/FreshRSS/FreshRSS](https://github.com/FreshRSS/FreshRSS) ([https://demo.freshrss.org/](https://demo.freshrss.org/))  
[https://git.tt-rss.org/fox/tt-rss](https://git.tt-rss.org/fox/tt-rss) ([https://github.com/HenryQW/Awesome-TTRSS](https://github.com/HenryQW/Awesome-TTRSS)) (demo: [https://srv.tt-rss.org/tt-rss/](https://srv.tt-rss.org/tt-rss/) (usr=demo, pass=demo)) ([https://tt-rss.snopyta.org/](https://tt-rss.snopyta.org/) ([https://account.snopyta.org/pwm/public/newuser](https://account.snopyta.org/pwm/public/newuser)))  
[https://github.com/codysnider/urss](https://github.com/codysnider/urss) (TT-RSS fork)  
[https://github.com/jaesivsm/JARR](https://github.com/jaesivsm/JARR) (demo: [https://jarr.info/](https://jarr.info/) (usr=5bnhbdk, pass=@f5.si))  
[https://github.com/samuelclay/NewsBlur](https://github.com/samuelclay/NewsBlur) ([https://www.newsblur.com/folder/everything](https://www.newsblur.com/folder/everything))  
[https://github.com/swanson/stringer](https://github.com/swanson/stringer)  
[https://github.com/feedbin/feedbin](https://github.com/feedbin/feedbin)  
[https://github.com/miniflux/miniflux](https://github.com/miniflux/miniflux) (Simplicity, seriously)  
[https://github.com/fazalmajid/temboz](https://github.com/fazalmajid/temboz) (two-column reader with a focus on filtering)  
[https://github.com/simplepie/simplepie](https://github.com/simplepie/simplepie) ([http://simplepie.org/demo/](http://simplepie.org/demo/))  
[https://github.com/LeedRSS/Leed](https://github.com/LeedRSS/Leed)  
[https://github.com/cubny/lite-reader](https://github.com/cubny/lite-reader) (demo: [http://cubny.com/lite-reader/](http://cubny.com/lite-reader/))  
[https://github.com/toxinu/leselys](https://github.com/toxinu/leselys)  
[https://github.com/tontof/kriss\_feed](https://github.com/tontof/kriss_feed) (demo: [https://tontof.net/feed/;](https://tontof.net/feed/;) [https://tontof.net/kriss/feed/](https://tontof.net/kriss/feed/))  
[https://github.com/Athou/commafeed](https://github.com/Athou/commafeed) (demo: [https://www.commafeed.com/](https://www.commafeed.com/) (usr=am2h, pass=am2h@tapi.re))  
[https://github.com/sismics/reader](https://github.com/sismics/reader) (demo: [https://reader-demo.sismics.com/](https://reader-demo.sismics.com/) (usr=demo, pass=demo))  
[https://github.com/channikhabra/yarr](https://github.com/channikhabra/yarr) ([http://channikhabra.github.io/yarr/](https://channikhabra.github.io/yarr/))  
[https://github.com/huginn/huginn](https://github.com/huginn/huginn) (IFTTT, but open-source, customizable and norse)([https://vimeo.com/61976251](https://vimeo.com/61976251))  
[https://github.com/nerevu/riko](https://github.com/nerevu/riko)  
[https://github.com/NicolasLM/feedsubs](https://github.com/NicolasLM/feedsubs) ([https://feedsubs.com/](https://feedsubs.com/))  
[https://github.com/pietheinstrengholt/rssmonster](https://github.com/pietheinstrengholt/rssmonster) (inspired by google reader)  
[https://github.com/feedhq/feedhq](https://github.com/feedhq/feedhq)  
[https://github.com/GetStream/Winds](https://github.com/GetStream/Winds)  
[https://github.com/jtanza/rufus](https://github.com/jtanza/rufus) ([http://rufus.news/](http://rufus.news/))  
[https://github.com/arussellsaw/news](https://github.com/arussellsaw/news) ([https://news.russellsaw.io/](https://news.russellsaw.io/))  
[https://github.com/geekuillaume/Freader](https://github.com/geekuillaume/Freader) ([https://freader-rss.herokuapp.com/](https://freader-rss.herokuapp.com/))  
[https://github.com/truerss/truerss](https://github.com/truerss/truerss) ([http://demo.truerss.net/](http://demo.truerss.net/))  
[https://github.com/harold/rss-box](https://github.com/harold/rss-box)  
[https://github.com/SSilence/selfoss](https://github.com/SSilence/selfoss)  
[https://sourceforge.net/projects/gregarius/](https://sourceforge.net/projects/gregarius/)  
[https://github.com/ncarlier/nunux-reader](https://github.com/ncarlier/nunux-reader)  
[https://github.com/ahernp/django-feedreader](https://github.com/ahernp/django-feedreader)  
Podcast-specific  
[https://github.com/janw/tapedrive](https://github.com/janw/tapedrive) (focus on archival)

**Feed Readers**  
[https://github.com/lwindolf/liferea](https://github.com/lwindolf/liferea)  
[https://github.com/QuiteRSS/quiterss](https://github.com/QuiteRSS/quiterss)  
[https://github.com/martinrotter/rssguard](https://github.com/martinrotter/rssguard)  
[https://support.mozilla.org/en-US/kb/how-subscribe-news-feeds-and-blogs](https://support.mozilla.org/en-US/kb/how-subscribe-news-feeds-and-blogs)  
[https://github.com/newsboat/newsboat](https://github.com/newsboat/newsboat) (for all those lynx users)  
\- [https://github.com/akinozgen/youtube-to-newsboat](https://github.com/akinozgen/youtube-to-newsboat) (converts youtube Subscriptions export to newsboat urls file)  
[https://github.com/Lallassu/gorss](https://github.com/Lallassu/gorss) (another cli feed reader)  
[https://github.com/seenaburns/picofeed](https://github.com/seenaburns/picofeed) (yet another cli feed reader)  
[https://git.sr.ht/~tho/lydia](https://git.sr.ht/~tho/lydia)  
[https://github.com/hello-efficiency-inc/raven-reader](https://github.com/hello-efficiency-inc/raven-reader)  
[http://www.feedbucket.com/](http://www.feedbucket.com/) (web-based service)  
[https://github.com/mikefrancis/nosh](https://github.com/mikefrancis/nosh) (demo: [https://nosh.rocks/](https://nosh.rocks/))  
[https://github.com/moonmoon/moonmoon](https://github.com/moonmoon/moonmoon)  
[https://github.com/readerself/readerself](https://github.com/readerself/readerself)  
[https://github.com/dertuxmalwieder/rssfs](https://github.com/dertuxmalwieder/rssfs)  
[https://github.com/flok99/rsstail](https://github.com/flok99/rsstail) (tail for rss feeds)  
[https://github.com/gvalkov/rsstail.py](https://github.com/gvalkov/rsstail.py)  
[https://github.com/YoloSwagTeam/feedstail](https://github.com/YoloSwagTeam/feedstail)  
[https://github.com/tylerharper/wag](https://github.com/tylerharper/wag)  
Podcast-specific  
[https://github.com/gpodder/gpodder](https://github.com/gpodder/gpodder)  
[https://github.com/manolomartinez/greg](https://github.com/manolomartinez/greg)  
[https://github.com/rafaelmartins/marrie](https://github.com/rafaelmartins/marrie)  
[https://github.com/brokkr/poca](https://github.com/brokkr/poca)  
[https://github.com/m3nu/upodder](https://github.com/m3nu/upodder)  
[https://github.com/arthurnn/podcast](https://github.com/arthurnn/podcast)  
[https://github.com/IBM/PodcastDownloader](https://github.com/IBM/PodcastDownloader)  
[https://github.com/janw/podcast-archiver](https://github.com/janw/podcast-archiver) (focus on archival)  
[https://github.com/robotmlg/podsnatch](https://github.com/robotmlg/podsnatch) (focus on archival)  
Android  
[https://github.com/FredJul/Flym](https://github.com/FredJul/Flym) ([https://f-droid.org/en/packages/net.frju.flym/](https://f-droid.org/en/packages/net.frju.flym/))  
[https://gitlab.com/spacecowboy/Feeder](https://gitlab.com/spacecowboy/Feeder) ([https://f-droid.org/en/packages/com.nononsenseapps.feeder/](https://f-droid.org/en/packages/com.nononsenseapps.feeder/))  
[https://github.com/nilsbraden/ttrss-reader-fork](https://github.com/nilsbraden/ttrss-reader-fork) ([https://f-droid.org/en/packages/org.ttrssreader/](https://f-droid.org/en/packages/org.ttrssreader/))  
[https://github.com/poloure/rss](https://github.com/poloure/rss) ([https://f-droid.org/en/packages/com.poloure.simplerss/](https://f-droid.org/en/packages/com.poloure.simplerss/))  
[https://github.com/aminecmi/ReaderforSelfoss](https://github.com/aminecmi/ReaderforSelfoss) ([https://f-droid.org/en/packages/apps.amine.bou.readerforselfoss/](https://f-droid.org/en/packages/apps.amine.bou.readerforselfoss/))  
[https://git.feneas.org/christophehenry/freshrss-android](https://git.feneas.org/christophehenry/freshrss-android) ([https://f-droid.org/en/packages/fr.chenry.android.freshrss/](https://f-droid.org/en/packages/fr.chenry.android.freshrss/))  
[https://play.google.com/store/apps/details?id=com.spians.plenary](https://play.google.com/store/apps/details?id=com.spians.plenary)  
Browser extension  
[https://github.com/podStation/podStation](https://github.com/podStation/podStation)  
[https://github.com/adamsanderson/brook](https://github.com/adamsanderson/brook)  
[https://github.com/dauphine-dev/drop-feeds](https://github.com/dauphine-dev/drop-feeds)  
[https://github.com/SmartRSS/Smart-RSS](https://github.com/SmartRSS/Smart-RSS)

[https://en.wikipedia.org/wiki/List\_of\_podcatchers](https://en.wikipedia.org/wiki/List_of_podcatchers)  
[https://en.wikipedia.org/wiki/Comparison\_of\_feed\_aggregators](https://en.wikipedia.org/wiki/Comparison_of_feed_aggregators)  
[https://wiki.archlinux.org/index.php/List\_of\_applications/Internet#News\_aggregators](https://wiki.archlinux.org/index.php/List_of_applications/Internet#News_aggregators)

**Feed View in Firefox** (Removed in Firefox 64+)  
[https://github.com/brief-rss/brief](https://github.com/brief-rss/brief)  
[https://nodetics.com/feedbro/](https://nodetics.com/feedbro/)  
[https://github.com/shgysk8zer0/awesome-rss](https://github.com/shgysk8zer0/awesome-rss) (Brings back the Feed Subscription button in the URL bar)  
[https://github.com/aureliendavid/rsspreview](https://github.com/aureliendavid/rsspreview) (Brings back the Feed Preview)  
[https://addons.mozilla.org/firefox/addon/feed-preview/](https://addons.mozilla.org/firefox/addon/feed-preview/) (comparable to the one above; [https://hg.guido-berhoerster.org/addons/firefox-addons/feed-preview/](https://hg.guido-berhoerster.org/addons/firefox-addons/feed-preview/))  
[https://addons.mozilla.org/firefox/addon/rss-html/](https://addons.mozilla.org/firefox/addon/rss-html/) (keeps it simple; does not preserve feed url)

**Manual RSS Builders**  
[http://createfeed.fivefilters.org/](http://createfeed.fivefilters.org/)  
[https://politepol.com/en/](https://politepol.com/en/) ([https://github.com/taroved/pol](https://github.com/taroved/pol))  
[https://feed43.com/](https://feed43.com/) (demo: [https://node2.feed43.com/weboasis\_tech\_feed.xml](https://node2.feed43.com/weboasis_tech_feed.xml))  
[https://github.com/damoeb/rss-proxy/](https://github.com/damoeb/rss-proxy/) (demo: [https://rssproxy.migor.org/](https://rssproxy.migor.org/))  
[https://feedity.com/](https://feedity.com/)  
[https://rss.app/rss-feed](https://rss.app/rss-feed)  
[http://fetchrss.com/manual](http://fetchrss.com/manual)

**Full Article Extractors**  
[https://github.com/pictuga/morss](https://github.com/pictuga/morss) (demo: [https://morss.it/](https://morss.it/))  
[https://fulltextrssplz.whtsky.me/](https://fulltextrssplz.whtsky.me/)  
[https://www.freefullrss.com/](https://www.freefullrss.com/)  
[http://fullcontentrss.com/](http://fullcontentrss.com/)  
[https://feedex.net/](https://feedex.net/)  
[http://ftr.fivefilters.org/](http://ftr.fivefilters.org/)

**Item Filtering**  
[https://siftrss.com/](https://siftrss.com/)  
[https://github.com/bcongdon/rssfilter](https://github.com/bcongdon/rssfilter) (demo: [https://rssfilter.netlify.app/](https://rssfilter.netlify.app/))  
[https://github.com/gromnitsky/grepfeed](https://github.com/gromnitsky/grepfeed) (demo: [https://serene-river-17732.herokuapp.com/](https://serene-river-17732.herokuapp.com/))

**Other Feed Generators**  
[https://github.com/amsehili/genRSS](https://github.com/amsehili/genRSS) (media library -&gt; rss)  
[https://github.com/herrbischoff/screaming-liquid-tiger](https://github.com/herrbischoff/screaming-liquid-tiger) (media library -&gt; rss)  
[https://github.com/albertobeta/PodcastGenerator](https://github.com/albertobeta/PodcastGenerator) ([http://www.podcastgenerator.net/demo](http://www.podcastgenerator.net/demo))  
[https://github.com/fossasia/searss](https://github.com/fossasia/searss) (search engine result -&gt; rss)  
[https://github.com/Kombustor/rss-fulltext-proxy](https://github.com/Kombustor/rss-fulltext-proxy) (retrieves full-text content)  
[https://github.com/mediadrop/mediadrop](https://github.com/mediadrop/mediadrop)  
[https://github.com/dewey/feedbridge](https://github.com/dewey/feedbridge) ([https://feedbridge.notmyhostna.me/](https://feedbridge.notmyhostna.me/))  
[https://fivefilters.org/content-only/](https://fivefilters.org/content-only/)  
[http://www.webrss.com/](http://www.webrss.com/)  
[https://github.com/h43z/rssify](https://github.com/h43z/rssify) (python script with configurable scraping)

**Feedsearch**  
[https://feedsearch.dev/](https://feedsearch.dev/) (using [https://github.com/DBeath/feedsearch-crawler](https://github.com/DBeath/feedsearch-crawler))  
[http://www.rssmicro.com/api.web](http://www.rssmicro.com/api.web)  
[https://feedly.com/i/search/](https://feedly.com/i/search/)  
[https://www.datorss.com/](https://www.datorss.com/)  
[https://github.com/davidesantangelo/feedirss-api](https://github.com/davidesantangelo/feedirss-api) ([https://api.feedirss.com/](https://api.feedirss.com/))  
[https://github.com/AntonioStipic/RssNewsAPI](https://github.com/AntonioStipic/RssNewsAPI) ([https://newsapi.xyz/](https://newsapi.xyz/))  
[https://search.feedi.me/](https://search.feedi.me/) ([https://github.com/davidesantangelo/feedi](https://github.com/davidesantangelo/feedi))  
[http://www.2rss.com/](http://www.2rss.com/)  
[https://feeds.pub/explore](https://feeds.pub/explore)

**Podcastsearch**  
[https://podbay.fm/](https://podbay.fm/)  
[https://www.listennotes.com/](https://www.listennotes.com/)  
[https://player.fm/](https://player.fm/)  
Use the magnifying glass in the top right corner, search for talks/podcasts, go to the page and click "Public Feed".  
[https://podurama.com/home](https://podurama.com/home)  
[https://podhunt.app/](https://podhunt.app/)  
[https://podhound.co/](https://podhound.co/)  
[https://podflix.app/](https://podflix.app/)  
[https://podnami.com/](https://podnami.com/) (podcast episodes aggregator)  
[https://pod.link/](https://pod.link/)  
[https://pdcstly.com/](https://pdcstly.com/)  
[http://rssrad.io/#/podcast/search](http://rssrad.io/#/podcast/search)  
[https://fyyd.de/](https://fyyd.de/)  
[https://blubrry.com/podcast-search/](https://blubrry.com/podcast-search/)  
[https://overcast.fm/](https://overcast.fm/)  
[https://www.podchaser.com/](https://www.podchaser.com/)  
[https://vocalmatic.com/podcasts](https://vocalmatic.com/podcasts)  
[https://www.spreaker.com/](https://www.spreaker.com/)  
[https://podsearch.com/](https://podsearch.com/)

Feed2Mail  
[https://github.com/rcarmo/rss2imap](https://github.com/rcarmo/rss2imap)  
[https://github.com/wking/rss2email](https://github.com/wking/rss2email)  
[https://github.com/skx/rss2email/](https://github.com/skx/rss2email/) (golang port of the above)  
[https://github.com/sulami/feed2maildir](https://github.com/sulami/feed2maildir)  
[https://github.com/teythoon/rss2maildir](https://github.com/teythoon/rss2maildir)  
[https://github.com/jspricke/rss2maildir](https://github.com/jspricke/rss2maildir)  
[https://github.com/feed2imap/feed2imap](https://github.com/feed2imap/feed2imap)  
[https://github.com/acg/rssdrop](https://github.com/acg/rssdrop) (rss to maildir)  
[https://github.com/sloonz/ua](https://github.com/sloonz/ua) ('rss2json' tool)  
[https://www.feedsub.com/](https://www.feedsub.com/)  
[https://blogtrottr.com/](https://blogtrottr.com/)  
[https://feedlivery.com/](https://feedlivery.com/)  
[https://myrss.email/](https://myrss.email/)

Feed2Json  
[https://feed2json.org/convert?url=https://predb.org/rss.xml](https://feed2json.org/convert?url=https://predb.org/rss.xml)  
Note: Part of the effort to establish feeds in JSON, not XML. (Specification: [https://jsonfeed.org/version/1](https://jsonfeed.org/version/1))  
[https://meetingguide.org/validate?url=](https://meetingguide.org/validate?url=) (JSON feed validator)

Feed2IRC  
[https://github.com/gehaxelt/python-rss2irc](https://github.com/gehaxelt/python-rss2irc)

Feed2ActivityPub  
[https://github.com/dariusk/rss-to-activitypub](https://github.com/dariusk/rss-to-activitypub)

Embedding Feeds  
[https://github.com/bloopletech/rss2html](https://github.com/bloopletech/rss2html) ([https://rss.bloople.net/](https://rss.bloople.net/))

Lorem-RSS  
[https://github.com/mbertolacci/lorem-rss](https://github.com/mbertolacci/lorem-rss) ([https://lorem-rss.herokuapp.com/](https://lorem-rss.herokuapp.com/))

FeedValidator  
[https://www.feedvalidator.org/check.cgi?url=](https://www.feedvalidator.org/check.cgi?url=)  
[https://validator.w3.org/feed/](https://validator.w3.org/feed/)  
[https://castfeedvalidator.com/?url=](https://castfeedvalidator.com/?url=) (podcast-specific)  
[https://podba.se/validate/?url=](https://podba.se/validate/?url=) (podcast-specific)  
[http://rssvalidator.net/](http://rssvalidator.net/)  
[https://cap-validator.appspot.com/validate](https://cap-validator.appspot.com/validate)  
[https://www.zbozi.cz/validace-feedu/](https://www.zbozi.cz/validace-feedu/)

Other tools  
[https://github.com/synzen/Discord.RSS](https://github.com/synzen/Discord.RSS) (discord rss bot)  
[https://backfeed.strangecode.com/](https://backfeed.strangecode.com/) (collecting removed entries from archive.org)  
[https://github.com/taophp/rss-merger](https://github.com/taophp/rss-merger) (merging multiple feeds)  
[https://github.com/jasonmunro/cypht](https://github.com/jasonmunro/cypht) ([https://cypht.org/install.html](https://cypht.org/install.html), webmail client)  
[https://github.com/anarcat/feed2tweet](https://github.com/anarcat/feed2tweet) (rss to twitter)  
[https://opml-gen.ovh/](https://opml-gen.ovh/) (opml generator)  
[https://github.com/embyt/balloonrss](https://github.com/embyt/balloonrss) (only notifications)

Libraries &amp; scripts  
[https://github.com/kurtmckee/feedparser](https://github.com/kurtmckee/feedparser) (feed parser written in python: doc: [https://pythonhosted.org/feedparser/](https://pythonhosted.org/feedparser/))  
[https://github.com/jmoiron/speedparser](https://github.com/jmoiron/speedparser) (rewrite of feedparser using lxml: diff: [https://github.com/jmoiron/speedparser#differences](https://github.com/jmoiron/speedparser#differences))  
[https://github.com/custom-components/feedparser](https://github.com/custom-components/feedparser) (feed parser for home-assistant)  
[https://github.com/lkiesow/python-feedgen](https://github.com/lkiesow/python-feedgen) (feed generator written in python: doc: [https://feedgen.kiesow.be/](https://feedgen.kiesow.be/))  
[https://github.com/grangier/python-goose](https://github.com/grangier/python-goose) (python article extractor)  
[https://github.com/danmactough/node-feedparser](https://github.com/danmactough/node-feedparser)  
[https://github.com/ahkimkoo/node-article-extractor](https://github.com/ahkimkoo/node-article-extractor)  
[https://github.com/j0k3r/graby](https://github.com/j0k3r/graby) (article extractor written in php)  
[https://github.com/advancedlogic/GoOse](https://github.com/advancedlogic/GoOse) (article extractor written in golang)  
[https://github.com/codelucas/newspaper](https://github.com/codelucas/newspaper) (doc: [https://newspaper.readthedocs.io/en/latest/](https://newspaper.readthedocs.io/en/latest/))  
[https://github.com/Anonyfox/elixir-scrape](https://github.com/Anonyfox/elixir-scrape) (feed scraper written in elixir)  
[https://github.com/feedparser/feedparser](https://github.com/feedparser/feedparser) (feed parser written in ruby)  
[https://github.com/sveetch/django-feedparser](https://github.com/sveetch/django-feedparser) (django app for rendering feeds)

**Other resources**  
[https://rssguide.neocities.org/](https://rssguide.neocities.org/) (guide to adding rss feed to Neocities site)  
[https://raymii.org/s/articles/Tiny-Tiny-RSS-Readability-plaintext.html](https://raymii.org/s/articles/Tiny-Tiny-RSS-Readability-plaintext.html) (TT-RSS + Readability)  
[https://www.godo.dev/tutorials/hugo-full-text-rss/](https://www.godo.dev/tutorials/hugo-full-text-rss/) (full text rss for hugo site)
