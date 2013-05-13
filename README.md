Mustache-RSS-Template
=====================
Mustache templates for RSS 2.0 and Atom feeds.

[View the project on Github](https://github.com/ajacksified/Mustache-RSS-Templates)

[View the documentation](http://ajacksified.github.com/Mustache-RSS-Templates/)

Expected Input
--------------
Here's what the template expects:

    {
      Feed: { 
        Title: "Derp News",
        Subtitle: "All the news you need to Herp",
        Link: "http://blog.derpinc.com",
        Language: "en",
        CopyrightInfo: "Copyright 2011 Derp Inc.",
        PubDate: "Thu, 20 Oct 2011 20:38:06 PST",
        LastBuildDate: "Thu, 20 Oct 2011 20:38:03 PST",
        
        Items: [
          {
            Title: "2nd Post",
            Content: "This is my blog content, or maybe just a snippet. Whatevs",
            Summary: "This is my second post.",
            Link: "http://blog.derpinc.com/2nd-post",
            PubDate: "Thu, 20 Oct 2011 20:35:15 PST"
          },
          {
            Title: "1st Post",
            Content: "This is my blog content, or maybe just a snippet. Whatevs",
            Summary: "This is my first post.",
            Link: "http://blog.derpinc.com/1st-post",
            PubDate: "Tue, 18 Oct 2011 19:38:03 PST"
          }
        ]
      }
    }

Subtitle is optional. If an atom feed, date should be 
[RFC-3339](http://www.ietf.org/rfc/rfc3339.txt). If an rss 2.0 feed, date 
should be [RFC-882](http://www.ietf.org/rfc/rfc0822.txt). Feed tested as valid
with the [W3C Feed Validation Service](http://validator.w3.org/feed/). 

License
-------

Copyright (c) 2013 Jack Lawson. MIT Licensed. See LICENSE.md file for details.

