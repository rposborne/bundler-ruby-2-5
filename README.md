# Bundler :(

```
Sending build context to Docker daemon  53.25kB
Step 1/5 : FROM ruby:2.5.0
 ---> 4c7885e3f2bb
Step 2/5 : RUN mkdir /app
 ---> Using cache
 ---> f8e40b3b2677
Step 3/5 : WORKDIR /app
 ---> Using cache
 ---> ef943c746811
Step 4/5 : COPY Gemfile Gemfile.lock /app/
 ---> e970750de1d5
Step 5/5 : RUN bundle install
 ---> Running in 5552bba02160
Fetching https://github.com/plataformatec/devise.git
/usr/local/lib/ruby/gems/2.5.0/gems/bundler-1.16.1/lib/bundler/vendor/thor/lib/thor/shell/basic.rb:88:in `=~': invalid byte sequence in US-ASCII (ArgumentError)
	from /usr/local/lib/ruby/gems/2.5.0/gems/bundler-1.16.1/lib/bundler/vendor/thor/lib/thor/shell/basic.rb:88:in `!~'
	from /usr/local/lib/ruby/gems/2.5.0/gems/bundler-1.16.1/lib/bundler/vendor/thor/lib/thor/shell/basic.rb:88:in `say'
	from /usr/local/lib/ruby/gems/2.5.0/gems/bundler-1.16.1/lib/bundler/ui/shell.rb:105:in `tell_me'
	from /usr/local/lib/ruby/gems/2.5.0/gems/bundler-1.16.1/lib/bundler/ui/shell.rb:45:in `error'
	from /usr/local/lib/ruby/gems/2.5.0/gems/bundler-1.16.1/lib/bundler/friendly_errors.rb:17:in `log_error'
	from /usr/local/lib/ruby/gems/2.5.0/gems/bundler-1.16.1/lib/bundler/friendly_errors.rb:126:in `rescue in with_friendly_errors'
	from /usr/local/lib/ruby/gems/2.5.0/gems/bundler-1.16.1/lib/bundler/friendly_errors.rb:121:in `with_friendly_errors'
	from /usr/local/lib/ruby/gems/2.5.0/gems/bundler-1.16.1/exe/bundle:22:in `<top (required)>'
	from /usr/local/bin/bundle:23:in `load'
	from /usr/local/bin/bundle:23:in `<main>'
The command '/bin/sh -c bundle install' returned a non-zero code: 1
```
