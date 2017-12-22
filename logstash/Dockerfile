FROM logstash:5

RUN logstash-plugin install logstash-filter-de_dot

COPY logstash/logstash.conf /etc/logstash/conf.d/

CMD ["-f", "/etc/logstash/conf.d/logstash.conf"]