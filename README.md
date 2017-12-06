# pelican-uno

A responsive, minimal theme with beaitufil fonts for [Pelican](http://docs.getpelican.com/en/stable/) static website generator (Python).
This theme is based on [uno](https://github.com/daleanthony/Uno) for [Ghost](https://ghost.org) environment. 
If you don't use python/Pelican but want to use uno theme, you might find following implementations useful:
* [hugo-uno](https://github.com/fredrikloch/hugo-uno) ... using [Go](https://golang.org) under [Hugo](https://gohugo.io) environment
* [jekyll-uno](https://github.com/joshgerdes/jekyll-uno) ... using [Ruby](https://www.ruby-lang.org/en/) under [Jekyll](https://jekyllrb.com)

The codes in this repository are taken from results running [jekyll-uno](https://github.com/joshgerdes/jekyll-uno).
I am not an expert of Pelican. In fact this is made on my day 2. Please help correcting mistakes and stupidities!

---

### Install and Test

0. If unfamiliar with Pelican, follow the [Quick Start](http://docs.getpelican.com/en/stable/quickstart.html#).
1. In pelicanconf.py add this line: 
`SCRIPTS = ['https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js','main.js']`
2. Generate your website: `make html` or `make devserver`

If you run `devserver` you can access via: [http://localhost:8000](http://localhost:8000)

---

### Demo and Download

Not a clean demo but this theme is used for [our website](https://www.deeplearnphysics.org).

---

### Copyright and license

It is under [the MIT license](/LICENSE).
