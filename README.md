Docker container for MPD
=======

Map your local music directory to the container's /mnt/music like this:
```
docker run --privileged=true -v /my/music/dir:/mnt/music -p 6600:6600 -p 8000:8000 finnyb/mpd
```

A playlists directory will be created inside this directory.  If you don't like this then mount your playlist
directory at /mnt/music/playlists

