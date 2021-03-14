## The <video> element allows you to embed a video very easily. A really simple example looks like this:
  
  * src :In the same way as for the <img> element, the src (source) attribute 
 contains a path to the video you want to embed. It works in exactly the same way.
 
 * control :Users must be able to control video and audio playback You must either 
 use the controls attribute to include the browser's own control interface, 
 or build your interface using the appropriate JavaScript API. At a minimum, 
 the interface must include a way to start and stop the media, and to adjust the volume.
 
 * autoplay:This Boolean attribute if specified, the video will automatically begin 
 to play back as soon as it can do so without stopping to finish loading the data.
 
 * autobuffer:This Boolean attribute if specified, the video will 
 automatically begin buffering even if it's not set to automatically play.
 
 * controls:If this attribute is present, it will allow the user to 
 control video playback, including volume, seeking, and pause/resume playback.
 
 * height:This attribute specifies the height of the video's display area, in CSS pixels.
 
 * loop:This Boolean attribute if specified, will allow video automatically 
 seek back to the start after reaching at the end.
 
 * preload:This attribute specifies that the video will be loaded at 
 page load, and ready to run. Ignored if autoplay is present.
