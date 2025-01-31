# Devbox plugin to run Solr

[![Test the debox solr plugin](https://github.com/carlotm/devbox-solr/actions/workflows/ci.yml/badge.svg)](https://github.com/carlotm/devbox-solr/actions/workflows/ci.yml)

A devbox plugin to run [apache solr](https://solr.apache.org/).

This plugin sets the following environment variables:

- `SOLR_LOGS_DIR` `${DEVBOX_PROJECT_ROOT}/.devbox/virtenv/carlotm.devbox-solr.solr/logs`
- `SOLR_PID_DIR` `${DEVBOX_PROJECT_ROOT}/.devbox/virtenv/carlotm.devbox-solr.solr/pid`
- `SOLR_HOME` `${DEVBOX_PROJECT_ROOT}/.devbox/virtenv/carlotm.devbox-solr.solr/data`
- `SOLR_PORT` `8983`
- `SOLR_ENV` `dev,label=MyDev,color=blue`

Services:
- solr

Use `devbox services start|stop [service]` to interact with services
