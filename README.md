# media-offset

Configures a media element to lock playback to a defined segment of the media.
The user will not be able to seek to the outside parts of the video.

## Usage

This video will autoplay muted and loop through the segment from 5s to 8s.

```html
  <script type="module" src="https://cdn.jsdelivr.net/npm/media-offset"></script>
  <video
    data-offset="5 8"
    src="https://stream.mux.com/O6LdRc0112FEJXH00bGsN9Q31yu5EIVHTgjTKRkKtEq1k/low.mp4"
    muted
    autoplay
    loop
  ></video>
```

## Related

- [Media Chrome](https://github.com/muxinc/media-chrome) Your media player's dancing suit. 🕺
- [`<media-playlist>`](https://github.com/muxinc/media-playlist) A custom element for playing through a set of audio and/or video elements.
- [`media-group`](https://github.com/muxinc/media-group) Sync and control multiple audio and/or video elements.
- [`<hls-video>`](https://github.com/muxinc/hls-video-element) A web component for playing HTTP Live Streaming (HLS) videos.
- [`<youtube-video>`](https://github.com/muxinc/youtube-video-element) A web component for the YouTube player.
- [`<vimeo-video>`](https://github.com/luwes/vimeo-video-element) A web component for the Vimeo player.
- [`castable-video`](https://github.com/muxinc/castable-video) Cast your video element to the big screen with ease!
- [`<mux-player>`](https://github.com/muxinc/elements/tree/main/packages/mux-player) The official Mux-flavored video player web component.
- [`<mux-video>`](https://github.com/muxinc/elements/tree/main/packages/mux-video) A Mux-flavored HTML5 video element w/ hls.js and Mux data builtin.
