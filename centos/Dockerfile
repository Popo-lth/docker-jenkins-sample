FROM centos:latest
MAINTAINER James Turnbull "james@example.com"
ENV REFRESHED_AT 2014-07-27
RUN yum -y install ruby rubygems rubygem-rake
RUN gem sources --remove https://rubygems.org/ ; gem sources -a http://ruby.taobao.org/
RUN gem install --no-rdoc --no-ri rspec ci_reporter_rspec
