# Note

This repo is a way for me to build static binaries of ffmpeg for the main OS's.


### Docker

 - Command to build docker images for the binaries:

`docker build -f Dockerfile.linux -t ffmpeg-linux .`
`docker build -f Dockerfile.windows-cross -t ffmpeg-win .`

