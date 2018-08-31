# pm2-gelf-pro
pm2 module for logging to graylog

# Installation

# Configuration

```sh
$> pm2 set pm2-gelf-pro:graylogHost graylog.myserver.org
$> pm2 set pm2-gelf-pro:graylogPort 12201
$> pm2 set pm2-gelf-pro:graylogFields '{"app": "test"}'
```