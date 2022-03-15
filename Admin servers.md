**w** -> show consoles actives
**tty** -> validate our console
**ps --ft** -> show PI of console

 #### Run script

 **nohup ./script.sh &  -> generate a Stdout and run de proccess**
 
#### Monitoring OS resources (top)
 
 With TOP we can show the resources for our system
 
 * Show proccess:
 	**cat /proc/cpuinfo | grep -i proc**
 * Show Memory:
 	**free -h**
 	
* Verify proccess that consum more CPU (k=3):
	**ps aux | sort -nr -k 3 | head -5**
	
* Verify proccess that consum more RAM (k=4):
	**ps aux | sort -nr -k 4 | head -5**