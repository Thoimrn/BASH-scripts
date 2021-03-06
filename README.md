## BASH scripts
##### By: Thomas Hirneisen

### This project is an example of some simple network and system administration scripts I have written.

#### These scripts are in BASH format. Some of these scripts have been designed to be run in the background using a job scheduler. Others require user input and would be more appropriate to be run on demand by a user. They are examples of some basic script structures, if-then, for loops, case statements etc.


##### [SCRIPT_1](https://github.com/Thoimrn/BASH-scripts/blob/94b4cedf6846a9fefe555f99445fcfebdfb226eb/MvFile30) ~ A basic file cleanup script that moves files modified more than 30 days ago. It prompts user to confirm action before running.

##### [SCRIPT_2](https://github.com/Thoimrn/BASH-scripts/blob/8b539793b9210742d2b3295d53f81451c84a488e/BannerGrabServer) ~ This pulls the server version from the response header of a select web url and saves it as a file in the specified directory.

##### [SCRIPT_3](https://github.com/Thoimrn/BASH-scripts/blob/29d98323b2ae2f15d51c53edc16a82573b8e5d18/BitcoinPrice) ~ Using the free coindesk API, this script displays the current price of a bitcoin in USD, British Pounds, and Euros. 

##### [SCRIPT_4](https://github.com/Thoimrn/BASH-scripts/blob/2e89ba7db96ca2a0584a31da3316f4776ef58ece/FileBackup) ~ This is a script that uses tape archive to backup and gzip to compress files.

##### [SCRIPT_5](https://github.com/Thoimrn/BASH-scripts/blob/0e4c36d88bfd80ee18a59da6c36ae98ede1719d1/Btc_OverUnder) ~ A variation of Script 3, this script is designed to trigger an action if the price of a bitcoin is above or below $40,000. Using a job scheduler and a notification service this script can be used to send a buy signal. 

##### [SCRIPT_6](https://github.com/Thoimrn/BASH-scripts/blob/6a931f2b5dd773bd9d1bb7a818320b60c83370b7/Server-Status) ~ This script checks the connectivity of specified remote servers in a list file. Unreachable servers are displayed as offline in red text. 

##### [SCRIPT_7](https://github.com/Thoimrn/BASH-scripts/blob/e60503bb84cf448fa0055c6e82553dc1f3ceb11c/NA_Time) ~ Using the free WorldTimeApi this script shows your current time zone and displays a select North American time zone.


##### [SCRIPT_8](https://github.com/Thoimrn/BASH-scripts/blob/8857449f344e20b07755752abd6154eaba1fb3da/Encrypt) ~ A basic file encryption script that uses GNU Privacy Guard (gpg) to encrypt and decrypt files with a passphrase. 
