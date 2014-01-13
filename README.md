JW Box - A JW Player LightBox
==========

JW Box is a small JavaScript LightBox for the JW Player. Is is responsive, and works in Flash and HTML5 environments.

### [Demo](http://www.pluginsbyethan.com/github/lightbox.html)

Implementation:
==========

First, the file lightbox.js needs to be loaded in the page's &lt;head&gt;, like so:

<pre>
&lt;script type=&quot;text/javascript&quot; src=&quot;lightbox.js&quot;&gt;&lt;/script&gt;
</pre>

Then, the LightBox needs to be loaded when the page loads, like so:

<pre>
&lt;body onload=&quot;setupPlayer();&quot;&gt;
</pre>

It can also be loaded like this, if you prefer:

<pre>
&lt;script&gt;
	window.onload = setupPlayer();
&lt;/script&gt;
</pre>

Then, for each link, or graphic, that you want a lightbox to appear when clicked on, you need to add the following call onclick:

<pre>
onclick="playVideo('sample_video.mp4','sample_image.jpg'); return false;"
</pre>

You just need to put in the video you want to play, and the poster image you want to use. If you do not have a poster image, you don't need to list one. 

That's it! 

Sample Implementation:
==========
<pre>
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&lt;head&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;title&gt;JW Lightbox Mobile&lt;/title&gt;
		&lt;link rel=&quot;icon&quot; type=&quot;image/x-icon&quot; href=&quot;http://www.jwplayer.com/wp-content/themes/jwplayer-104/favicon.ico&quot; /&gt;
		&lt;meta http-equiv=&quot;Content-Type&quot; content=&quot;text/html; charset=utf-8&quot; /&gt;
		&lt;script type=&quot;text/javascript&quot; src=&quot;lightbox.js&quot;&gt;&lt;/script&gt;
		&lt;style type=&quot;text/css&quot;&gt;
		body {
			font-family: sans-serif;
		}
		&lt;/style&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&lt;/head&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&lt;body onload=&quot;setupPlayer();&quot;&gt;
		&lt;h3&gt;JW Lightbox Mobile&lt;/h3&gt;
		&lt;a href=&quot;#&quot;&gt;&lt;img width=&quot;500&quot; height=&quot;300&quot; border=&quot;0&quot; src=&quot;http://content.bitsontherun.com/thumbs/i8oQD9zd-480.jpg&quot; onclick=&quot;playVideo('http://content.bitsontherun.com/videos/i8oQD9zd-kNspJqnJ.mp4','http://content.bitsontherun.com/thumbs/i8oQD9zd-480.jpg'); return false;&quot; /&gt;&lt;/a&gt;&lt;br /&gt;&lt;br /&gt;
		&lt;a href=&quot;#&quot;&gt;&lt;img width=&quot;500&quot; height=&quot;300&quot; border=&quot;0&quot; src=&quot;http://www.longtailvideo.com/jw/upload/bunny.jpg&quot; onclick=&quot;playVideo('http://www.longtailvideo.com/jw/upload/bunny.mp4','http://www.longtailvideo.com/jw/upload/bunny.jpg'); return false;&quot; /&gt;&lt;/a&gt;&lt;br /&gt;&lt;br /&gt;
		&lt;a href=&quot;#&quot;&gt;&lt;img width=&quot;500&quot; height=&quot;300&quot; border=&quot;0&quot; src=&quot;http://content.bitsontherun.com/thumbs/3XnJSIm4-480.jpg&quot; onclick=&quot;playVideo('http://content.bitsontherun.com/videos/3XnJSIm4-kNspJqnJ.mp4','http://content.bitsontherun.com/thumbs/3XnJSIm4-480.jpg'); return false;&quot; /&gt;&lt;/a&gt;&lt;br /&gt;&lt;br /&gt;
		&lt;a href=&quot;#&quot;&gt;&lt;img width=&quot;500&quot; height=&quot;300&quot; border=&quot;0&quot; src=&quot;http://content.bitsontherun.com/thumbs/6O7cYVpH-480.jpg&quot; onclick=&quot;playVideo('http://content.bitsontherun.com/videos/6O7cYVpH-1ahmry41.mp4','http://content.bitsontherun.com/thumbs/6O7cYVpH-480.jpg'); return false;&quot; /&gt;&lt;/a&gt;&lt;br /&gt;&lt;br /&gt;
		&lt;a href=&quot;#&quot;&gt;&lt;img width=&quot;500&quot; height=&quot;300&quot; border=&quot;0&quot; src=&quot;http://content.bitsontherun.com/thumbs/zhiesZIW-480.jpg&quot; onclick=&quot;playVideo('http://content.bitsontherun.com/videos/zhiesZIW-52qL9xLP.mp4','http://content.bitsontherun.com/thumbs/zhiesZIW-480.jpg'); return false;&quot; /&gt;&lt;/a&gt;&lt;br /&gt;&lt;br /&gt;
		This is some content.&lt;br /&gt;
		This is some content.&lt;br /&gt;
		This is some content.
&nbsp;&nbsp;&nbsp;&nbsp;&lt;/body&gt;
&lt;/html&gt;
</pre>

The source code is available for this plugin. There is just a .js file for JavaScript. Publishing the JavaScipt can be simply done with any text editor. Enjoy~! :)
