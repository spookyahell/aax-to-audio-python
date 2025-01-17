# AAX to M4A/MP3 in Python

A simple script that wraps over other utils online to convert your own audible library to a more portable / free format.

Requires Python 3.6 and up, [ffmpeg](https://ffmpeg.zeranoe.com/builds/) and [inAudible-NG tables](https://github.com/inAudible-NG/tables/).
See [this awesome tutorial](https://wphelp365.com/blog/ultimate-guide-downloading-converting-aax-mp3/) on how to get the
two working. You really only need steps 1-4 to get the Activation Bytes.

Then it's just a matter of calling

```
python convert.py -i "The Tower of the Swallow.aax" -a xxxxxx -c copy
```

I really recommend the "-c copy" option as it copys the data from the original stream over (most players these day will be able to play it) if not you can ofc still ommit that and convert it to mp3

and have your owned aax converted into **mp3**s or **m4a**s (original / stream-copied / my recommendation), split by chapters, automatically with '_{Chapter_number}' appended to the end.

## Why?

Splitting the very long audio book files by chapters seemed like a much more sensible way of handling extended audio.
