FROM centos:7

RUN mkdir -p /opt/BESClient/bin

ENV QNA_VERSION 9.2.5.130

ADD qna /opt/BESClient/bin/qna
ADD libBEScrypto.so /opt/BESClient/bin/libBEScrypto.so

CMD ["/opt/BESClient/bin/qna"]
