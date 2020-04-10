# Browser Based Stream Selection 
  
Demonstration code to select a video manifest based on the browser detected locally.  The test manifests represent different codecs.  As browsers have varying codec support capabilites, the goal is to select the codec that is most bandwidth efficient for a given browser.  There is an underlying mapping to browsers to codecs based on April 2020 research (which is not shown here).

This based on an exisitng Bitmovin Demo at https://github.com/bitmovin/bitmovin-player-web-samples/blob/master/vue/vuejs.html and https://github.com/lancedikson/bowser

As documented at https://bitmovin.com/docs/player/tutorials/get-started-with-the-bitmovin-player, the index.html requires that it be served via http from localhost (e.g. npm install serve).
