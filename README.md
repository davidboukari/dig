# dig

```bash
dig  davidtheteacher.com any

; <<>> DiG 9.10.6 <<>> davidtheteacher.com any
;; global options: +cmd
;; Got answer:
;; ->>HEADER<<- opcode: QUERY, status: NOERROR, id: 13387
;; flags: qr rd ra; QUERY: 1, ANSWER: 7, AUTHORITY: 0, ADDITIONAL: 1

;; OPT PSEUDOSECTION:
; EDNS: version: 0, flags:; udp: 1472
;; QUESTION SECTION:
;davidtheteacher.com.		IN	ANY

;; ANSWER SECTION:
davidtheteacher.com.	60	IN	A	44.238.22.250
davidtheteacher.com.	60	IN	A	52.35.142.205
davidtheteacher.com.	86400	IN	NS	ns-1524.awsdns-62.org.
davidtheteacher.com.	86400	IN	NS	ns-2040.awsdns-63.co.uk.
davidtheteacher.com.	86400	IN	NS	ns-304.awsdns-38.com.
davidtheteacher.com.	86400	IN	NS	ns-765.awsdns-31.net.
davidtheteacher.com.	900	IN	SOA	ns-1524.awsdns-62.org. awsdns-hostmaster.amazon.com. 1 7200 900 1209600 86400

;; Query time: 40 msec
;; SERVER: 192.168.0.254#53(192.168.0.254)
;; WHEN: Mon Jan 11 21:16:31 CET 2021
;; MSG SIZE  rcvd: 278
```
