# bad_rep_iptables
iptables import for bad rep IP subnets

Data collected from attacks on my own host.
Some big subnets will be blocked from sending traffic to your host, so watch out for blocking unintended traffic.

sudo iptables-restore < iprules.v4

These are non-persistent, so you'd need to do something to make the rule persist after reboot.
