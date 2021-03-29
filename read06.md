HTML5: 
to adding the audio file to my html file I have to use this code :
<audio controls autoplay>
 <source src="audio/test-audio.ogg" />
 <source src="audio/test-audio.mp3" />
 <p>This browser does not support our audio
 format.</p>
 </audio>
 also we can add FLASH, VIdio:
 we can add the fash by adding this codes :
 var flashvars = {};
 var params = {movie: "../video/puppy.flv"};
 swfobject.embedSWF("flash/osplayer.swf", "snow",
 "400", "320", "8.0.0", flashvars, params);</script>
and add the vidio by this code :
<video poster="images/puppy.jpg" width="400"
 height="320" controls="controls">
 <source src="video/puppy.mp4" type='video/mp4;
 codecs="avc1.42E01E, mp4a.40.2"' />
 <source src="video/puppy.webm" type='video/webm;
 codecs="vp8, vorbis"' />
 <div id="snow">
 <p>You cannot see this video of a puppy playing
 in the snow because this browser does not
 support our video formats.</p>
 </div>
 </video> for exampel .
 Browsers that support the HTML5 elements do not
all support the same video and audio formats, so you
need to supply your files in different formats to ensure
that everyone can see/hear them.

css :
 CSS treats each HTML element as if it appears inside
its own box,CSS rules usually appear in a separate document,
although they may appear within an HTML page

 
