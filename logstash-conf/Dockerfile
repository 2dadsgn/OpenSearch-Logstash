#created 16/11/2022 by 2da.dsgn@gmail.com


FROM opensearchproject/logstash-oss-with-opensearch-output-plugin:8.4.0
RUN rm -f /usr/share/logstash/pipeline/logstash.conf
ADD pipeline/ /usr/share/logstash/pipeline/
ADD pipeline/ /usr/share/logstash/config/
ENTRYPOINT ["/usr/share/logstash/bin/logstash"]

