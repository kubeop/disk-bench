测试方式

```bash
curl -sSL https://cdn.jsdelivr.net/gh/kubeop/disk-bench/entrypoint.sh | BENCH_MOUNTPOINT=/data bash -s fio
```
或
```
curl -sSL https://ghproxy.net/https://raw.githubusercontent.com/kubeop/disk-bench/main/entrypoint.sh | BENCH_MOUNTPOINT=/data bash -s fio
```
