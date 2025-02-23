https://github.com/0xmoei/sonaric-node

Sonaric Update v1.9.6

```shell
sudo systemctl stop sonaricd
```

```shell
apt-get install sonaricd sonaric ou sh -c "$(curl -fsSL https://get.sonaric.xyz/scripts/install.sh)"
```

```shell
sonaric version et sonaric node-info
```

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
