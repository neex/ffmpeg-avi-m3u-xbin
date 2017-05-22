## Usage

1. `./gen_xbin_avi.py file://<filename> file_read.avi`
2. Upload `file_read.avi` to some website that processes videofiles
3. (on server side, done by the videoservice) `ffmpeg -i file_read.avi output.mp4`
4. Click "Play" in the videoservice.
5. If you are lucky, you'll the content of `<filename>` from the server.

## How it works

TBD

