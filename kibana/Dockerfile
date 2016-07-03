FROM kibana:latest

RUN kibana plugin --install elastic/sense
COPY ./config /opt/kibana/config

CMD kibana
