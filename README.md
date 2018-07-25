```
   _____                   _____       _   _____       _            _   
  / ____|                 |  __ \     | | |  __ \     | |          | |  
 | |     _ __ ___  ___ ___| |__) |__ _| |_| |  | | ___| |_ ___  ___| |_ 
 | |    | '__/ _ \/ __/ __|  _  // _` | __| |  | |/ _ \ __/ _ \/ __| __|
 | |____| | | (_) \__ \__ \ | \ \ (_| | |_| |__| |  __/ ||  __/ (__| |_ 
  \_____|_|  \___/|___/___/_|  \_\__,_|\__|_____/ \___|\__\___|\___|\__|
```        

## About
CrossRatDetect is a tool to detect and remove CrossRat from infected Linux systems. Windows and MacOS are not supported yet!

Note that this is not a vulnerability scanner, it is a malware scanner used to identify compromised web application installations/systems. 

## Signs of infections
The RAT always uses the same user agent ("CrossRatSpider" or "CRS2017WBAGNT") to send HTTP requests during the scanning for vulnerable servers. 
Normally a machine which sends requests using the above user agent has to be considered as infected.

To double check it's reccommended to verify the presence of the folder /tmp/crcache which should contains a list of files, one for
each IP address which has been scanned.

## Usage

http://blog.dpsecurity.net/blog/2018/01/23/crossrat/
