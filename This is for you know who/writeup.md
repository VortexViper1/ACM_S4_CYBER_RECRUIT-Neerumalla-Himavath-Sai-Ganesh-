Firstly i have downloaded the provided ZIP file and extracted it in my device.
After extracting, I got a txt file and it includes ""This message is sent to voldemort, No muggle should read it" from this i confimed that its something which is hidden.
I used "ls -la" for hidden files in that zip, ".message to voldemort" this is the hidden directory i found.
Inside the folder we hae got "secret.png" file and i used binwalk on this file to reveal embedded zip data on png.
After extracting the hidden zip manually, it produced another file which is "horcrux.jpg".
Inside horcrux i have found this "Lord Voldemort for more security from these students i secured it in deathly hallows cloak".
After I used some passwords for steghide to get hidden files in horcrux but no use, when I used command exiftool on horcrux, I have got one comment which is encrypted and I have decrypted that with base 64.
"echo cG90dGVyeXdoMTVfMTVfRDAxMHlzNV9VbThyMWRnM30= | base64 -d"
Finally I have got the flag.



Flag -- potter{7h15_15_D010r35_Um8r1dg3}
