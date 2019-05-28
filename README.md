React components for Video.js

## Installation

yarn add @makhataibar/react-video.js

## Usage

```
import VideoPlayer from '@makhataibar/react-video.js'

const videoJsOptions = {
  autoplay: true,
  
  controls: true,
  sources: [{
    src: '/path/to/video.mp4',
    type: 'video/mp4'
  }]
}

return <VideoPlayer { ...videoJsOptions } />
```