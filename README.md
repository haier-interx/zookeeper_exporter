# Prometheus ZooKeeper Exporter

An exporter for [Prometheus](http://prometheus.io/) to monitor an [Apache ZooKeeper](http://zookeeper.apache.org/) ensemble.

## Building and Running

    make
    ./zookeeper_exporter

### Modes

zookeeper_exporter can be run in two modes: exhibitor and explicit.

In explicit mode (the default), it monitors a list of ZooKeeper servers given as command line args.

In exhibitor mode, the exporter will automatically discover servers by querying [Exhibitor]. Command lines args are assumed to be a list of Exhibitor nodes. To enable exhibitor mode, use the `-exporter.discovery.exhibitor` flag.



// 启动参数 需要监控zk的地址:zk的端口 上报的端口
// 10.138.8.223:2181 10.138.8.224:2181 10.138.8.225:2181 :9123


指标太少 替换为：
https://github.com/carlpett/zookeeper_exporter


