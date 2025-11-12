# Dashboard network monitoring setup with Prometheus and Grafana

- Clone this repository

```bash
  git clone https://github.com/niiccc/network-monitoring.git
```

- Run docker compose

```bash
  sudo docker-compose up
```

- Permission denied will pop up, update permission for volumes folder by stopping the docker and update permission

```bash
  sudo chmod -R 777 volumes/
```

- Run docker in background

```bash
  sudo docker-compose up -d
```

- Add data sources in connections subsection, fill prometheus server URL with:

```bash
  http://prometheus:9090
```

- Upload dashboard template .json in Grafana dashboard

- Update data source variable DS_PROMETHEUS and interface with prometheus

- Update variable instance value with IP Address snmp target

- Run queries for each panel 
