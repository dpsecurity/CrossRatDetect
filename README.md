```
_________                            __________         __ ________          __                 __   
\_   ___ \_______  ____  ______ _____\______   \_____ _/  |\______ \   _____/  |_  ____   _____/  |_ 
/    \  \/\_  __ \/  _ \/  ___//  ___/|       _/\__  \\   __\    |  \_/ __ \   __\/ __ \_/ ___\   __\
\     \____|  | \(  <_> )___ \ \___ \ |    |   \ / __ \|  | |    `   \  ___/|  | \  ___/\  \___|  |  
 \______  /|__|   \____/____  >____  >|____|_  /(____  /__|/_______  /\___  >__|  \___  >\___  >__|  
        \/                  \/     \/        \/      \/            \/     \/          \/     \/      
```        

## About
CrossRatDetect is a tool to detect and remove CrossRat from infected Linux systems. Windows and MacOS are not supported yet!

Note that this is not a vulnerability scanner, it is a malware scanner used to identify compromised web application installations/systems. 

## Signs of infections
The RAT always uses the same user agent (CrossRatSpider) to send HTTP requests during the scanning for vulnerable servers. 
Normally a machine which sends requests using the above user agent has to be considered as infected.

To double check it's reccommended to verify the presence of the folder /tmp/crcache which should contains a list of files, one for
each IP address which has been scanned.

## Usage

http://blog.dpsecurity.net/blog/2018/01/23/crossrat/
