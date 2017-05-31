FROM  doublebyte/geonetwork:postgres-3.2.0

COPY wait-for-it.sh /
RUN chmod +x /wait-for-it.sh

CMD ["catalina.sh", "run"]
