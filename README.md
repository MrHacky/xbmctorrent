What it is
----------
This is a fork of the deprecated [XBMCTorrent](https://github.com/steeve/xbmctorrent) xbmc/kodi plugin because existing apps (chromes "Play to Kodi" and androids yatse) seem to send their magnet links directly to that plugin.

This project aims to intercept magnet links sent to kodi and handle them by using MrHacky/torrent-streamer. It is only used to implement this magnet link handling hook, and is not intended to use any of the original XBMCTorrent other functionality.

