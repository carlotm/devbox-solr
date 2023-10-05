# Devbox plugin to run Solr

A devbox plugin to run [apache solr](https://solr.apache.org/).

This plugin sets the following environment variables:

- `SOLR_LOGS_DIR`=/path/of/my/project/.devbox/virtenv/carlotm-devbox-solr/logs
- `SOLR_PID_DIR`=/path/of/my/project/.devbox/virtenv/carlotm-devbox-solr/pid

Services:
- solr

Use `devbox services start|stop [service]` to interact with services
