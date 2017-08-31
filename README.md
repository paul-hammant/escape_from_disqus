# A python script to process your exported Disqus XML dump, and make JSON/HTML snippets

Why did I do this? Well I setup my Disqus incorrectly many years ago, and article titles were a bit non-standard. 
I only worked that a month ago. I tried to seek help through the Disqus support system (a forum), but didn't get
what I was looking for. See [here](https://disqus.com/home/channel/discussdisqus/discussion/channel-discussdisqus/installation_changed_from_http_to_https_and_comments_are_not_attached_to_the_page_anymore/) 
and [here](https://disqus.com/home/channel/discussdisqus/discussion/channel-discussdisqus/installation_getting_comments_back_after_http_https_switch_is_hard/). There was a help document [elsewhere](https://woorkup.com/migrate-disqus-comments-https/) but it was out of date.

So bye bye Disqus. Hello Twitter for comments (that I will try to work out how to bring back to the page later)

And the Python script?  Run it in Python3 - no args - it's going to create a `disqusoutput/` folder.

Oh, and: 

```
sudo pip3 install python-dateutil
sudo pip3 install sh
```

