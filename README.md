# Labview Lost Bitcoin -Key-Finder
 Labview Bitcoin Lost Key finder.

Uses Linux named Pipes implementation to read Keygen executable. Peaks out at 1,065,000 Addresses a second.
Benchmarked on 4X E7-4830 Processors, 50 threads. Uses text Address File.
Can search a few Million address Compressed and Uncompressed With no siginificant slow down using labview search 1d array VIM. 
See Example Bitcoin address File. Also Can notify with Text message. 

Issues

 Current Build Will not save found key file untill you set path in VI But will copy it to the clip baord. 
 Pipe Data format issues causes loss in 1 in a few thousands lines. Still trying to figure this out. 
 Need to set or automate path to save Found Key file. Loop timing is ajustable as throttle
 Becuase doesn't handle pipe wait properly but could be fixed possibly. Default is 2 Ms.
 Collaborators Welcome!

Labview Version 2020 Linux Bitcoin Key finder
Uses Fast Keygen By Magnuspub with Mod's. 




![Key Finder](https://user-images.githubusercontent.com/36019554/180500126-c5626ea6-956f-4d81-bfd4-71770173cb0f.jpg)





Instructions 

Install labview 2020 or newer community addition Linux. 

Note: Keygen needs path Set In source code constant. (Would like to automate this In the future and package release with Keygen).

Copy all Project files Main Vi and sub vi's into a folder.
Open project (Bitcoin Lost key Finder.lvproj)
Open (Hunters Crack Pipes.vi) <------Main VI
Set Path for Keygen, Copy Keygen executable to path you choose.
Set Path constant in (Search both Addresses Sub vi) to save found key file. (optional)
Load Search text File. File can have one address or millions. Or use the indled file with over 500k Addresses. 
Run VI. 
Select Number of threads. 
Press start. Enjoy! 

Chances of finding a Key Near Zero but hey, you never know! 

Donate: Bitcoin Address  bc1q7h637v8x62lapknuvlyxzf0ylan38vexc0h6wr


