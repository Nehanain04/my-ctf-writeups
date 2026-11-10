#My First CTF Writeup

#1 Challenge Name:
A Frame from the South

#1Category
Forensics

#1Challenge Description
A response team recovered one photograph from a contractor’s camera card. 
Download camera_card.jpg and inspect its image metadata. Convert the GPS coordinates to decimal degrees.
Submit latitude and longitude to six decimal places, separated by an underscore: ISDF{latitude_longitude}.

#1Solution
upload the given file on metadata.
and check 1Latitude: 12° 58′ 12″ 
convert into decimal=12+(58/60)+(12/3600)7=12.970000
2 longitude:77° 35′ 24″ 
convert into decimal:77+35/60+24/3600=77.590000

#1flag
ISDF{12.970000_77.590000}

#2Challenge Name:
The Quiet Author

#2Category
Forensics

#2Challenge Description
A draft policy PDF was found in a shared export folder. Download policy.
pdf and inspect its document metadata. Who is recorded as the document author? 
Use lowercase and underscores in the flag.

#2Solution
upload the given file on metadata.
and check the author name. 

#2flag
ISDF{rhea_menon}

#3Challenge Name:
Office, Then the loader

#3Challenge Description
A Windows memory image was triaged with a process-tree view.
Download triage.txt and identify which process ran immediately beneath PowerShell. 
Submit its PID

#3Solution
power sell ki PID Hai
