mtech@programming-lab-45:~$ sudo tcpdump -A tcp
[sudo] password for mtech: 
tcpdump: verbose output suppressed, use -v or -vv for full protocol decode
listening on enp2s0, link-type EN10MB (Ethernet), capture size 262144 bytes
15:36:24.416110 IP programming-lab-45.36650 > connectivity-check-ubuntu-com-0.ps5.canonical.com.http: Flags [S], seq 1086469341, win 64240, options [mss 1460,sackOK,TS val 1710212891 ecr 0,nop,wscale 7], length 0
E..<..@.@..X

.n.}.c.*.P@.4....................
e...........
15:36:24.416440 IP connectivity-check-ubuntu-com-0.ps5.canonical.com.http > programming-lab-45.36650: Flags [S.], seq 4007496359, ack 1086469342, win 32768, options [mss 1400,sackOK,TS val 1820194 ecr 1710212891,nop,wscale 5], length 0
E..<..@.@..c.}.c

.n.P.*....@.4............x...
..."e.......
15:36:24.416477 IP programming-lab-45.36650 > connectivity-check-ubuntu-com-0.ps5.canonical.com.http: Flags [.], ack 1, win 502, options [nop,nop,TS val 1710212891 ecr 1820194], length 0
E..4..@.@.._

.n.}.c.*.P@.4................
e......"
15:36:24.416578 IP programming-lab-45.36650 > connectivity-check-ubuntu-com-0.ps5.canonical.com.http: Flags [P.], seq 1:88, ack 1, win 502, options [nop,nop,TS val 1710212891 ecr 1820194], length 87: HTTP: GET / HTTP/1.1
E.....@.@...

.n.}.c.*.P@.4................
e......"GET / HTTP/1.1
Host: connectivity-check.ubuntu.com
Accept: */*
Connection: close


15:36:24.416772 IP connectivity-check-ubuntu-com-0.ps5.canonical.com.http > programming-lab-45.36650: Flags [.], ack 88, win 1024, options [nop,nop,TS val 1820194 ecr 1710212891], length 0
E..4L.@.@.j..}.c

.n.P.*....@.55....}#.....
..."e...
15:36:24.783477 IP connectivity-check-ubuntu-com-0.ps5.canonical.com.http > programming-lab-45.36650: Flags [P.], seq 1:115, ack 88, win 1024, options [nop,nop,TS val 1820304 ecr 1710212891], length 114: HTTP: HTTP/1.1 204 No Content
E...L.@.@.jn.}.c

.n.P.*....@.55....}R.....
....e...HTTP/1.1 204 No Content
server: nginx/1.18.0 (Ubuntu)
date: Wed, 08 Jul 2026 10:06:24 GMT
connection: close


15:36:24.783509 IP programming-lab-45.36650 > connectivity-check-ubuntu-com-0.ps5.canonical.com.http: Flags [.], ack 115, win 502, options [nop,nop,TS val 1710213258 ecr 1820304], length 0
E..4..@.@..]

.n.}.c.*.P@.55...............
e.......
15:36:24.783532 IP connectivity-check-ubuntu-com-0.ps5.canonical.com.http > programming-lab-45.36650: Flags [F.], seq 115, ack 88, win 1024, options [nop,nop,TS val 1820304 ecr 1710212891], length 0
E..4L.@.@.j..}.c

.n.P.*....@.55....|B.....
....e...
15:36:24.783601 IP programming-lab-45.36650 > connectivity-check-ubuntu-com-0.ps5.canonical.com.http: Flags [F.], seq 88, ack 116, win 502, options [nop,nop,TS val 1710213258 ecr 1820304], length 0
E..4..@.@..\

.n.}.c.*.P@.55...............
e.......
15:36:24.783837 IP connectivity-check-ubuntu-com-0.ps5.canonical.com.http > programming-lab-45.36650: Flags [.], ack 89, win 1024, options [nop,nop,TS val 1820304 ecr 1710213258], length 0
E..4L.@.@.j..}.c

.n.P.*....@.56....z......
....e...
^C
10 packets captured
10 packets received by filter
0 packets dropped by kernel
