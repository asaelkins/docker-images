FROM sebp/elkx:latest
LABEL org.freenas.interactive="false" \
      org.freenas.version="1.0.6" \
      org.freenas.upgradeable="true" \
      org.freenas.expose-ports-at-host="true" \
      org.freenas.autostart="true" \
      org.freenas.web-ui-protocol="http" \
      org.freenas.web-ui-port="5601" \
      org.freenas.web-ui-path="" \
      org.freenas.port-mappings="5601:5601/tcp,9200:9200/tcp,5044:5044/tcp" \
      org.freenas.volumes="[                          \
          {                                           \
              \"name\": \"/var/lib/elasticsearch\",   \
              \"descr\": \"ES data\"                  \
          },                                          \
          {                                           \
              \"name\": \"/opt/kibana/config\",       \
              \"descr\": \"Kibana config data\"       \
          },                                          \
          {                                           \
              \"name\": \"/etc/logstash/conf.d\",     \
              \"descr\": \"logstash config\"          \
          }                                           \
      ]" \
      
