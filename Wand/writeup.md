Firstly, I have downloaded the wand.jpeg which is provied on task.
After seeing the image which have provided, as wand is related to harrypotter and I did not see yet, I have asked google that whose wand is this, then it replied that it is "Albus Dumbledore".
I checked the jpeg with strings and exiftool.
Strings is a command which is used to all readable ascii text from binary file as it is jpeg.
Exiftool is a command which is used to see the metadata which includes comments in jpeg or any files, I got output as password : Full name of the wielder. 
I used "strings wand.jpeg" and i got output as password : Full name of the wielder, Then i have got an idea that there's something hidden file is presented in jpeg.
After i used "steghide" command which is used to extract the hidden data embedded inside any file.
steghide extract -sf wand.jpeg, -sf which represents steg file and we have also -cv which represents coverfile used to cover the file or hidethe data.
it asks me for a password and I typed the full name of wielder which is "albuspercivalwulfricbriandumbledore".
The flag is extracted to another file and I have got that!!

flag -- potter{1_570l3_7h47_3ld3r_w4nd}
