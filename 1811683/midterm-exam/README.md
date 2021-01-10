
<h3> Directory Summary </h3>

```
.
├── README.md
├── ansible.cfg
├── config
│   ├── centos
│   │   ├── 02-beats-input.conf
│   │   ├── 10-syslog-filter.conf
│   │   ├── 30-elasticsearch-output.conf
│   │   ├── elasticsearch.repo
│   │   ├── grafana.repo
│   │   ├── influxdb.repo
│   │   └── prometheus.repo
│   └── ubuntu
│       ├── 02-beats-input.conf
│       ├── 10-syslog-filter.conf
│       ├── 30-elasticsearch-output.conf
│       ├── filebeat.yml
│       └── midterm.html
├── config.yaml
├── inventory
├── playbook.yaml
└── roles
    ├── centos
    │   ├── elk
    │   │   ├── elasticsearch
    │   │   │   ├── README.md
    │   │   │   ├── defaults
    │   │   │   │   └── main.yml
    │   │   │   ├── files
    │   │   │   ├── handlers
    │   │   │   │   └── main.yml
    │   │   │   ├── meta
    │   │   │   │   └── main.yml
    │   │   │   ├── tasks
    │   │   │   │   └── main.yml
    │   │   │   ├── templates
    │   │   │   ├── tests
    │   │   │   │   ├── inventory
    │   │   │   │   └── test.yml
    │   │   │   └── vars
    │   │   │       └── main.yml
    │   │   ├── java
    │   │   │   ├── README.md
    │   │   │   ├── defaults
    │   │   │   │   └── main.yml
    │   │   │   ├── files
    │   │   │   ├── handlers
    │   │   │   │   └── main.yml
    │   │   │   ├── meta
    │   │   │   │   └── main.yml
    │   │   │   ├── tasks
    │   │   │   │   └── main.yml
    │   │   │   ├── templates
    │   │   │   ├── tests
    │   │   │   │   ├── inventory
    │   │   │   │   └── test.yml
    │   │   │   └── vars
    │   │   │       └── main.yml
    │   │   ├── kibana
    │   │   │   ├── README.md
    │   │   │   ├── defaults
    │   │   │   │   └── main.yml
    │   │   │   ├── files
    │   │   │   ├── handlers
    │   │   │   │   └── main.yml
    │   │   │   ├── meta
    │   │   │   │   └── main.yml
    │   │   │   ├── tasks
    │   │   │   │   └── main.yml
    │   │   │   ├── templates
    │   │   │   ├── tests
    │   │   │   │   ├── inventory
    │   │   │   │   └── test.yml
    │   │   │   └── vars
    │   │   │       └── main.yml
    │   │   └── logstash
    │   │       ├── README.md
    │   │       ├── defaults
    │   │       │   └── main.yml
    │   │       ├── files
    │   │       ├── handlers
    │   │       │   └── main.yml
    │   │       ├── meta
    │   │       │   └── main.yml
    │   │       ├── tasks
    │   │       │   └── main.yml
    │   │       ├── templates
    │   │       ├── tests
    │   │       │   ├── inventory
    │   │       │   └── test.yml
    │   │       └── vars
    │   │           └── main.yml
    │   ├── grafana
    │   │   ├── README.md
    │   │   ├── defaults
    │   │   │   └── main.yml
    │   │   ├── files
    │   │   ├── handlers
    │   │   │   └── main.yml
    │   │   ├── meta
    │   │   │   └── main.yml
    │   │   ├── tasks
    │   │   │   └── main.yml
    │   │   ├── templates
    │   │   ├── tests
    │   │   │   ├── inventory
    │   │   │   └── test.yml
    │   │   └── vars
    │   │       └── main.yml
    │   ├── influxdb
    │   │   ├── README.md
    │   │   ├── defaults
    │   │   │   └── main.yml
    │   │   ├── files
    │   │   ├── handlers
    │   │   │   └── main.yml
    │   │   ├── meta
    │   │   │   └── main.yml
    │   │   ├── tasks
    │   │   │   └── main.yml
    │   │   ├── templates
    │   │   ├── tests
    │   │   │   ├── inventory
    │   │   │   └── test.yml
    │   │   └── vars
    │   │       └── main.yml
    │   ├── lampstack
    │   │   ├── README.md
    │   │   ├── defaults
    │   │   │   └── main.yml
    │   │   ├── files
    │   │   ├── handlers
    │   │   │   └── main.yml
    │   │   ├── meta
    │   │   │   └── main.yml
    │   │   ├── tasks
    │   │   │   └── main.yml
    │   │   ├── templates
    │   │   ├── tests
    │   │   │   ├── inventory
    │   │   │   └── test.yml
    │   │   └── vars
    │   │       └── main.yml
    │   ├── nagios
    │   │   ├── README.md
    │   │   ├── defaults
    │   │   │   └── main.yml
    │   │   ├── files
    │   │   ├── handlers
    │   │   │   └── main.yml
    │   │   ├── meta
    │   │   │   └── main.yml
    │   │   ├── tasks
    │   │   │   └── main.yml
    │   │   ├── templates
    │   │   ├── tests
    │   │   │   ├── inventory
    │   │   │   └── test.yml
    │   │   └── vars
    │   │       └── main.yml
    │   └── prometheus
    │       ├── README.md
    │       ├── defaults
    │       │   └── main.yml
    │       ├── files
    │       ├── handlers
    │       │   └── main.yml
    │       ├── meta
    │       │   └── main.yml
    │       ├── tasks
    │       │   └── main.yml
    │       ├── templates
    │       ├── tests
    │       │   ├── inventory
    │       │   └── test.yml
    │       └── vars
    │           └── main.yml
    └── ubuntu
        ├── elk
        │   ├── elasticsearch
        │   │   ├── README.md
        │   │   ├── defaults
        │   │   │   └── main.yml
        │   │   ├── files
        │   │   ├── handlers
        │   │   │   └── main.yml
        │   │   ├── meta
        │   │   │   └── main.yml
        │   │   ├── tasks
        │   │   │   └── main.yml
        │   │   ├── templates
        │   │   ├── tests
        │   │   │   ├── inventory
        │   │   │   └── test.yml
        │   │   └── vars
        │   │       └── main.yml
        │   ├── filebeat
        │   │   ├── README.md
        │   │   ├── defaults
        │   │   │   └── main.yml
        │   │   ├── files
        │   │   ├── handlers
        │   │   │   └── main.yml
        │   │   ├── meta
        │   │   │   └── main.yml
        │   │   ├── tasks
        │   │   │   ├── 1
        │   │   │   └── main.yml
        │   │   ├── templates
        │   │   ├── tests
        │   │   │   ├── inventory
        │   │   │   └── test.yml
        │   │   └── vars
        │   │       └── main.yml
        │   ├── java
        │   │   ├── README.md
        │   │   ├── defaults
        │   │   │   └── main.yml
        │   │   ├── files
        │   │   ├── handlers
        │   │   │   └── main.yml
        │   │   ├── meta
        │   │   │   └── main.yml
        │   │   ├── tasks
        │   │   │   └── main.yml
        │   │   ├── templates
        │   │   ├── tests
        │   │   │   ├── inventory
        │   │   │   └── test.yml
        │   │   └── vars
        │   │       └── main.yml
        │   ├── kibana
        │   │   ├── README.md
        │   │   ├── defaults
        │   │   │   └── main.yml
        │   │   ├── files
        │   │   ├── handlers
        │   │   │   └── main.yml
        │   │   ├── meta
        │   │   │   └── main.yml
        │   │   ├── tasks
        │   │   │   └── main.yml
        │   │   ├── templates
        │   │   ├── tests
        │   │   │   ├── inventory
        │   │   │   └── test.yml
        │   │   └── vars
        │   │       └── main.yml
        │   └── logstash
        │       ├── README.md
        │       ├── defaults
        │       │   └── main.yml
        │       ├── files
        │       ├── handlers
        │       │   └── main.yml
        │       ├── meta
        │       │   └── main.yml
        │       ├── tasks
        │       │   └── main.yml
        │       ├── templates
        │       ├── tests
        │       │   ├── inventory
        │       │   └── test.yml
        │       └── vars
        │           └── main.yml
        ├── grafana
        │   ├── README.md
        │   ├── defaults
        │   │   └── main.yml
        │   ├── files
        │   ├── handlers
        │   │   └── main.yml
        │   ├── meta
        │   │   └── main.yml
        │   ├── tasks
        │   │   └── main.yml
        │   ├── templates
        │   ├── tests
        │   │   ├── inventory
        │   │   └── test.yml
        │   └── vars
        │       └── main.yml
        ├── influxdb
        │   ├── README.md
        │   ├── defaults
        │   │   └── main.yml
        │   ├── files
        │   ├── handlers
        │   │   └── main.yml
        │   ├── meta
        │   │   └── main.yml
        │   ├── tasks
        │   │   └── main.yml
        │   ├── templates
        │   ├── tests
        │   │   ├── inventory
        │   │   └── test.yml
        │   └── vars
        │       └── main.yml
        ├── lampstack
        │   ├── README.md
        │   ├── defaults
        │   │   └── main.yml
        │   ├── files
        │   ├── handlers
        │   │   └── main.yml
        │   ├── meta
        │   │   └── main.yml
        │   ├── tasks
        │   │   └── main.yml
        │   ├── templates
        │   ├── tests
        │   │   ├── inventory
        │   │   └── test.yml
        │   └── vars
        │       └── main.yml
        └── prometheus
            ├── README.md
            ├── defaults
            │   └── main.yml
            ├── files
            ├── handlers
            │   └── main.yml
            ├── meta
            │   └── main.yml
            ├── tasks
            │   └── main.yml
            ├── templates
            ├── tests
            │   ├── inventory
            │   └── test.yml
            └── vars
                └── main.yml

170 directories, 162 files
```
