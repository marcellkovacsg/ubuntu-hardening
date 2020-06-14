# Detailed list of changes

* ## User related changes

    * Adding DevOps group

    * Adding necessary users

    * Disabling password login

    * Disabling root login

    * Disabling switching to root

* ## Filesystem and package related changes

    * Installing common packages

        * htop
        * mc
        * iptables-persistent ( maybe ufw is already persistent)
        * sudosh

    * Set maximum number of processes and open files (limit_nofile,limit_nproc )

    * Disabling unwanted kernel modules

        * bluetooth
        * bnep (bluetooth network)
        * btusb ( bluetooth usb )
        * [cpia2](https://www.kernel.org/doc/html/latest/media/v4l-drivers/cpia2.html)
        * floppy
        * net-pf-31 ( bluetooth autoload )
        * [pcspkr](https://wiki.archlinux.org/index.php/PC_speaker)
        * soundcore ( bluetooth sound driver )
        * thunderbolt
        * usb-midi
        * usb-storage
        * [uvcvideo](https://help.ubuntu.com/community/UVC)
        * v4l2_common ( video4linux )

* ## Network related changes

    * Configuring ip-tables and/or ufw

    * Disabling ipv6

    * Disabling unused network modules

        * [dccp](https://en.wikipedia.org/wiki/Datagram_Congestion_Control_Protocol)
        * [sctp](http://manpages.ubuntu.com/manpages/bionic/man7/sctp.7.html)
        * [rds](http://manpages.ubuntu.com/manpages/trusty/man7/rds.7.html)
        * [tipc](http://manpages.ubuntu.com/manpages/bionic/man8/tipc.8.html)