# Nixie

Nixie is a simple, minimal theme for [Lektor](https://www.getlektor.com/) made for floss blogging. 

# Configuration

### Create configs:

* `configs/atom.ini`:

    [blog]
    name = <BLOG NAME>
    source_path = /
    url_path = /atom.xml
    items = site.query('/')
    item_model = blog-post
    
* `configs/`

### Configure `.lektorproject` file:

    [theme_settings]
    name = super cool blog for cool people only
    links = about,support # links in header to static pages
    googleanalytics = UA-xxxxxx-x
    gitlab_id = granitosaurus
    github_id = granitosaurus
    mastodon = mastodon.technology/@wraptile
    diaspora = diasp.org/u/tinarg
    email = granitosaurus@pm.me
    stackoverflow_id = 3737009

    [project]
    name = 🕷 crawl.blog
    url = http://crawl.blog
    themes = lektor-theme-nixie
    upstream = gitlab.com/granitosaurus/crawl.blog
    author = Bernardas Ališauskas
    description = blog focused on web crawling, scraping and automation

    [packages]
    lektor-tags = 0.3
    lektor-atom = 0.3
    lektor-shortcodes = 0.2.5

### Static files:

Create some static images that are used in <meta> tags and favicon at `/assets/static/`
    
    favicon.png - favicon name
    image.svg - default for <meta> images 

# Writing blogs

See example blog: TODO

## License

Nix is licensed under the [MIT License](LICENSE.md)
