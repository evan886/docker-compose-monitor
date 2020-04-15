docker-compose快速搭建 Prometheus+Grafana+alertmanager 监控系统 


Prometheus负责收集数据，Grafana负责展示数据。其中采用Prometheus 中的 Exporter含：
1）Node Exporter，负责收集 host 硬件和操作系统数据。它将以容器方式运行在所有 host 上。
2）cAdvisor，负责收集容器数据。它将以容器方式运行在所有 host 上。
3）Alertmanager，负责告警。它将以容器方式运行在所有 host 上。
