FROM jfcantu/elastalert:v0.1.1

LABEL maintainer="Daichi Kimura <daichi703n@gmail.com>"
ENV TZ Etc/UTC

COPY elastalert.py /opt/elastalert/elastalert/elastalert.py
COPY loaders.py /opt/elastalert/elastalert/loaders.py
COPY test_rule.py /opt/elastalert/elastalert/test_rule.py

WORKDIR /opt/elastalert-server

ENTRYPOINT ["npm", "start"]
