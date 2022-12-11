---

---



[◄◄ Back to Guides](https://www.reddit.com/r/piracy/wiki/guides)

---

---

## ► **How do i know which release is the better one?**

It all depends on the bitrate of the video, which is an indication of average amount of data processed per second. For video, it will be indicated by units of Mb/s (Megabits per second). Given 2 videos of equal length, the larger one will obviously have a higher bitrate. Given an x264-encoded video, most people will settle at a bitrate of 4000 kbps (4 Mbps) at 720p (Which would give you a 2GiB file a 1-hour movie, or 4GiB for a 2-hour movie). Any less and the video will look [extremely pixelated.](https://i.imgur.com/WVsOaJ0.jpg), especially given that most low-bitrate inclined groups tend churn out re-encodes through automation upon the first releases, which tend to be already-encoded releases, instead of encoding from the remux (See BRRips below). Higher bitrates are preferred by enthusiasts, however, with the highest quality encodes reaching upwards of 10-20 GiB per movie, and Remuxes (unadulterated video straight from the disc), reaching even higher.

&nbsp;

## ► On Bitrate and Codecs

Just a note before we go into codecs: a ‘container’ is the name for the small wrapper that contains video data and codec data. It can be identified by its file extension. MP4, MKV, AVI, FLV, and WEBM are examples.

Extra note: An MKV can hold any kind of video, audio, and subtitles, including all the ones listed below.

&nbsp;

**Codecs:**

A ‘codec’ is a specification on how to convert from raw data to images on a screen. When a video file is stored, there is a specific codec that converts that data into what you see.

Video files that use a specific codec are said to be ‘encoded’ using that codec.

Some codecs are better than others in the sense that they can get more quality using fewer bits (smaller filesizes) than others. We describe these codecs as ‘more efficient’.

Here is a small list of popular codecs:

**Xvid**

Xvid isn’t actually a codec, it’s a program that encodes videos. The name for the codec it uses is MPEG-4 ASP, but that never stuck. Quality-wise, it was OK for it’s time (2001!), but doesn’t hold a candle to modern codecs. Usually contained in AVI containers.

**H.264**

Also called MPEG-4 AVC, this codec is used everywhere, basically. Usually contained in MP4, if not MKV.

**VP9**

Developed by Google and used in YouTube and WEBM, this codec usually beats out H.264 by a small margin. Since no media standard uses it (Blu-Rays use H.264 or H.265), you won’t see this one very often. Usually contained in WEBM

**H.265**

Also called HEVC. It is the successor to H264 and it aims to reduce filesizes by up to 50% compared to H264, though this number is not a blanket figure to be applied to every single scenario. H265 is more effective at higher resolutions, so the 50% figure might be applicable to 4K, though the savings can still be considerable at 1080p and 720p. Many people choose to download small-sized H265 content that would otherwise be too blurry on H264. Though H264 still reigns supreme at higher bitrates, as x265 (the encoding tool used to create H265 video) is still not as mature as x264, which is why many quality-oriented private trackers still maintain a higher focus on x264-encoded content. Some 1080p Blu-Rays and all 4K Blu-Rays use this one.

Usually contained in MP4, if not MKV.

&nbsp;

## ► **Resolution**

Resolution refers to the number of pixels in an image or a single frame of a video file. It is usually expressed in the form WxH, where W is the width of the frame and H is the height. Most televisions are ‘Full HD’, which means 1920x1080. ‘UHD’, on the other hand, is twice the width and height to make 3840x2160. Most individuals and companies call this specific resolution ‘4K’.

(Historically, the term ‘4K’ referred to a slightly wider 4096x2160, but for the sake of simplicity, this article takes the most commonplace definition.)

Additionally, resolution can be expressed as the height of the image followed by a ‘p’. 1920x1080 becomes 1080p, 3840x2160 (4K) becomes 2160p. This can be a very loose definition, however, as movies that are produced at a wider aspect ratio will be called 1080p, yet will have a resolution 1920x800.

&nbsp;

## ► **Why do Movie/TV-Show torrents vary so wildly in file size?**

***A: Different compression settings, resulting in different bitrates.***

The term ‘bitrate’ refers to the number of bits (ones and zeros) per second for a video or audio file. This number directly affects both quality and filesize. A video file with a high bitrate will result in a larger filesize than one with a low bitrate (assuming equal runtime), and will be more detailed. How much of this detail you see will be dependent upon you and your set up (ie. the size of your screen, how far you sit from it). Most people will settle at a bitrate of 4000 kbps (4 Mbps) at 720p (Which would give you a 2GiB file a 1-hour movie, or 4GiB for a 2-hour movie). When watching on a small screen (like a phone), the requirements will go even lower (down to 1 Mbps or maybe even lower).

For a more visual description, consider the image comparisons linked below.

Video runtime: 2 hr 50 min.

[Image 1](https://i.ibb.co/SwzV8NX/bomi-snapshot-2020-01-08-00-55-05.png) (AVC / **1080p** / 24.2 Mbps / 31 GiB). Cropped [Image.](https://files.catbox.moe/dywl65.png)

[Image 2](https://i.ibb.co/8YC5fXq/bomi-snapshot-2019-12-25-20-08-04.png) (x264 / **1080p** / 10.7 Mbps / 15 GiB).

[Image 3](https://i.ibb.co/fQYr3F1/bomi-snapshot-2020-01-08-02-01-49.png) (x264 / **720p** / 5.85 Mbps / 9 GiB).

[Image 4](https://i.ibb.co/XLQCncc/bomi-snapshot-2019-12-25-20-07-39.png) (x264 / **1080p** / 0.15 Mbps / example shot).

As you can see, the last image has been aggressively compressed and is completely bitstarved. This is why resolution is not an indicator of quality, but rather an indicator of maximum quality. The better indicator of quality is bitrate.

A higher bitrate yields better quality at the cost of filesize. Conversely, a lower bitrate takes up less space, but hurts image quality. Dual-layer Blu-Ray discs hold 50 GiB. If you see a movie release that’s 1.4 GiB, don’t be surprised if it’s not up to par.

Bitrate is usually measured in megabits per second, abbreviated to Mbps (note the lowercase ‘b’). One byte is 8 bits, so **one megabyte is 8 megabits**.

You can calculate bitrate by finding the file’s size **in megabits**, and then dividing by the length of the file in seconds. You don't have to take out a calculator every time though, as you can install [Mediainfo](https://mediaarea.net/en/MediaInfo), which allows you to right click on a video file and it will display all relevant data, including bitrate of all of its individual tracks.

&nbsp;

## ► **Converting from MKV to MP4**

Oftentimes people will ask how to convert an mkv file to mp4 for the purpose of playing it on their TV. Many TVs in fact do not support mkv file formats, which is a newer container than mp4 is. This doesn't mean that the container is the only culprit. Check your TV's manual online and look for a list of supported formats and codecs, because it may be that your TV does support MKV but your specific MKV file contains certain streams encoded in a particular format that is not supported by your TV. You can use [mediainfo](https://mediaarea.net/en/MediaInfo) to check the different tracks inside your video file to check which codec they are encoded as, and compare them to your TV's list of supported specs to see what the culprit is.

If in fact, your TV does not support the MKV container, converting to MP4 is simple. Many users recommend using handbrake to do this -- ignore them. Handbrake will always transcode the video stream, and if it turns out that you only need to transcode the audio track, or simply do a complete remux, you'll be introducing unnecessary quality loss. Not to mention that transcoding video is very tough on the CPU and can take hours to complete.

As a first resort, do a remux (a direct copy of the streams in a container into another, no quality is lost). This is a very quick process and will only take a few minutes. You can use [ffmpeg](https://www.ffmpeg.org/), a commandline utility, to remux a video [\(How to install ffmpeg\)](https://www.youtube.com/watch?v=UDIMVp4jWXo). Afterwards, navigate to the folder containing your MKV file, then follow [these instructions](https://streamable.com/uhshg).

Essentially, you'll run the command `ffmpeg -i "infile.mkv" -c copy "outfile.mp4"`. This will remux your mkv file into an mp4 file. However, mkv supports a lot of codecs that mp4 doesn't, so in case the audio file is incompatible with either the mp4 format or your TV, you'll need to transcode the audio as well: `ffmpeg -i "infile.mkv" -c:v copy -c:a ac3 "outfile.mp4"`

Alternatively, in case you want to transcode the audio to AAC: `ffmpeg -i "infile.mkv" -c:v copy -c:a aac "outfile.mp4"`

Sometimes, multi-channel AAC tracks can produce playback issues, so lowering the number of channels to stereo might solve them: `ffmpeg -i "infile.mkv" -c:v copy -c:a aac -ac 2 "outfile.mp4"`

If the video track is encoded in a format not supported by your TV, find another download, as transcoding the video track will take entirely too long to be worth a bother.

&nbsp;

## ► **Breakdown of the different parts of a Warez release name (Title.Of.The.Movie.YEAR.Source.Codec-GROUP)**

There are many different acronyms that exist in release names, but they all follow a similar format. In the example of a movie, it would be Title.Of.The.Movie.YEAR.Source.Codec-GROUP

* **Group** -  The name of the group who created/distributed the release.

* **Codec** -  Will indicate what the codec is of the main stream of each type. Eg. `Title.Of.The.Movie.2001.BluRay.DD5.1.x264-GROUP`, indicates that the audio track (or main audio track, if it has multiple) is encoded in Dolby Digital (AC3) with 5.1 channels, and the video has been encoded with the x264 encoder to H264/AVC.

* **Source** -  Will vary depending on the medium it was sourced from (BluRay, DVD, WEB). It will also vary depending on how the media was ripped (BRRip, WEBRip, HDRip, HDcam)

There are a few variations of WEB releases, mainly WEB-DL and WEBRip. Scene groups will not specify the type of WEB release their content is and will simply use WEB instead of specifiying WEB-DL or WEBRip. P2P groups will tend to specify between WEB-DL and WEBRip.

* **WEB-DL** -  This is a direct download of the video provided by the streaming service. It is unadulterated and simply remuxed (repackaged) into a popular video format (ie. mkv). Paid streaming services such as Netflix utilize [Widevine DRM](https://en.wikipedia.org/wiki/Widevine) to prevent downloading of the video stream. If somehow, you are able to, it will be encrypted. Only a handful of underground groups around the world (namely, The Scene) has access to tools to decrypt Widevine-protected content.

* **WEB** - This is the Scene's tag for WEB-DLs. [Scene rules.](https://scenerules.org/t.html?id=wdx264v1.0-ecb63c67.nfo)

* **WEBRip** -  This can be a vague term, in that it can mean that a web stream was screen captured or that it has been encoded down from a higher resolution WEB-DL (typically a 4k WEB-DL, encoded down to 1080p or 720p), which in many cases results in a higher quality video compared to the actual 720p or 1080p WEB-DL.

WEB releases can also have extra qualifiers which will indicate which streaming service is was sourced from. The scene doesn't provide this type of indication, so only p2p groups will indicate which streaming service it was sourced from.

An example of these are:

* **NF** -  Netflix

* **AMZN** -  Amazon prime video

* **IT** -  iTunes

* **DSNP** -  Disney Plus

There are other qualifiers that indicate other attributes regarding the release, though these apply to Bluray releases as well:

* **SDR** -  Standard Dynamic range. If it's a 4k release, it's a given that it is an HDR/HDR10 release, unless otherwise specified as `SDR`

* **DV** -  Dolby Vision. Only a handful of movies/shows (approximately 100 total, at the time of writing) have made their way onto the wild with DV metadata included. These releases are uploaded in the `.mp4` format since mkv does not have support for DV metadata.

* **Remux** -  Remuxing is the process of "repackaging" the streams inside a video container into another video container. However, in regards to Warez releases, `REMUX` is only used for Bluray releases, indicating that the main video stream from a Bluray has been remuxed into a single video file. The full bluray contains a number of different directories and video containers, each containing different different types of videos depending on the bluray, including extras such as cast Q&A, director interviews, deleted scenes, etc. Remuxes and full blurays can be many tens of GiB, averaging out at around 60 GiB per 4k remux.

Video containers are file formats such as mp4, mkv, avi, VOB (used by DVDs, example of a [raw DVD dump](https://i.imgur.com/mCYYOKI.jpg)), m2ts (used by Blurays), etc. They contain varying quantities of streams of different types (video, audio, subtitle streams, chapter information and other metadata, such as the video's FPS, the codepage the subtitle stream is encoded in -- typically UTF-8 if it is a text stream) and more. They will even contain the HDR/DV metadata included as a separate track.

* **Full Bluray** -  This is not indicated anywhere in the filename, however it can be easily perceived by paying attention to the video codec, as it can specify whether the video is an encode or if it is unadulterated. If the release title contains `AVC` or `HEVC`, then it means it is the unadulterated video (not encoded). Following that, if it contains `REMUX` in the title, then it is a single video file (an mkv file), otherwise it is the full bluray, shared as an `.iso` file or its contents dumped into a folder ([example of a bluray dump's file tree](https://i.imgur.com/FVAJh2j.jpg)).

The explanation for this is as follows: `H264` and `AVC` are the exact same things, they are video codecs. The same is true of `H265` and `HEVC`. They are, however, different from `x264` and `x265`, which are both encoders, utilized to encode video into the aforementioned codecs, respectively. That is why you'll see some videos include `x264` while others will use `H264` or `AVC`, assuming they are named correctly. In regards to Bluray releases, if it says `x264` or `x265`, then it has been encoded from the original bluray. If it says `AVC` or `HEVC`, then it means the video is unadulterated from the original bluray.

Bluray releases are be indicated by BluRay, BDRip, or BRRip

* **BDRip** -  Encoded from the remux

* **BluRay** -  Vague terminology, can be used for either a full bluray, remux or encoded release

* **BRRip** -  Means it has been re-encoded from an existing bluray encode, which results in further quality loss compared to a regular bluray encode (which itself is encoded from the full bluray/remux): <https://redd.it/8bddu7>

&nbsp;
