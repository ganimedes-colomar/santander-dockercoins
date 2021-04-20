FROM ruby
RUN gem install sinatra && gem install thin
COPY hasher.rb .

ENTRYPOINT ["ruby"]
CMD ["hasher.rb"]
