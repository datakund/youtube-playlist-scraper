## Youtube-Playlist-Scraper
A python library that uses browser automation to scrape videos from youtube playlist
It uses [datakund](https://pypi.org/project/datakund) internally

Complete Documentation available [here](https://youtube-api.datakund.com/en/latest/)


### Support
For any help / feedback you can message us here
* datakund@gmail.com
* https://t.me/datakund

### Installation

```sh
pip install youtube-playlist-videos-scraper
```

### Import

```javascript
from youtube-playlist-videos-scraper import *
```

### Open Playlist link

To open youtube playlist we use ``open`` function. It requires **url** as input parameter

```javascript
youtube.open("playlist_link_here")
```

### Fetch playlist videos

To fetch videos from youtube playlist we use ``get_playlist_videos`` method.
It requires **playlist_link** as input parameter.

```javascript
response=youtube.get_playlist_videos(playlist_link="playlist_link_here")
videos=response['body']
```

### Example Response

```sh
[
   {
      "Title":"Title",
      "Video_Link":"Video_Link"
   },
   {

   },
   ...
]
```

### DataKund
It uses [datakund](https://pypi.org/project/datakund/) internally to do browser automation
DataKund is an automation library that uses selenium & supports automation of many sites including [Youtube](https://youtube-api.datakund.com/en/latest/), [Amazon](https://amazon-api.datakund.com/en/latest/), [Twitter](https://twitter-api.datakund.com/en/latest/), [LinkedIn](https://linkedin-api.datakund.com/en/latest/) , [Google](https://google-api.datakund.com/en/latest/) etc.
