# Collecting diagnostics data
Follow these steps to collect diagnostics data for roksnet security servers.

1. Log in to `security server` with `ssh`.
2. Download `roksnet_diag` script with `curl`.
```
curl -O https://raw.githubusercontent.com/Roksnet/support/main/roksnet_diag
```
3. Grant execution privileges on `roksnet_diag`.
```
chmod 755 roksnet_diag
```
4. Execute diagnostics script by specifing destionation directory as first positional argument.
```
sudo ./roksnet_diag /tmp
```
5. Copy diagnostics archive from security server with `scp`, `rsync` or any other method and send it to `support@roksnet.com`.
