#Movie Parse

Install

`npm -g install movie-parse`

Usage:

`movie-parse "The.Staying.Alive.S05E02.720p.HDTV.x264-KILLERS[rartv]" "Arrow.S05E03.2015"`

##API

(http://movie-parse.massimo.me/?movie=The%20Martian%202015%201080p%20BluRay%20x264%20AC3%20ETRG])[http://movie-parse.massimo.me/?movie=The%20Martian%202015%201080p%20BluRay%20x264%20AC3%20ETRG]

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

(http://movie-parse.massimo.me/?movie[]=The%20Martian%202015%201080p%20BluRay%20x264%20AC3%20ETRG&movie[]=Mission%20Impossible%20Rogue%20Nation%202015%201080p%20WEB%20DL%20x264%20AC3%20JYK)[http://movie-parse.massimo.me/?movie[]=The%20Martian%202015%201080p%20BluRay%20x264%20AC3%20ETRG&movie[]=Mission%20Impossible%20Rogue%20Nation%202015%201080p%20WEB%20DL%20x264%20AC3%20JYK]

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
