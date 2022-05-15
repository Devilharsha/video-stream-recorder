# video stream recorder
hls live video stream recorder / vod service provider

for latest version check https://github.com/streamingriver/video-stream-recorder/releases

downloader:
```
./vsr --url http://full/url/with/m3u8 --tail 24

url = m3u8 url to process
tail = how many hours keep
```

wath live (last downloaded files):
```
http://youripaddress:8080/live/stream.m3u8
```


watch recorder stream via your favorite video player:
```
http://youripaddress:8080/start/<timestamp>/300/stream.m3u8

or with normal full date with seconds:

http://youripaddress:8080/start/20191225150000/300/vod.m3u8

```
replace "{timestamp}" to localtime unix timestamp (https://www.epochconverter.com/)
replace 300 with how long video is (if you dont know, keep 300)


## ✨ Deploy to Heroku ✨

ᴄʟɪᴄᴋ ᴛᴏ ᴅᴇᴘʟᴏʏ sᴄʀᴇᴇɴ ᴏғ ʜᴇʀᴏᴋᴜ ғɪʟʟ ᴀ ᴠᴀʀs ɴᴏᴡ ʙᴏᴛ ʀᴜɴs ʜᴇʀᴏᴋᴜ!
<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/Devilharsha/video-stream-recorder"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-black?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>



