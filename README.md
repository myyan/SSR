# install SSR
	- chmod +x shadowsocksR.sh
	- ./shadowsocksR.sh 2>&1 | tee shadowsocksR.log

# install bbr
	-  chmod +x bbr.sh && ./bbr.sh

    - sysctl net.ipv4.tcp_available_congestion_control

	if display below response  
    - net.ipv4.tcp_available_congestion_control = bbr cubic reno 
