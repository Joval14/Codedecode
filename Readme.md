#1/bin/bash

clear
echo -n "Enter your name: "
read name

clear
echo "Hello $name."
echo "Type the word devices to learn about devices"
read devices

clear
echo "$devices dev/null sends some stuff from the standard output to a file"
echo "Now saving that info"
echo "$name learn about $devices." >> devices.log

echo "Data saved"
echo "Press Enter to continue"
read

clear
echo "Type the word udevadm"
read udevadm

clear
echo "$udevadm is an administrator tool"
echo "Now saving that info"
echo "$name learn aboout $udevadm." >> udevadm.log

echo "Data saved"
echo "Press Enter to continue"
read

clear
echo "Have a nice day $name"

