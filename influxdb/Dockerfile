FROM influxdb:2.2.0


ENV DOCKER_INFLUXDB_INIT_MODE=setup
ENV DOCKER_INFLUXDB_INIT_USERNAME=YouShin
ENV DOCKER_INFLUXDB_INIT_PASSWORD=M11007317
ENV DOCKER_INFLUXDB_INIT_ORG=MMLAB
ENV DOCKER_INFLUXDB_INIT_BUCKET=docker174
ENV DOCKER_INFLUXDB_INIT_RETENTION=1w
ENV DOCKER_INFLUXDB_INIT_ADMIN_TOKEN=my-influxdb-token



# RUN wget -qO- https://repos.influxdata.com/influxdb.key | tee /etc/apt/trusted.gpg.d/influxdb.asc >/dev/null
# RUN source /etc/os-release
# RUN echo "deb https://repos.influxdata.com/${ID} ${VERSION_CODENAME} stable" | tee /etc/apt/sources.list.d/influxdb.list
# RUN apt-get install telegraf


# RUN curl -sL https://deb.nodesource.com/setup_14.x -o setup_14.sh
# RUN chmod +x ./setup_14.sh 
# RUN ./setup_14.sh
# RUN apt update
# RUN apt install nodejs