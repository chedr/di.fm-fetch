#DI.fm Parser

Python3 Digitally Imported playlist parser based on [chuckatkins/DI.fm-PlaylistParser](https://github.com/chuckatkins/DI.fm-PlaylistParser/)

```
usage: di.fm-fetch [-h] [-o OUTPUT_DIR] [-s {di}] [-c {mp3,aac}]
                   [-q {40,64,128,96,256}] [-k KEY] [-l]

Extract DI.fm playlists

optional arguments:
  -h, --help            show this help message and exit
  -o OUTPUT_DIR, --output-dir OUTPUT_DIR
                        Output directory. Default: "."
  -s {di}, --source {di}
                        Playlist source, DI.fm. Default: "di"
  -c {mp3,aac}, --codec {mp3,aac}
                        Audio codec. Default: "aac"
  -q {40,64,128,96,256}, --quality {40,64,128,96,256}
                        Bitrate in kbps. Default: highest possible given codec
                        and free / premium constraints.
  -k KEY, --key KEY     Your premium Listen Key.
  -l, --long            Use the full channel title for the filename instead of
                        the short name.
```
