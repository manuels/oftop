# Intro

Like `top` but for open files.

# Installation

    sudo pip3 install oftop

# Usage

Call the programm:

    sudo oftop

Then you will see output like this:

    oftop v0.1.0 (Ctrl+C to quit)
    
      PID     USER STATUS   POSITION       SIZE   POS%      SPEED  COMMAND                   FILE
     4386   manuel S         2495608  473088368   0.5% 1012.7 KB/s  /usr/bin/vlc --started-fr /home/manuel/Videos/Meet Linux Kernel Developer Greg Kroah-Hartman-agC5N9I6jRE.webm
     4339   manuel S               0   18782166   0.0%    0.0 B/s  /usr/bin/nautilus --gappl /home/manuel/.local/share/tracker/data/tracker-store.journal
      642     root S         2128516    2128516 100.0%    0.0 B/s  /usr/sbin/rsyslogd -n -iN /var/log/syslog
      642     root S         3021360    3021360 100.0%    0.0 B/s  /usr/sbin/rsyslogd -n -iN /var/log/messages
      642     root S         1764542    1764542 100.0%    0.0 B/s  /usr/sbin/rsyslogd -n -iN /var/log/user.log
      642     root S         1463557    1463557 100.0%    0.0 B/s  /usr/sbin/rsyslogd -n -iN /var/log/daemon.log
      642     root S          188136     188136 100.0%    0.0 B/s  /usr/sbin/rsyslogd -n -iN /var/log/debug
        1     root S               0          0   0.0%    0.0 B/s  /sbin/init                /proc/1/mountinfo
     1084   manuel S             100          0 100.0%    0.0 B/s  /lib/systemd/systemd --us /proc/swaps

