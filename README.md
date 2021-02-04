# embed_video_from_youtube
This script is needed in order to embed videos from YouTube and not waste time loading the iframe at the time the page loads. Iframe initialization occurs at the moment of clicking on the video block.

## Install
```
<link rel="stylesheet" href="/css/embedVideo.css">
<script src="/js/embedVideo.js"></script>
```

## Usage example
Create and style the block where you want to place the video. In the "data-video" attribute, specify the id of the desired video.
```
<div class="frame" data-video="6zTc2hD2npA"></div>
```
Call the "embedVideo()" function with the video block class as an argument.
```
embedVideo('.frame');
```
As a result of the function, a preview of your video will be placed in the block, and the iframe will be initialized when you click on the block.
