               total        used        free      shared  buff/cache   available
Mem:           3.7Gi       547Mi       2.8Gi        28Mi       481Mi       3.1Gi
Swap:          1.0Gi       780Ki       1.0Gi
12State        Recv-Q        Send-Q                Local Address:Port               Peer Address:Port       Process
LISTEN       0             1000                 10.255.255.254:53                      0.0.0.0:*
LISTEN       0             4096                     127.0.0.54:53                      0.0.0.0:*
LISTEN       0             4096                  127.0.0.53%lo:53                      0.0.0.0:*State        Recv-Q        Send-Q                Local Address:Port               Peer Address:Port       Process
LISTEN       0             1000                 10.255.255.254:53                      0.0.0.0:*
LISTEN       0             4096                     127.0.0.54:53                      0.0.0.0:*
LISTEN       0             4096                  127.0.0.53%lo:53                      0.0.0.0:*
userlakhdari@DESKTOP-7IN4NVM:~$ free -h && nprocUSER       PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root         1  0.0  0.3  22232 13056 ?        Ss   10:33   0:02 /usr/lib/systemd/systemd --system --deserialize=65
root         2  0.0  0.0   3120  1920 ?        Sl   10:33   0:00 /init
root         7  0.0  0.0   3120  1792 ?        Sl   10:33   0:00 plan9 --control-socket 7 --log-level 4 --server-fd 8 --pipe-fd 10 --log-truncate
root        43  0.0  0.3  66756 14944 ?        S<s  10:33   0:00 /usr/lib/systemd/systemd-journald
root       102  0.0  0.1  25412  6528 ?        Ss   10:33   0:01 /usr/lib/systemd/systemd-udevd
systemd+   111  0.0  0.3  21340 12032 ?        Ss   10:33   0:00 /usr/lib/systemd/systemd-resolved
systemd+   112  0.0  0.1  91032  7424 ?        Ssl  10:33   0:00 /usr/lib/systemd/systemd-timesyncd
root       159  0.0  0.0   4236  2304 ?        Ss   10:33   0:00 /usr/sbin/cron -f -P
message+   160  0.0  0.1   9788  4992 ?        Ss   10:33   0:00 @dbus-daemon --system --address=systemd: --nofork --nopidfile --systemd-activation --syslog-only
root       177  0.0  0.2  17968  8192 ?        Ss   10:33   0:00 /usr/lib/systemd/systemd-logind
root       201  0.0  0.5 107020 22396 ?        Ssl  10:33   0:00 /usr/bin/python3 /usr/share/unattended-upgrades/unattended-upgrade-shutdown --wait-for-signal
root       305  0.0  0.0   3124   768 ?        Ss   10:33   0:00 /init
root       306  0.0  0.0   3140  1024 ?        S    10:33   0:00 /init
userlak+   307  0.0  0.1   6072  5248 pts/0    Ss+  10:33   0:00 -bashuserlakhdari
uid=1000(userlakhdari) gid=1000(userlakhdari) groups=1000(userlakhdari),4(adm),24(cdrom),27(sudo),30(dip),46(plugdev),100(users)PRETTY_NAME="Ubuntu 24.04.5 LTS"
NAME="Ubuntu"
VERSION_ID="24.04"
VERSION="24.04.5 LTS (Noble Numbat)"
VERSION_CODENAME=noble
ID=ubuntu
ID_LIKE=debian
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
UBUNTU_CODENAME=noble
LOGO=ubuntu-logo6.6.87.2-microsoft-standard-WSL2
