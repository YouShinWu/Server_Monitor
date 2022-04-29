# Server mointer system

## Influxdb and Telegraf and Grafana

### Install 
- grafana/grafana:8.1.5 : query data from influxdb
- influxdb:2.2.0 : Save data
- telegraf : collect data and send to influxdb 

#
### Influxdb
- https://github.com/docker-library/docs/blob/master/influxdb/README.md
- Using port 8086 as default web ui port


### Telegraf
- Use this command to deal woith docker.sock permission denied
    ```
    sudo usermod -a -G docker $USER
    // sudo usermod -a -G docker mmlab
    ```
    - Use your login user name in $USER
<!-- - Use nodejs to query data (Can use another API) -->
<!-- https://github.com/influxdata/influxdb-client-js -->
