# FRC_IDE_VM
Hey, Here's the first version of a 2016 FRC virtual machine image with:
Eclipse IDE + FRC plugins (and github plugin not tested). located at /home/frc/FRC/eclipse
FRCSim - simulator for FRC (launch with 'run as > wpilib Java simulation)
qdriverstation - cross platform driver station (someone tell ken). Launch with qdriverstation, its already in the $PATH. 
Git (ssh keys is not set up)
Java 8 (Oracle's, not the openJDK)
Defaults to LXDE but you can switch back to Unity or openBox. 
And I should have disabled all the social stuff (amazon one connectors)
OVA is located @ https://mega.nz/#!JoxD2RBA
!mBk_Lp4PYTTE5BRbynnwI4tp0lYjEGUVsE9EbkGmah0
(The latter red part is the decryption key if asked)

Login details
User: frc
Password: frc2016

But I built the pacgoat project and then ran it thru the FRCSim (man, is it super slow/not working). I ran FRCSim native on my old macbook, that sucked too. Not as bad as a VM though. 

Turns out if you convert the OVA to a VMWare player compatible disk, the VM performs incredibly well. 
https://www.youtube.com/watch?v=URtE-CwcKaE

Here it is running the FRCsim at a usable frame rate with my xbox controller (controller is not working, hence the robot driving in circles). 

