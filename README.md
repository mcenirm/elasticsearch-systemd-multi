systemd unit file for multiple elasticsearch instances

based on elasticsearch-2.4.4-1.noarch, assumes el7-ish distro

```
sudo install -o root -g root -m 0644 -p -v -T elasticsearch@.service /etc/systemd/system/elasticsearch@.service
```
