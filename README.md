# iptables-cheatsheet

I hate iptables. That's why i have these on hand.

Also some tips:

* For single host setups use docker with --iptables=false, your life will get much easier.
* Do not commit what docker generates as rules,  i.e. be carful when running `iptables-save > /etc/iptables/rules.v4`

