# Roku
Documents and notes on using Roku's Direct Publisher platform

There's nothing particularly difficult about using Direct Publisher, it's extremely simple once you work
out the quirks in their documentation. My biggest issue was figuring out which of the objects in their
JSON documentation were actually required and which weren't - some are marked as required but aren't,
others are marked as optional but you won't have a functioning channel without them.

I wanted to set up a simple channel that shows the live stream from Cloudflare.tv. If you're looking
to set up video libraries of movie and TV content, this may not be quite as useful to you.

The JSON configuration file I'm using is in this repository. You should be able to use it as a template
for your own live channel. 
