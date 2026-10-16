# Win With Us — backend host list

The Win With Us app and admin read `hosts.json` to know which backend servers to use, in order.
Edit `hosts.json` (first = primary). Apps pick up changes within ~10 minutes (jsDelivr mirror can take up to ~12 h unless purged).
Only public server URLs go here — never keys or secrets.
