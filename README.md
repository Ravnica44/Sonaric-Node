(https://github.com/0xmoei/sonaric-node)

Sonaric Update

CLI version:    v1.9.6
Daemon version: v1.9.6

sudo systemctl stop sonaricd

apt-get install sonaricd sonaric ou sh -c "$(curl -fsSL https://get.sonaric.xyz/scripts/install.sh)"

sonaric version et sonaric node-info

sudo systemctl status sonaricd

sudo journalctl -u sonaricd -f

sonaric run sonaric-gui/latest

sonaric ps

tail -f /var/lib/sonaricd/log/sonaricd.log
