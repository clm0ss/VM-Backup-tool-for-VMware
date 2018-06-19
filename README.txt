
This tool will backup VMs on multiple ESXi hosts, it will download the VMs whole directory and place everything into a folder named backup[month-date-year]

You can schedule a backup every 'n' days by running the .py file with --when=n option. (python xxx.py --when=3)

format the credentials for the ESXi hosts as follows, each on own line in the 'credentials.txt' file. (172.16.0.1:username:password)

add the virtual machines to download in the 'virtualmachines.txt' file, with each VM name on a new line, it is case sensitive.

if an intial connection session fails or the configuration text files are not found, the program will exit.

please contact clmoss@cisco.com for feature requests.

Coded by clm0ss Clayton Moss (clmoss@cisco.com) 