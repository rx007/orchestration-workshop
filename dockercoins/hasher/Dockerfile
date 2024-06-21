FROM ruby:3.3.3-alpine3.20
RUN apk add --update build-base
RUN gem install sinatra
RUN gem install thin
ADD hasher.rb /
CMD ["ruby", "hasher.rb"]
EXPOSE 80
