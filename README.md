#PYTRip
A collection of python functions to aid in ripping songs from YouTube in MP3 format.

#Usage
```python
import PYTRip
```

Download a song from a specific URL to a folder:
```python
PYTRip.downloadToMP3(url,folder)
```

Download a whole playlist:
```python
PYTRip.downloadPlaylist(url, folder)
```
*The songs will be stored in a subdirectory named after the playlist*

Download a song:
```python
PYTRip.downloadSong(artist, song, folder)
```

Download the top search results for an artist:
```python
PYTRip.downloadTop(artist, number, folder)
```
*The number parameter is optional and defaults to 5*

#Dependencies
* [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/)
* [Pafy](https://pypi.python.org/pypi/Pafy)
* [Pydub](http://pydub.com/)