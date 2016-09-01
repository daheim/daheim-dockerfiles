FROM kibana:latest

RUN cd /opt/kibana && \
    bin/kibana plugin --install elasticsearch/marvel/latest && \
    chown -R kibana:kibana /opt/kibana
