FROM ruby
MAINTAINER silvade <steve.desilva@gmail.com>
EXPOSE 4567
ENTRYPOINT ["bundle","exec","rackup","-p","4567","--host","0.0.0.0"]
ONBUILD ADD . /
ONBUILD RUN bundle install
