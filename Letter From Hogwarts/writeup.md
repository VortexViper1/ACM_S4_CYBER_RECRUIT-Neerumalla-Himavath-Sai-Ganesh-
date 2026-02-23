This is one of the tasks that really gave me a hard time.
Firstly I have downloaded the pdf which is provided.
I used strings and exiftool if there is a clue but nothing is there, as I am scrolling down its nothing showing after I tried with some patterns like grep password in strings but its empty.
After that I used pdfcrack tool and I used some common passwords and also I kept a folder which is related to harrypotter theme as the task is designed like that but no use.
After I used the same thing with JOHN THE RIPPER to try some common passwords and theme related passwords but no use.
After I used some patterns and masks but no use.
Lastly I downloaded wordlist (rockyou) which contain the old cracked passwords, again I checked with john then I have got the password for file..
"john --wordlist=/usr/share/wordlists/rockyou.txt hash.txt"
After, I saved that in another file and got password for that and unlocked and finally I got the flag.


flag -- potter{w3lc0m3_70_h0gw4r75}
