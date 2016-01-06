#Movie Parse

Install

`npm -g install movie-parse`

Usage:

`movie-parse "The.Staying.Alive.S05E02.720p.HDTV.x264-KILLERS[rartv]" "Arrow.S05E03.2015"`

##API

[Test with one movie](http://bit.ly/1SzRGTr)

```json
{  
   "year":2015,
   "resolution":"1080p",
   "quality":"BluRay",
   "codec":"x264",
   "audio":"AC3",
   "title":"The Martian",
   "group":"ETRG"
}

```

[Test with more movies](http://bit.ly/1VIMxZ5)

```json
[  
   {  
      "year":2015,
      "resolution":"1080p",
      "quality":"BluRay",
      "codec":"x264",
      "audio":"AC3",
      "title":"The Martian",
      "group":"ETRG"
   },
   {  
      "year":2015,
      "resolution":"1080p",
      "codec":"x264",
      "audio":"AC3",
      "title":"Mission Impossible Rogue Nation",
      "group":"JYK",
      "excess":[  
         "WEB",
         "DL"
      ]
   }
]

```

![Torrent Movie Parse](https://cloud.githubusercontent.com/assets/5167596/12103341/d1c973c4-b341-11e5-9744-e25ba27ca20c.png)

## Contributing

Take a look at the open
[issues](https://github.com/jzjzjzj/parse-torrent-name/issues) on the original
project and submit a PR!
