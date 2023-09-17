# torrent-client

[![CircleCI](https://circleci.com/gh/veggiedefender/torrent-client.svg?style=shield)](https://circleci.com/gh/veggiedefender/torrent-client)

Tiny BitTorrent client written in Go. Read the blog post: https://blog.jse.li/posts/torrent/

## Build and Install

```sh
go build
```

## Usage
Try downloading [Debian](https://cdimage.debian.org/debian-cd/current/amd64/bt-cd/#indexlist)!


```sh
./torrent-client deb.torrent debian.iso
```

[![asciicast](https://asciinema.org/a/xqRSB0Jec8RN91Zt89rbb9PcL.svg)](https://asciinema.org/a/xqRSB0Jec8RN91Zt89rbb9PcL)


## Limitations
* Only supports `.torrent` files (no magnet links)
* Only supports HTTP trackers
* Does not support multi-file torrents
* Strictly leeches (does not support uploading pieces)
