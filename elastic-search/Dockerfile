FROM docker.elastic.co/elasticsearch/elasticsearch:8.15.0

# Environment configs (Render uses these if you set them in dashboard)
ENV discovery.type=single-node
ENV ES_JAVA_OPTS="-Xms512m -Xmx512m"
ENV xpack.security.enabled=false

EXPOSE 9200