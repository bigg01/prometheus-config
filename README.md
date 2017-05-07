# prometheus-config
# config reload

 $ curl -X POST http://localhost:9090/-/reload


# urls
https://www.robustperception.io/reloading-prometheus-configuration/
https://github.com/prometheus/collectd_exporter
http://www.techietown.info/2017/01/netdata-with-prometheus/
https://github.com/prometheus/node_exporter
#
https://www.digitalocean.com/community/tutorials/how-to-use-prometheus-to-monitor-your-centos-7-server
# haproxy
https://github.com/ramr/openshift-prometheus-haproxy-demo

# collectd exporter
https://github.com/prometheus/collectd_exporter
```
1554ab7265b6        prom/collectd-exporter   "/bin/collectd_export"   4 hours ago         Up 16 minutes       0.0.0.0:9103->9103/tcp, 0.0.0.0:25826->25826/udp   fervent_morse



Include "/etc/collectd.d"

LoadPlugin network
<Plugin network>
  Server "localhost" "25826"
</Plugin
```

