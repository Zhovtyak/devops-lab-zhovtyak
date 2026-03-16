# Лабораторная работа №3 "Мониторинг с Prometheus и Grafana"

### 1. Создал папку prometheus и файл prometheus.yml
<p align="center">
  <img src="../assets/31.png" width="500">
</p>

### 2. Запустил контейнер Node Exporter для сбора системных метрик через Docker и проверил его работу, выполнив запрос curl http://localhost:9100/metrics.
<p align="center">
  <img src="../assets/32.png" width="500">
</p>

### 3. Запустил Prometheus
<p align="center">
  <img src="../assets/33.png" width="500">
</p>
<p align="center">
  <img src="../assets/34.png" width="500">
</p>

### 4. Запустил Grafana
<p align="center">
  <img src="../assets/35.png" width="500">
</p>
<p align="center">
  <img src="../assets/36.png" width="500">
</p>

### 5. Настроил Grafana: добавил источник данных Prometheus и создал дашборд с визуализацией метрики node_cpu_seconds_total.
<p align="center">
  <img src="../assets/37.png" width="500">
</p>
<p align="center">
  <img src="../assets/38.png" width="500">
</p>

### 6. Проверил запущенные контейнеры через docker ps, убедился в сборе метрик в Prometheus и проверил отображение графиков в Grafana, добавив графики для CPU, памяти и диска.
<p align="center">
  <img src="../assets/39.png" width="500">
</p>
<p align="center">
  <img src="../assets/40.png" width="500">
</p>