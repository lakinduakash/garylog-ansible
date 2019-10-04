# Graylog Ansible with Filebeat

This ansible module automates the deployment of graylog server with elasticsearch and filebeats. Filebeats agents are installed to nodes which have logs to collect. After that logs can be analysed with graylog ui.

### Archtecture Overview

![architecture](docs/arc.jpg)

### Configuring ansible inventory