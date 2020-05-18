# How it's Made
This repo contains the source code to [my website.](https://c-x-berger.github.io/)

I got tired of manually writing HTML, but didn't want to make a Jekyll theme to keep my
precious style intact. So I wrote [my own generator](https://github.com/c-x-berger/blagger)
before realizing GitHub does not in fact offer any mechanism to use anything *but* Jekyll
for a static site generator. (I'm quite certain they could now employ a "get the files
into a magic folder" API with Actions, but that's none of my business.)

To get around this limitation, I write my Markdown source in here, and use a clone of
[`c-x-berger/c-x-berger.github.io`](https://github.com/c-x-berger/c-x-berger.github.io)
as the output directory for `blagger`. Then I can just push the clone and viola - custom
generator.

If you want to recreate this process for yourself, have a look at `blag.sh`.

# Legal Notice
The source code contained within, **and the resulting output on
https://c-x-berger.github.io** is made available under the Creative Commons Attribution
International License, unless otherwise noted.
