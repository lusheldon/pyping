# pyping
A simple ping tool based on python with SOCK_RAW

	Usage:
	./pyping destination [-c count] [-t timeout] [-i interval]
	-c      count: specify how many times you want to ping
	-t    timeout: specify how long to wait for the response
	-i   interval: specify the time before next ping
	
        Example: 
		pyping 192.168.0.1 -c 4 -t 0.5 -i 0.01
		pyping www.google.com -t 2
