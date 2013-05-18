GDB
===

Introduction
------------

This is an attempt to leverage Google Drive as a blogging platform driven by a published Google Drive Spreadsheet.

It's online [here](https://googledrive.com/host/0ByRgQIhodQXfaVdHOElsZTV5c3c/driveblog/) and uses a [Google Spreadsheet](https://docs.google.com/spreadsheet/ccc?key=0AiRgQIhodQXfdGZ5OV9INlNRME9YUnc2VUhmRGtPaVE&usp=sharing) as its data source for posts and comments (different sheets).

I base64 encode the posts because I wasn't sure how a spreadsheet would cope with HTML text. Perhaps I should be braver, but there you go.

At present it contains a few posts about HTML that I wrote for one of my sons.

The Future
----------

I'd like to figure out a way of posting just using JavaScript as nearly all my work at present is JavaScript based and I think that that would be a more elegant approach. I'd also like to be able to figure out a mechanism for adding comments and an RSS feed etc...

If you can think of a use for it then feel free to play with it. It uses [BootStrap](http://twitter.github.io/bootstrap/) for the layout and [jQuery](http://jquery.com/) for the heavy lifting