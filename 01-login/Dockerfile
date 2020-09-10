FROM gradle:4.2-jdk8

RUN mkdir /usr/local/docker-java-home && cd usr/local/docker-java-home && \
    git clone https://github.com/junaid-mudasir-educative/Auth0-Demo.git

WORKDIR /home/gradle
ADD . /home/gradle

CMD ["gradle", "appRun"]

