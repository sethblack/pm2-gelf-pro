# pm2-gelf-pro
pm2 module for logging to graylog

# Installation

```sh
pm2 install pm2-gelf-pro
```

# Configuration

I've added some basic gelf-pro settings.

```sh
$> pm2 set pm2-gelf-pro:graylogHost graylog.myserver.org
$> pm2 set pm2-gelf-pro:graylogPort 12201
$> pm2 set pm2-gelf-pro:graylogFields '{"app": "test"}'
```
