Let's say, you are -
	
	- browsing on your web browser
	- listening to music on spotify
	- chatting with your friend on skype. 
	
You are doing these activities at the same time.	
	
Your web browser, spotify and skype - all of them send and receive data from internet. But your PC has only one internet connection. All data is sent and received with this single connection. 

Since all data is transmitted through the same connection, when data is received, how do we know which application should use which data? We need to have some sort of identifier which will tell us which data packet should be used by which application. We do this with port. Any service that need to connect to network, bind itself to a port, data packets that are being transmitted also have port number, operating system then forwards data packets to network services.