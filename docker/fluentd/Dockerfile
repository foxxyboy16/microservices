FROM fluent/fluentd:v0.12
RUN gem install fluent-plugin-elasticsearch --no-document --version 1.9.5
RUN gem install fluent-plugin-grok-parser --no-document --version 1.0.0
ADD fluent.conf /fluentd/etc
