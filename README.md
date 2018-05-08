ARM64 Dante proxy for Telegram
==============================
[![](https://images.microbadger.com/badges/image/zhukovra/tgdante-arm64.svg)](https://microbadger.com/images/zhukovra/tgdante-arm64 "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/zhukovra/tgdante-arm64.svg)](https://microbadger.com/images/zhukovra/tgdante-arm64 "Get your own version badge on microbadger.com")

## Features
* User management scripts
* Only telegram usage restrictions
* Try to autodetect interface and IPv6 support

## Requirements
* [Docker](https://www.docker.com/docker-community) for virtual containers

## Usage

#### Simple

```console
docker run -d --restart unless-stopped -p 1080:1080 -e USER=user0 -e PASS=secret0 --name tgdante zhukovra/tgdante-arm64
```

## Links
* Based on [x86_64 version](https://github.com/schors/tgdante2)
