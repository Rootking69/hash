# hash
Crack the hash TryHackMe wirteup

![passw](https://user-images.githubusercontent.com/44844246/160678484-38f91571-76b3-49cd-a8d8-e634ac691194.png)


To identify and crack the hashes I have some good links !!!!
1.https://hashes.com/en/decrypt/hash
2.https://crackstation.net/

Or some inbuilt tools in Kali Linux which are
Hash-Identifier
Hashcat

LVL 1



So let's begin our walkthrough of How to crack hashes. The hash given in the task is 

48bb6e862e54f2a795ffc4e541caed4d



![ezz](https://user-images.githubusercontent.com/44844246/160678841-edf92e8d-0cea-491c-82a0-99e2a3fa11bf.png)



you can see is the good one !



![try](https://user-images.githubusercontent.com/44844246/160679107-1ce72bb9-3e0c-4560-9c25-5526adf47d49.png)



for the second hash (CBFDAC6008F9CAB4083784CBD1874F76618D2A97) i went to https://crackstation.net/




![sec](https://user-images.githubusercontent.com/44844246/160679326-3cbc7f28-8b55-4e16-9d9e-4c303502ed6d.png)




you just put the hash there and you good :))  hash: CBFDAC6008F9CAB4083784CBD1874F76618D2A97




![crk](https://user-images.githubusercontent.com/44844246/160679419-af62b7f7-a7bf-4bf5-8839-be1ef1103205.png)



WE FOUND IT HAHAHA basic 



![dounf](https://user-images.githubusercontent.com/44844246/160679595-63c18c87-fc9b-4a6a-b795-10139e32cc75.png)



Next task hash is 1C8BFE8F801D79745C4631D09FFF36C82AA37FC4CCE4FC946683D7B336B63032




![wew](https://user-images.githubusercontent.com/44844246/160680144-ccbfd33b-1476-4eb6-807a-0439a92a7d91.png)



you gotta love this site !!!



![erere](https://user-images.githubusercontent.com/44844246/160680319-8f532ba3-7c47-4d8e-ac78-6d1432ba4c56.png)



$2y$12$Dwt1BZj6pcyc3Dy1FWZ5ieeUznr71EeNkJkUlypTsgbX1H68wsRom
be the next task
we can see this is  diff hash so we kinda need a terminal to crack it a bit harder boyszzz !! HAHA JK
We use this comand and tool : hashcat -m 3200 \$2y\$12\$Dwt1BZj6pcyc3Dy1FWZ5ieeUznr71EeNkJkUlypTsgbX1H68wsRom /usr/share/wordlists/rockyou.txt


And the resultant password is Bleh.



![1231](https://user-images.githubusercontent.com/44844246/160681677-4d09e23d-ef6b-4514-8b35-4e731511ae92.png)



Next-task: 279412f945939ba78ce0758d3fd83daa   last from lvl1 haha let's gooooo



![lcl1](https://user-images.githubusercontent.com/44844246/160682035-5452deb7-1056-467f-a527-f806a909305c.png)



password found : 	Eternity22



![asd](https://user-images.githubusercontent.com/44844246/160682057-d38a40a3-8c3d-4acc-abcb-0f96e272b113.png)





LVL 2









