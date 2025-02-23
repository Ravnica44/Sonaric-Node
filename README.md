https://github.com/0xmoei/sonaric-node

Sonaric Update v1.9.6

```shell
sudo systemctl stop sonaricd
```

`apt-get install sonaricd sonaric` or `sh -c "$(curl -fsSL https://get.sonaric.xyz/scripts/install.sh)"`

`sonaric version` and `sonaric node-info`

```shell
sudo systemctl status sonaricd
```

```shell
sudo journalctl -u sonaricd -f
```

```shell
sonaric run sonaric-gui/latest
```

```shell
sonaric ps
```

```shell
tail -f /var/lib/sonaricd/log/sonaricd.log
```
