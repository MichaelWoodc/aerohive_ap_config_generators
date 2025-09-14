Two files, the index.html generates basic setup commands, and we have the optimizations page that can generate it with some basic tings like channel width, but I have not worked out the bugs yet.

https://michaelwoodc.github.io/aerohive_ap_config_generators/

https://michaelwoodc.github.io/aerohive_ap_config_generators/optimizations.html

Pro tip: 
on windonws to ssh into the AP, we need to:

PS C:\Users\Michael> ssh admin@192.168.1.109
  >>Unable to negotiate with 192.168.1.109 port 22: no matching MAC found. Their offer: hmac-sha1,hmac-ripemd160

PS C:\Users\Michael> ssh -o MACs=hmac-sha1 admin@192.168.1.109

