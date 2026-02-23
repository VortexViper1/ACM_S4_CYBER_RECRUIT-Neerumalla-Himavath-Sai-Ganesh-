Firstly I have downloaded the pcap file which contains packets or requests.
After I filtered packets with http and manually see PACKET BYTES PANE which is the bottom right corner contains hexa decimal data as well as ASCII data but no use.
After I export those as objects and I got some jpgs, I checked those with exiftool, if there are comments and lastly it is true in the file "ron.jpg" I have got the flag.
When I submitting this as flag its not coming later I was realized that there is 2nd part and I have got nothing with exiftool.
Later I used ghex, which is hex editor shows hexadecimals and ascii text when I have gone through that data I have got 2nd part as this 
"w1tch3s_$nd_w1z4rds}" then I combined them and submitted the flag.


flag -- ACM{w3_4r3_cyb3rw1tch3s_$nd_w1z4rds}"
