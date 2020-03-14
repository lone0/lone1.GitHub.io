## Welcome to GitHub Pages

Intel J1900 Compact Unit
Debian Buster

### Hardware Spec
Architecture:        x86_64
Address sizes:       36 bits physical, 48 bits virtual
CPU(s):              4
Thread(s) per core:  1
Vendor ID:           GenuineIntel
CPU family:          6
Model:               55
Model name:          Intel(R) Celeron(R) CPU  J1900  @ 1.99GHz
Stepping:            9
CPU MHz:             2091.912
CPU max MHz:         2415.7000
CPU min MHz:         1332.8000
Virtualization:      VT-x
Flags:               fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx rdtscp lm constant_tsc arch_perfmon pebs bts rep_good nopl xtopology tsc_reliable nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 cx16 xtpr pdcm sse4_1 sse4_2 movbe popcnt tsc_deadline_timer rdrand lahf_lm 3dnowprefetch epb pti ibrs ibpb stibp tpr_shadow vnmi flexpriority ept vpid tsc_adjust smep erms dtherm ida arat

enp1s0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet 192.168.17.216  netmask 255.255.255.0  broadcast 192.168.17.255
        inet6 fe80::290:67ff:fee0:2581  prefixlen 64  scopeid 0x20<link>
        ether 00:90:67:e0:25:81  txqueuelen 1000  (Ethernet)
        RX packets 46828795  bytes 24747733574 (23.0 GiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 71789727  bytes 59335064934 (55.2 GiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
        device memory 0xd0900000-d091ffff  

enp2s0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet 103.254.196.249  netmask 255.255.255.252  broadcast 103.254.196.251
        inet6 fe80::290:67ff:fee0:2582  prefixlen 64  scopeid 0x20<link>
        ether 00:90:67:e0:25:82  txqueuelen 1000  (Ethernet)
        RX packets 56477510  bytes 58730532291 (54.6 GiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 47887441  bytes 22588107830 (21.0 GiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
        device memory 0xd0800000-d081ffff  

enp3s0: flags=4099<UP,BROADCAST,MULTICAST>  mtu 1500
        inet 192.168.16.1  netmask 255.255.255.0  broadcast 192.168.16.255
        inet6 fe80::290:67ff:fee0:2583  prefixlen 64  scopeid 0x20<link>
        ether 00:90:67:e0:25:83  txqueuelen 1000  (Ethernet)
        RX packets 5906  bytes 1399930 (1.3 MiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 5325  bytes 1473515 (1.4 MiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
        device memory 0xd0700000-d071ffff  

enp4s0: flags=4099<UP,BROADCAST,MULTICAST>  mtu 1500
        ether 00:90:67:e0:25:84  txqueuelen 1000  (Ethernet)
        RX packets 0  bytes 0 (0.0 B)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 0  bytes 0 (0.0 B)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
        device memory 0xd0600000-d061ffff  
        
              total        used        free      shared  buff/cache   available
Mem:        3929408      237764     2477748       21524     1213896     3434344
Swap:       4080636           0     4080636

### Software
Debian Buster NetInst
PRETTY_NAME="Debian GNU/Linux 10 (buster)"
NAME="Debian GNU/Linux"
VERSION_ID="10"
VERSION="10 (buster)"
VERSION_CODENAME=buster
ID=debian
HOME_URL="https://www.debian.org/"
SUPPORT_URL="https://www.debian.org/support"
BUG_REPORT_URL="https://bugs.debian.org/"

#### WAN1: PPPoE
Install pppoeconf

#### WAN2: OpenVPN
/etc/openvpn/

#### LAN: private IPv4
/etc/network/interfaces.d/setup
/etc/dnsmasq.d/setup (dnsmasq)

#### LAN: Advanced Routing
/etc/sysctl.conf: Enable forwarding
/etc/iproute2/rt_tables
