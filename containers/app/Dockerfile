FROM ruby:alpine

ENV BUNDLE_PATH /bundle

RUN apk add --update --no-cache \
      # for nio4r
      build-base \
      # for nokogiri
      linux-headers \
      # for pg
      postgresql-dev \
      # for activesupport
      tzdata

WORKDIR /work/app
