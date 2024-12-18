FROM grafana/grafana:11.4.0
 
COPY --chown=grafana:root grafana.db /var/lib/grafana/grafana.db
RUN chmod 640 /var/lib/grafana/grafana.db