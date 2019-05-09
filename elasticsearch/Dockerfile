FROM docker.elastic.co/elasticsearch/elasticsearch:7.0.1@sha256:ab3884396356595a665b88fbf61d4f0c1c39eb8891c77b1b72d5fe83ae3a1c75
COPY --chown=elasticsearch:elasticsearch elasticsearch.yml /usr/share/elasticsearch/config/

CMD ["elasticsearch", "-Elogger.level=INFO"]
