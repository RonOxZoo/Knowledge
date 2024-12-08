http acronym --> hepertext transfer protocol.
-------------------------------------------
http port number = 80
-------------------------------------------
Gobuster --> webPT tool for enumarating websites.


switches:
-----------
dir - the classic directory brute-forcing   mode
    dns - DNS subdomain brute-forcing mode
    s3 - Enumerate open S3 buckets and look for existence and bucket listings
    gcs - Enumerate open google cloud buckets
    vhost - virtual host brute-forcing mode (not the same as DNS!)
    fuzz - some basic fuzzing, replaces the FUZZ keyword
    tftp - bruteforce tftp files
    ---------------------------------------

gobuster -x php --> will look for php files.
 Example usage:
 ---------------
 gobuster dir -x php --url http://10.129.140.37/ -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt