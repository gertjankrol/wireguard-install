## wireguard-install
WireGuard [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Ubuntu, Debian, CentOS and Fedora.

This script will let you set up your own VPN server in no more than a minute, even if you haven't used WireGuard before. It has been designed to be as unobtrusive and universal as possible.\
Clients will be configured to use the VPN server (`10.7.0.1`) as their DNS server, so make sure you have a DNS server running on the host when using this script.

### Installation
Run the script and follow the assistant:

`wget https://raw.githubusercontent.com/gertjankrol/wireguard-install/master/wireguard-install.sh -O wireguard-install.sh`\
`chmod +x wireguard-install.sh`\
`./wireguard-install.sh`

Once it's done, you can run it again to add more users, remove some of them or even completely uninstall WireGuard.

### Donations
If you want to show your appreciation, you can donate to [@Nyr](https://github.com/Nyr/wireguard-install) (creator of the repository I forked) via [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=VBAYDL34Z7J6L) or [cryptocurrency](https://pastebin.com/raw/M2JJpQpC). Thanks!
