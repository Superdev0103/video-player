# Changelog

All notable changes to this project will be documented in this file.

### v1.0.0 (2022-08-15)

- chore: release v1.0.0

### v1.0.0-beta.4 (2022-08-14)

- fix: video.js types

### v1.0.0-beta.3 (2022-08-07)

- feat: improve `initClassName`

### v1.0.0-beta.2 (2022-08-07)

- feat: `className` will now work from the beginning

### v1.0.0-beta.1 (2022-08-06)

- feat: normalize prop name `playsinline` and `crossorigin`
- fix: prop name confusion `playsInline` > `playsinline`

### v1.0.0-beta.0 (2022-08-06)

- fix: prop `class` type
- fix: player `updateClassNames`
- fix: remove prop `restoreEl` `Element` type

### v0.3.0 (2022-08-05)

- fix: player `dispose` error
- feat: add new event `onUnmounted`

### v0.2.1 (2022-08-05)

- fix: preprocessing of prop `className`

### v0.2.0 (2022-08-05)

- fix: state `playbackRate`
- feat: `state.fullscreen` > `state.isFullscreen`
- feat: add new state `isInPictureInPicture`
- feat: add new state `isLive`
- feat: new prop `disablePictureInPicture`
- feat: new [div ingest](https://videojs.com/guides/embeds/#player-div-ingest) type

### v0.1.0 (2022-07-28)

- feat: full support for the Video.js API
- feat: responsive support for props
- feat: fully customizable control panel
- feat: externally available player states
