FROM google/dart
RUN curl -sSfL -o dart-sass.tar.gz https://github.com/sass/dart-sass/releases/download/1.32.11/dart-sass-1.32.11-linux-x64.tar.gz && \
    tar zxvf dart-sass.tar.gz
ENTRYPOINT ["/dart-sass/sass"]

