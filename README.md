# setup fluentbit local environment

Run application

```
podman run -it -v /home/tom/fluentbitlocal/files:/fluent-bit/etc -v /home/tom/fluentbitlocal/logs:/var/log fluent/fluent-bit:1.8.12
```