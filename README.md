# openwrt-feeds
A custom feed for my OpenWRT packages.

### Repository Usage

1. Move into the openwrt folder:

```bash
cd /path/to/openwrt
```

2. Add this repo into the feed configureation file:

```bash
echo "src-git core-labs https://github.com/core-labs/openwrt-feeds.git" >> feeds.conf.default
```