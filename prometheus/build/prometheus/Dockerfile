FROM prom/prometheus:0.16.1
MAINTAINER Aaron Crickenberger <spiffxp@gmail.com>

RUN apk add --update ruby ruby-json

COPY ./run.sh /prometheus/run.sh
COPY ./run.rb /prometheus/run.rb

ENTRYPOINT ["/usr/bin/ruby", "/prometheus/run.rb"]
CMD []
