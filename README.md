# xinmingcreative.github.io
This is the source of Xinming Creative Enterprise official Website.

## Requirements
> Jekyll 3.x

# Install Jekyll on Ubuntu 16.04
~~~
$ sudo apt-get update
$ sudo apt-get install ruby ruby-dev make gcc
$ sudo gem install jekyll bundler
~~~

see [source](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-jekyll-development-site-on-ubuntu-16-04)

## How to Start Jekyll
~~~
$ jekyll new myblog
$ cd myblog
~~~

Run
~~~
$ bundle exec jekyll serve
~~~

or simply
~~~
$ jekyll serve
~~~

with reload and refresh every file changes
~~~
$ jekyll serve -w
~~~

Start Jekyll locally same like Github page environment
~~~
$ jekyll serve --safe
~~~

Now browse to http://localhost:4000


## Reference
- [How to create github page](https://pages.github.com/)
- [Agency Jekyll Theme](http://y7kim.github.io/agency-jekyll-theme/)
- [Support Multiple Languages](https://github.com/Anthony-Gaudino/jekyll-multiple-languages-plugin)
