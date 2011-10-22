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

License
-------
[WTFPL](http://sam.zoy.org/wtfpl/COPYING)

