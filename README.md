# Fluentd Log Collector For Kubernetes

Load pod with fluent-pod.yaml

Currently didn't send logs to ovh, for debug a sample of payload passed to https://github.com/Graylog2/gelf-rb :
{"timestamp":1477915664.0,"_tag":"kubernetes.var.log.containers.fluentd-gelf_default_docker-fluentd-kubernetes-gelf-ea6231fcd00d6c393dec95dd740410605e6af450fccb9c5e3a4668c5c8e55925.log","facility":null,"_stream":"stdout","host":"fluentd-gelf","_version":"1.1","short_message":"2016-10-31 12:07:44 +0000 [info]: reading config file path=\"/etc/fluent/fluent.conf\"\n","_X-OVH-TOKEN":"MON TOKEN"}
