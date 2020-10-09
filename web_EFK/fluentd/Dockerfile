FROM fluent/fluentd:v1.11.1-debian-1.0
USER root
RUN gem install fluent-plugin-elasticsearch --version 4.1.1
USER fluent
# RUN ["fluent", "gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri", "--version", "4.1.1"]
# RUN ["gem", "uninstall", "faraday"]
# RUN ["gem", "install", "faraday", "--version", "0.17.0"]