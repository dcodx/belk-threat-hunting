FROM docker.elastic.co/kibana/kibana:7.4.0
USER kibana
RUN bin/kibana-plugin install https://github.com/bitsensor/elastalert-kibana-plugin/releases/download/1.1.0/elastalert-kibana-plugin-1.1.0-7.4.0.zip
ADD kibana.yml /usr/share/kibana/config/kibana.yml

CMD ["/usr/local/bin/kibana-docker"]

