# FATBANDS-SIESTA
PROGRAM TO GENERATE FAT BAND STRUCTURES FROM SIESTA RESULTS (NON-SPIN)

Usage: fmgracefatband-siesta SIESTALABEL ref, where ref can be fermi or any energy value. 
To set yaxis range use:  fmgracefatband-siesta SIESTALABEL ref -10 10

Please create the file orb.input with each orbital (A_nl) and color to plot it
Colors represented by correspondent numbers of xmgrace schema
0=white; 1=black; 2=red; 3=green; 4=blue; 5=yellow; 6=brown; 7=grey;
8=violet; 9=cyan; 10=magenta; 11=orange; 12=indigo; 13=maroon; 14=turquoise

-----orb.input-----
C_2s 2
C_2p 4
-------------------

Remenber to rename the file SIESTALABEL.bands.WFSX to SIESTALABEL.WFSX

IMPORTANT: This program uses <siesta_version>/UTIL/COOP/fat and <siesta_version>/UTIL//Bands/eigfat2plot utilities. Put them in your PATH!
by Filipe Matusalem - December 2019
-----------------------------------------------------------------------------------------------
