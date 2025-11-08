# nordvpn_connect
I only include non-virtual (physically based) servers in all lists. Toggles by region, will turn off GNOME shell  notifications while it connects to prevent notify spam, then turns notifications back on at the very end.
## Install
Use ``chmod +x nordvpn_connect`` and move it to ``/usr/local/bin`` for easy use.

# nordvpn_statusd
Optional. nordvpn_connect doesnt require this daemon.
It replaces your Scroll-Lock LED with a useful indication of VPN connection and status (blinks if nordlynx iface exists but doesn't have a valid connection) (solid if nordlynx is working).

KEYBOARD_DEVICE_NAME has to be set to the exact device name of your keyboard.
## Install
Use ``chmod +x nordvpn_statusd`` and move it to ``/opt``. If it exists in ``/opt/nordvpn_statusd``, nordvpn_connect will start it after a successful connection.

## Timeout
CONNECTION_TIMEOUT=5

(increments of 0.5 second)
## Continent Toggle
ASIA_DISABLE=1

EUROPE_DISABLE=0

AFRICAN_DISABLE=0

NORTH_AMERICAN_DISABLE=0

SOUTH_AMERICAN_DISABLE=0

OCEANIA_DISABLE=1

## Country Toggle
USA_DISABLE=1


