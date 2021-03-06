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

## Build Github with Travis-CI
1. Sign up [Travis-CI](https://travis-ci.org).
2. Enable Travis-CI services in repo settings by enter:
 - Travis-CI username
 - Token from Travis CI
3. Add _Gemfile_ and _.travis.yml_ at root repo.
4. Done.

The build will auto trigger on every git push.

see https://help.github.com/articles/viewing-jekyll-build-error-messages/


## Reference
- [How to create github page](https://pages.github.com/)
- [Agency Jekyll Theme](http://y7kim.github.io/agency-jekyll-theme/)
- [Support Multiple Languages](https://github.com/Anthony-Gaudino/jekyll-multiple-languages-plugin)
