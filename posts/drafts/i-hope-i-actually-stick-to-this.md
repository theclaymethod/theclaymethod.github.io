---
title: 'I Hope I Actually Stick to This'
date: '2014-05-03'
description: 'A Welcome Post'
tags: ['blog', 'ramblings', 'agency', 'moving', 'San Francisco']
---

The New American Dream

I’ve left the glitz and glam (read: traffic and more traffic) of Los Angeles ad agency world for the San Francisco tech scene. It seems that rental prices are just the thing to complain about in SF, much like what traffic is in LA. I wonder if brunch has the same appeal here.

<img src="http://i.imgur.com/fxqvX.gif"><br>
<i>For Reference, this is a time-lapse of my commute in LA.</i>

Over the coming weeks, I will be chronicling my transition from Agency to Startup: media buying to media platform. The demands will definitely be different. No more clients, just customers. 

The first ordeal was really the housing search. I won’t go into the details, since <a href="http://techcrunch.com/2014/04/14/sf-housing/">TechCrunch</a> did such a great job setting the scene. All I can say is that it really is a pain to find good housing here, especially when you like nice things. 

Moving along, now we are at setting up this blog. I've installed Ruhoh using the instructions <a href="http://ruhoh.com/docs/2/">here</a>. My girlfriend insisted that I use a SquareSpace account or something just to get my writing up, but I didn't become a developer just to do things the easy way and automate everything (don't think about it). 

The instructions were easy enough to follow. My only gripe is that I wish the templating language was something closer to Django's, but I think I remember some Ruby from college. 
<pre class="prettyprint bash-html">
	git clone git@github.com:theclaymethod/theclaymethod.github.io.git
	#Obviously change "theClaymethod" to your own username, unless you want to mirror my blog. 
	#That would be cool too
	cd theclaymethod.github.io
	touch Gemfile
	echo "source \"https://rubygems.org\"" >> Gemfile
	echo "gem 'ruhoh', \"~> 2\"" >> Gemfile
	bundle install
	bundle exec ruhoh server 9292
	git clone https://github.com/ruhoh/theme-bootstrap-2.git theme-bootstrap-2
</pre>

This is pretty much about as far as I got. I will probably force myself to fiddle with the CSS and styling in the coming weeks, but Vanilla Bootstrap it is for now. There's some minor configuration stuff you have to do, but for that I'd say just read the <a href="http://ruhoh.com/docs/2/">docs</a>. 