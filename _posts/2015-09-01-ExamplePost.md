---
layout:           post
category :        Example # ["category1"] - best is to have one category in a post      
tags :            [] # ["tag1", "tag2", "tag3"] - you can have several post tags
author:           dave
title:            "This is an example title"
tagline:          # This tagline is not in use
date:             2015-09-01T13:04:19+05:45 # XML Schema Date/Time
last_modified_at: 2015-09-01T05:20:00+05:45 # last page modified date/time
excerpt:          "This is an excerpt used for many, many things" # Optional for overriding content excerpt
featured_image:   McKinney_1440x720.jpg
featured_image_caption:   "Photo: Steve Reeves"
featured_image_caption_url: http://www.zenkeep.com
thumbnail_image:  # This image is not in use Thumbnail3.png
trending:         "no"
hidden: 					true


---
{% assign author = site.data.authors[page.author] %}
{% include JB/setup %}
<div class="examplelineonly"></div>
<h2>This is a standalone h2</h2>
<div class="examplelineonly">
	<xmp><h2>This is a standalone h2</h2></xmp>
</div>
<h3>This is a standalone h3</h3>
<div class="examplelineonly">
	<xmp><h3>This is a standalone h3</h3></xmp>
</div>
<h4>This is a standalone h4</h4>
<div class="examplelineonly">
	<xmp><h4>This is a standalone h4</h4></xmp>
</div>
<p>This is a standalone p</p>
<div class="examplelineonly">
	<xmp><p>This is a standalone p</p></xmp>
</div>
<ul>
	<li>This is a standalone li inside of a ul</li>
	<li>This is a standalone li inside of a ul</li>
</ul>
<div class="examplelineonly">
	<xmp><ul>
		<li>This is a standalone li inside of a ul</li>
		<li>This is a standalone li inside of a ul</li>
</ul></xmp>
</div>
<ol>
	<li>This is a standalone li inside of an ol</li>
	<li>This is a standalone li inside of an ol</li>
</ol>
<div class="examplelineonly">
	<xmp><ol>
		<li>This is a standalone li inside of an ol</li>
		<li>This is a standalone li inside of an ol</li>
</ol></xmp>
</div>
<blockquote>This is a standalone blockquote</blockquote>
<div class="examplelineonly">
	<xmp><blockquote>This is a standalone blockquote</blockquote></xmp>
</div>
<blockquote class="pullquote">This is a standalone pullquote</blockquote>
<div class="examplelineonly">
	<xmp><blockquote class="pullquote">This is a standalone pullquote</blockquote></xmp>
</div>
<h2>This is an h2</h2>
<h3 class="h3-after-h2">This is an h3 after an h2</h3>
<div class="examplelineonly">
	<xmp><h2>This is an h2</h2>
<h3 class="h3-after-h2">This is an h3 after an h2</h3></xmp>
</div>
<h3>This is an h3</h3>
<h4 class="h4-after-h3">This is an h4 after an h3.</h4>
<div class="examplelineonly">
	<xmp><h3>This is an h3</h3>
<h4 class="h4-after-h3">This is an h4 after an h3.</h4></xmp>
</div>
<h2>This is an h2</h2>
<h4 class="h4-after-h2">This is an h4 after an h2</h4>
<div class="examplelineonly">
	<xmp><h2>This is an h2</h2>
<h4 class="h4-after-h2">This is an h4 after an h2</h4></xmp>
</div>
<h4>This is an h4</h4>
<h2 class="h2-after-h4">This is an h2 after an h4.</h2>
<div class="examplelineonly">
	<xmp><h4>This is an h4</h4>
<h2 class="h2-after-h4">This is an h2 after an h4.</h2></xmp>
</div>
<h4>This is an h4</h4>
<h3 class="h3-after-h4">This is an h3 after an h4.</h3>
<div class="examplelineonly">
	<xmp><h4>This is an h4</h4>
<h3 class="h3-after-h4">This is an h3 after an h4.</h3></xmp>
</div>
<h3>This is an h3</h3>
<h2 class="h2-after-h3">This is an h2 after an h3.</h2>
<div class="examplelineonly">
	<xmp><h3>This is an h3</h3>
<h2 class="h2-after-h3">This is an h2 after an h3.</h2></xmp>
</div>
<div class="center"><div class="section-divider">...</div></div>
<h2 class="h2-after-section-divider">This is an h2 after a divider then by a p</h2>
<p class="p-after-h2">This is an paragraph after an h2</p>
<div class="examplelineonly">
	<xmp><div class="section-divider">...</div>
<h2 class="h2-after-section-divider">This is an h2 after a divider then by a p</h2>
<p class="p-after-h2">This is an paragraph after an h2</p></xmp>
</div>
<div class="section-divider">...</div>
<h3 class="h3-after-section-divider">This is an h3 after a divider then by a p</h3>
<p class="p-after-h3">This is an paragraph after an h3.</p>
<div class="examplelineonly">
	<xmp><div class="section-divider">...</div>
<h3 class="h3-after-section-divider">This is an h3 after a divider then by a p</h3>
<p class="p-after-h3">This is an paragraph after an h3.</p></xmp>
</div>
<div class="section-divider">...</div>
<h4 class="h4-after-section-divider">This is an h4 after a divider then by a p</h4>
<p class="p-after-h4">This is an paragraph after an h4.</p>
<div class="examplelineonly">
	<xmp><div class="section-divider">...</div>
<h4 class="h4-after-section-divider">This is an h4 after a divider then by a p</h4>
<p class="p-after-h4">This is an paragraph after an h4.</p></xmp>
</div>
<div class="section-divider">...</div>
<p class="p-after-section-divider">This is an paragraph after a divider then by an h2 </p>
<h2 class="h2-after-p">This is an h2 following a p</h2>
<div class="examplelineonly">
	<xmp><div class="section-divider">...</div>
<p class="p-after-section-divider">This is an paragraph after a divider then by an h2 </p>
<h2 class="h2-after-p">This is an h2 following a p</h2></xmp>
</div>
<p>This is an paragraph followed by an h3.</p>
<h3 class="h3-after-p">This is an h3 following a p</h3>
<div class="examplelineonly">
	<xmp><p>This is an paragraph followed by an h3.</p>
<h3 class="h3-after-p">This is an h3 following a p</h3></xmp>
</div>
<p>This is an paragraph followed by an h4.</p>
<h4 class="h4-after-p">This is an h4 following a p</h4>
<div class="examplelineonly">
	<xmp><p>This is an paragraph followed by an h4.</p>
<h4 class="h4-after-p">This is an h4 following a p</h4></xmp>
</div>
<p><span class="dropCap">T</span><span class="dropCapContent">his is an paragraph that starts with a dropcap. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam consectetur ut ipsum non egestas. Quisque cursus odio ut facilisis porttitor. Donec malesuada nec neque pellentesque sodales.</span></p>
<div class="examplelineonly">
	<xmp><p><span class="dropCap">T</span><span class="dropCapContent">his is an paragraph that starts with a dropcap.</span></p></xmp>
</div>
<p>This is a p followed by a blockquote</p>
<blockquote class="quote-after-p">"This is a blockquote, following a p, which is followed by a p"</blockquote>
<p class="quote-before-p">This is a p after a blockquote</p>
<div class="examplelineonly">
<xmp><p>This is a p followed by a blockquote</p>
<blockquote class="quote-after-p">"This is a blockquote, following a p, which is followed by a p"</blockquote>
<p class="quote-before-p">This is a p after a blockquote</p></xmp>
</div>
<h2>This is an h2 followed by a blockquote</h2>
<blockquote class="quote-after-h2">This is a blockquote, following a h2, which is followed by a h2"</blockquote>
<h2 class="quote-before-h2">This is an h2 after a blockquote</h2>
<div class="examplelineonly">
<xmp><h2>This is an h2 followed by a blockquote</h2>
<blockquote class="quote-after-h2">This is a blockquote, following a h2, which is followed by a h2"</blockquote>
<h2 class="quote-before-h2">This is an h2 after a blockquote</h2></xmp>
</div>
<h3>This is an h3 followed by a blockquote</h3>
<blockquote class="quote-after-h3">This is a blockquote, following a h3, which is followed by a h3"</blockquote>
<h3 class="quote-before-h3">This is an h3 after a blockquote</h3>
<div class="examplelineonly">
<xmp><h3>This is an h3 followed by a blockquote</h3>
<blockquote class="quote-after-h3">This is a blockquote, following a h3, which is followed by a h3"</blockquote>
<h3 class="quote-before-h3">This is an h3 after a blockquote</h3></xmp>
</div>
<h4>This is an h4 followed by a blockquote</h4>
<blockquote class="quote-after-h4">This is a blockquote, following a h4, which is followed by a h4"</blockquote>
<h4 class="quote-before-h4">This is an h4 after a blockquote</h4>
<div class="examplelineonly">
<xmp><h4>This is an h4 followed by a blockquote</h4>
<blockquote class="quote-after-h4">This is a blockquote, following a h4, which is followed by a h4"</blockquote>
<h4 class="quote-before-h4">This is an h4 after a blockquote</h4></xmp>
</div>
<h2>This is an h2 followed by an image</h2>
<div class="img-after-h2">
	<a href="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" class="popup-link">
		<img src="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" alt="wallpaper" class="aligncenter size-full" width="100%"/>
	</a>
</div>
<div class="imageCaption">This is an image caption</div>
<div class="examplelineonly">
<xmp><h2>This is an h2 followed by an image</h2>
<div class="img-after-h2">
	<a href="wallpaperno.com_.jpg" class="popup-link">
		<img src="wallpaperno.com_.jpg" alt="3d magic eye wallpaper" class="aligncenter size-full" width="100%"/>
	</a>
</div>
<div class="imageCaption">This is an image caption</div></xmp>
</div>
<h3>This is an h3 followed by an image</h3>
<div class="img-after-h3">
	<a href="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" class="popup-link">
		<img src="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" alt="3d magic eye wallpaper" class="aligncenter size-full" width="100%"/></a>
</div>
<div class="examplelineonly">
<xmp><h3>This is an h3 followed by an image</h3>
<div class="img-after-h3">
	<a href="wallpaperno.com_.jpg" class="popup-link">
		<img src="wallpaperno.com_.jpg" alt="wallpaper" class="aligncenter size-full" width="100%"/></a>
</div></xmp>
</div>
<h4>This is an h4 followed by an image</h4>
<div class="img-after-h4">
	<a href="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" class="popup-link">
		<img src="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" alt="3d magic eye wallpaper" class="aligncenter size-full" width="100%"/>
	</a>
</div>
<div class="examplelineonly">
<xmp><h4>This is an h4 followed by an image</h4>
<div class="img-after-h4">
	<a href="wallpaperno.com_.jpg" class="popup-link">
		<img src="wallpaperno.com_.jpg" alt="wallpaper" class="aligncenter size-full" width="100%"/>
	</a>
</div></xmp>
</div>
<p>This is a p followed by an image</p>
<div class="img-after-p">
	<a href="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" class="popup-link">
		<img src="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" alt="3d magic eye wallpaper" class="aligncenter size-full" width="100%"/>
	</a>
</div>
<div class="examplelineonly">
<xmp><p>This is a p followed by an image</p>
<div class="img-after-p">
	<a href="wallpaperno.com_.jpg" class="popup-link">
		<img src="wallpaperno.com_.jpg" alt="wallpaper" class="aligncenter size-full" width="100%"/>
	</a>
</div></xmp>
</div>
<p>This is a p followed by another p </p>
<p class="p-after-p">This is a p after another p </p>
<div class="examplelineonly">
<xmp><p>This is a p followed by another p </p>
<p class="p-after-p">This is a p after another p </p></xmp>
</div>
<p>This is a p followed by a li (either ul or ol)</p>
<ul class="li-after-p">
	<li>This is a li after a p</li>
	<li>This is a li after a p</li>
</ul>
<div class="examplelineonly">
<xmp><p>This is a p followed by a li (either ul or ol)</p>
<ul class="li-after-p">
	<li>This is a li after a p</li>
	<li>This is a li after a p</li>
</ul></xmp>
</div>
<ol>
	<li>This is a li before a p</li>
	<li>This is a li before a p</li>
</ol>
<p class="p-after-li">This is a p following a li (either ul or ol)</p>
<div class="examplelineonly">
<xmp><ol>
	<li>This is a li before a p</li>
	<li>This is a li before a p</li>
</ol>
<p class="p-after-li">This is a p following a li (either ul or ol)</p></xmp>
</div>
<ol>
	<li>This is a li before an li</li>
	<li>This is a li before an li</li>
</ol>
<ol class="li-after-li">
	<li>This is a li after an li</li>
	<li>This is a li after an li</li>
</ol>
<div class="examplelineonly">
<xmp><ol>
	<li>This is a li before an li</li>
	<li>This is a li before an li</li>
</ol>
<ol class="li-after-li">
	<li>This is a li after an li</li>
	<li>This is a li after an li</li>
</ol></xmp>
</div>
<a href="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" class="popup-link"><img src="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" alt="3d magic eye wallpaper" class="aligncenter size-full wp-image-373" width="100%"/></a>
<p class="p-after-img">This is an image followed by a p</p>
<div class="examplelineonly">
<xmp><a href="wallpaperno.com_.jpg" class="popup-link">
	<img src="wallpaperno.com_.jpg" alt="wallpaper" class="aligncenter size-full" width="100%"/>
</a>
<p class="p-after-img">This is an image followed by a p</p></xmp>
</div>
<a href="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" class="popup-link"><img src="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" alt="3d magic eye wallpaper" class="aligncenter size-full wp-image-373" width="100%"/></a>
<ol class="li-after-img">
	<li>This is a li after an img</li>
	<li>This is a li after an img</li>
</ol>
<div class="examplelineonly">
<xmp><a href="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" class="popup-link"><img src="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" alt="3d magic eye wallpaper" class="aligncenter size-full wp-image-373" width="100%"/></a>
<ol class="li-after-img">
	<li>This is a li after an img</li>
	<li>This is a li after an img</li>
</ol></xmp>
</div>
<a href="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" class="popup-link"><img src="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" alt="3d magic eye wallpaper" class="aligncenter size-full wp-image-373" width="100%"/></a>
<h2 class="h2-after-img">This is an image followed by a h2</h2>
<div class="examplelineonly">
<xmp><a href="wallpaperno.com_.jpg" class="popup-link">
	<img src="wallpaperno.com_.jpg" alt="wallpaper" class="aligncenter size-full" width="100%"/>
</a>
<h2 class="h2-after-img">This is an image followed by a h2</h2></xmp>
</div>
<a href="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" class="popup-link"><img src="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" alt="3d magic eye wallpaper" class="aligncenter size-full" width="100%"/></a>
<h3 class="h3-after-img">This is an image followed by a h3</h3>
<div class="examplelineonly">
<xmp><a href="wallpaperno.com_.jpg" class="popup-link">
	<img src="wallpaperno.com_.jpg" alt="wallpaper" class="aligncenter size-full" width="100%"/>
</a>
<h3 class="h3-after-img">This is an image followed by a h3</h3></xmp>
</div>
<a href="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" class="popup-link"><img src="http://www.zenkeep.com/blog/wp-content/uploads/2015/10/stereogram_magic_eye_1900x1378_2560x1600_wallpaperno.com_.jpg" alt="3d magic eye wallpaper" class="aligncenter size-full" width="100%"/></a>
<h4 class="h4-after-img">This is an image followed by a h4</h4>
<div class="examplelineonly">
<xmp><a href="wallpaperno.com_.jpg" class="popup-link">
	<img src="wallpaperno.com_.jpg" alt="wallpaper" class="aligncenter size-full" width="100%"/>
</a>
<h4 class="h4-after-img">This is an image followed by a h4</h4></xmp>
</div>
{% if author %}
  Written by <a href="{{ author.web }}" target="_blank">{{ author.name }}</a>
{% endif %}
