# Cohesity Oracle Backup Sample Script using souce-side dedupe library (sbt_tape)
Warning: this code is provided on a best effort basis and is not in any way officially supported or sanctioned by Cohesity. The code in this repository is provided as-is and the author accepts no liability for damages resulting from its use.

## Download individual script
Check individual script link

## AIX Prerequisite 
GNU package: bash, gawk, python, mpfr, findutils

## Download all SBT related scripts
### Linux
linux-sbt-download script will download all RMAN shell scripts to run on Linux servers and Cohesity Python scripts that are necessary to do Oracle backup and restore using Cohesity sbt library. 
### AIX
aix-sbt-download script will download all RMAN shell scripts to run on AIX servers and Cohesity Python scripts that are necessary to do Oracle backup and restore using Cohesity sbt library.

## Download SBT library
SBT library needs to be downloaded from Cohesity support site. 
### Linux
The linux sbt library link is http://downloads.cohesity.com/oracle_sbt/RPC-Library/6.4.1-and-above/libsbt_6_and_7_linux-x86_64.so. When you click it first, it may ask you to login. Once you login, click this link again. It will download the library to your computer. Copy this sbt library file to the lib directory in the script directory on the Oracle server (\<top directory\>/rman/lib).
### AIX
The AIX sbt installer script link is http://downloads.cohesity.com/oracle_sbt/RPC-Library/6.4.1-and-above/AIX/cohesity_plugin_sbt_0.0.0-master_aix_powerpc_installer. The installation command is

- cohesity_plugin_sbt_0.0.0-master_aix_powerpc_installer -- -d \<top directory\>/rman/lib

