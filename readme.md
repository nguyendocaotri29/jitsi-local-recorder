## Installation

```
git clone https://github.com/nguyendocaotri29/jitsiLocalRecorder.git
cd jitsi-local-recorder
./install.sh
```

Installation assumes Jitsi Meet's web files are located in `/usr/share/jitsi-meet/index.html`. 
If your files are located somewhere else, then run `./install.sh {{meet_web_dir}}` with the 
correct directory.

## getDisplayMedia testing

Load `getDisplayMedia.html` to:
 1. Check if your browser supports `getDisplayMedia` (it should)
 1. Demonstrate how getDisplayMedia ignores user constraints 
 1. Check if you can capture audio (currently only Chrome for some user selections)
 
 
 
