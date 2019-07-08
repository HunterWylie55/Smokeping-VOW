# Smokeping-VOW BETA
Smokeping install for VOW


Step 1.  Download zip file from Github or find it in Z:\Support Documents


Step 2. Exctract the zip file to an easily accessible location on your machine.



Step 3. launch winscp and kitty at the same time. 

-on kitty type in the pharmacy you need to be editied and click on their opie session, grab their Ip address and load into their opie.

-on winscp put in their ip and port number and login like you would on kitty.



Step 4. Extract the zip file into the "/" directory in winscp. (if you are in the correct directory it will have a ton of folders like bin, boot, debootstrap, etc.)


Step 5. open the smokeping folder you just extracted and highlight all the contents in the folder and right click > properties > and give Owner R,W,X privelages. Do NOT touch the other privelages.


Step 6. Open kitty with the opie you had previously loaded and then type     cd /smokeping     then    ./smokeping.sh
This will install smokeping automatically. Refer to my issues tab to know what to keep an eye out for and how to fix it.


If you find any issues let me know and I will add them to the bug list.
