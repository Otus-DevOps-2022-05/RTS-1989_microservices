FROM ruby:2.2-alpine

#RUN apk --no-cache --update add build-base && \
#    bundle install && \
#    apk del build-base

ENV APP_HOME /app
RUN mkdir $APP_HOME
WORKDIR $APP_HOME
ADD Gemfile* $APP_HOME/
ADD . $APP_HOME

RUN apk --no-cache --update add build-base && \
    bundle install && \
    apk del build-base

ENV COMMENT_DATABASE_HOST comment_db
ENV COMMENT_DATABASE comments

CMD ["puma"]
