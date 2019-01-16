project comp 6461
by Pazim Goyal

There are 10 cases which could be used to test the program using keys 1 - 10.
If you want to add any command manually just press any key (i.e 0, a ,b ) and enter command in format :
[anyword i.e curl,httpc,comp] [get/post/help] [-v] [-h key:value][-d data][-f filename.ext] [url][-o filename.ext]

Project handels most  of exceptions like
1. Entered header in non key value pair would result in removing header
2. Entering both data and file name would result in eleminating one
3. Redirected Url may be full url or just path
4. User may enter full url using http:// or just the host name
5. if we receive just header in output and there is no verbose it will display header
6. Entering just host without any path will work


After execution of command 
1. if file is created it would be saved in same folder where .py file is kept
2. User will get option to run program again by pressing "Y" or exit using any other key    