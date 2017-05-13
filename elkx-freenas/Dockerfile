FROM sebp/elkx
LABEL org.freenas.interactive="false" 		\
      org.freenas.version="1.0.007"		  \
      org.freenas.upgradeable="true"		  \
      org.freenas.expose-ports-at-host="true"	\
      org.freenas.autostart="true"		    \
      org.freenas.capabilities-add="NET_BROADCAST" \
      org.freenas.web-ui-protocol="http"	\
      org.freenas.web-ui-port=5601		    \
      org.freenas.port-mappings="5601:5601/tcp,5000:5000/tcp,514:514/tcp,9200:9200/tcp,5001:5001/tcp,5002:5002/tcp,5002:5002/udp,514:514/udp"			\
      org.freenas.volumes="[                    \
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
      ]"
