munin-tor
=========

Munin plugin to render various values taken from the a tor daemon.

Requires the stem library (https://stem.torproject.org/).


#### tor_connections
![alt tor_connections](https://i.imgur.com/LAkcKD0.png)
`ln -s /usr/share/munin/plugins/tor_ /etc/munin/plugins/tor_connections`

#### tor_traffic
![alt tor_traffic](https://i.imgur.com/YXLZHGa.png)
`ln -s /usr/share/munin/plugins/tor_ /etc/munin/plugins/tor_traffic


#### Adding new graphs
3.9 GETINFO - https://gitweb.torproject.org/torspec.git/blob/HEAD:/control-spec.txt

You can use get_info.py to lookup keys.


`
