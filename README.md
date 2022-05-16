测试方式

```bash
curl -sSL https://cdn.jsdelivr.net/gh/k8sre/disk-bench/entrypoint.sh | BENCH_MOUNTPOINT=/data bash -s fio
```
或
```
curl -sSL https://ghproxy.com/https://raw.githubusercontent.com/k8sre/disk-bench/main/entrypoint.sh | BENCH_MOUNTPOINT=/data bash -s fio
```
