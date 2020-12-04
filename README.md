# Video Summarizer

This tool lets you create a video summary. You can set the amount of parts and the time of this. Also, you can set if you want audio channel and how much threads will be used.

```
usage: video-summarizer [-h] [-p PARTS] [-q [QUIET]] [-s SECONDS]
                        [-na [NO_AUDIO]] [-t THREADS]
                        input output

Video Summarizer CLI

positional arguments:
  input                 Input filename
  output                Output filename

optional arguments:
  -h, --help            show this help message and exit
  -p PARTS, --parts PARTS
                        Number of parts to split the video
  -q [QUIET], --quiet [QUIET]
                        Quiet
  -s SECONDS, --seconds SECONDS
                        Time in second to each parts
  -na [NO_AUDIO], --no-audio [NO_AUDIO]
                        Disable audio channel in the video
  -t THREADS, --threads THREADS
                        Number of threads to work
```
