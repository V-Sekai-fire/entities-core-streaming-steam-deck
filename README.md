# entities-core-streaming-steam-deck

Setup notes for streaming a handheld gaming PC's screen to the desktop through a capture card, for work and study sessions.

## Use

The handheld docks to a video output that feeds a capture card on the desktop, and a dummy display plug keeps the output alive. The desktop's broadcast software takes the capture card's video and audio and shares it to a voice chat. Its overlay places a synchronised timecode beside the handheld's frame-rate counter, without overlap, on a half-transparent background.

![Overlay](attachments/image1.png)

## Build and run

Nothing here builds. On the desktop, clone the V-Sekai game and engine repositories and pair with the handheld through the vendor's developer kit client.

## Licence

MIT. See `LICENSE`.
