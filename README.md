Flocking Video Cam!
===================


#### Getting pixel x, y points from the video

in index.html, there is jquery script where you can use .offset to manipulate the positions for x,y.

```jquery
var offset = $('me').offset()
    $('#me').offset({top: offset.top +400, left: offset.left + 100}) //move in relation to previous one
 // $('#me').offset({top: 10, left: 30}) //move without considering previous offset

```
