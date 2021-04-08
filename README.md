# lcd-time-display

#Run auto python script easy steps

STEPS

STEP 1: Open new terminal..

sudo nano /etc/rc.local

STEP 2: Add your python file name with complete. 
- Example lets say your file is saved in /home/pi/Cheq-The-Rover/cheq_race-car.py
then add below line right below the last line where lines with # tags ended.

/home/pi/Cheq-The-Rover/cheq_race-car.py

STEP 3: Then Save the file by below commands

Press : ctrl x
Press : y
Press : Enter key

==> Above steps will save the rc.local file.

STEP 4: Now to your file directory and execute below command.

$ cd /home/pi/mirror
$ chmod +x mirror.py

STEP 5: Now after reboot pi, your file will run on boot.
 
 reboot
