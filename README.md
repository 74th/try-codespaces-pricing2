universal 以外の Dev Container イメージでも、料金がかかるのか？

rust のイメージでテスト

mcr.microsoft.com/vscode/devcontainers/rust:0-${VARIANT}

Used 24GB

```
@74th ➜ /workspaces/try-codespaces-pricing2 (main) $ df -h
Filesystem      Size  Used Avail Use% Mounted on
overlay          32G   24G  6.3G  80% /
tmpfs            64M     0   64M   0% /dev
tmpfs           2.0G     0  2.0G   0% /sys/fs/cgroup
shm              64M     0   64M   0% /dev/shm
/dev/sdb1        16G   60K   15G   1% /tmp
/dev/sda1        29G  9.8G   20G  34% /vscode
/dev/loop0       32G   24G  6.3G  80% /workspaces
tmpfs           2.0G     0  2.0G   0% /proc/acpi
tmpfs           2.0G     0  2.0G   0% /proc/scsi
tmpfs           2.0G     0  2.0G   0% /sys/firmware
```
