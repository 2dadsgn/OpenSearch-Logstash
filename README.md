#This docker compose has been developed in order to build a network containing the OpenSearch stack and the logstash endpoint.
#The logstash container is the middle man between the source and the OSS (OpenSearch stack), it receives the HTTP post arriving from Chirpstack
#and it forwards this data to OpenSearch through the OSS plugin.

#It's fully configurable through the pipeline.conf file in the logstash-conf folder.

#Security plugin in OSS is enabled.
