FROM fluent/fluentd-kubernetes-daemonset:v1.14.5-debian-elasticsearch7-1.1

RUN gem install fluent-plugin-detect-exceptions -v 0.0.14 \
 && gem sources --clear-all \
 && rm -rf /var/lib/apt/lists/* \
           /home/fluent/.gem/ruby/2.7.0/cache/*.gem
