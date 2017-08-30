jekyll-hinduarabic [![Gem Version](https://badge.fury.io/rb/jekyll-hinduarabic.svg)](https://badge.fury.io/rb/jekyll-hinduarabic)
============

This is a Liquid filter for Jekyll which converts English numerals to the corresponding [Hindu-Arabic](http://en.wikipedia.org/wiki/Hindu%E2%80%93Arabic_numeral_system) form. Currently Jekyll provides no way to produce these form of numbers i.e. ۱۲۳۴۵۶۷۸۹۰ instead of 1234567890.

# Installation

Append `gem jekyll-hinduarabic` to the `plugins` vector (formerly know as _gems_) of your website's __config.yml_ file. You can also put the _jekyll-hinduarabic.rb_ file inside _plugins_ directory of your website. You can install it from Rubygems too:

    gem install jekyll-hinduarabic

# Usage
Use it as a _Liquid_ filter inside any Jekyll template:

    {% page.date | habify %}

# License
MIT