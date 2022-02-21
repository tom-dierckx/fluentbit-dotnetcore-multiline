# setup fluentbit local environment

Run project with mount:

```
podman run -it -v /home/tom/repo/fluentbitlocal/files:/fluent-bit/etc -v /home/tom/repo/fluentbitlocal/logs:/var/log fluent/fluent-bit:1.8.12
```