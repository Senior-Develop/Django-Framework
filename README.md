Wagtail is an open source content management system built on Django, with a strong community and commercial support. It's focused on user experience, and offers precise control for designers and developers.

![Wagtail screenshot](https://cdn.jsdelivr.net/gh/wagtail/wagtail@main/.github/wagtail-screenshot-with-browser.png)

### Features

* A fast, attractive interface for authors
* Complete control over front-end design and structure
* Scales to millions of pages and thousands of editors
* Fast out of the box, cache-friendly when you need it
* Content API for 'headless' sites with de-coupled front-end
* Runs on a Raspberry Pi or a multi-datacenter cloud platform 
* StreamField encourages flexible content without compromising structure
* Powerful, integrated search, using Elasticsearch or PostgreSQL
* Excellent support for images and embedded content
* Multi-site and multi-language ready
* Embraces and extends Django

To get started with Wagtail, run the following in a virtual environment:

``` bash
pip install wagtail
wagtail start mysite
cd mysite
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```


