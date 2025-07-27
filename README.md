# TCP-PortScanner
A simple TCP port scanner with go by using goroutines and channels with a worker pool.

After you lunched the binary, it will ask you for a valid host (IPv4,IPv6 or Domain name), then the range of ports you want to scan.
Don't scan any hosts that you don't have the permission to.

Examples :

![alt text](https://github.com/n00bspider/TCP-PortScanner/blob/main/examples/example.png)

If you write a domain name, it will use the DNS-Resolver to get the IP :

![alt text](https://github.com/n00bspider/TCP-PortScanner/blob/main/examples/example2.png)
