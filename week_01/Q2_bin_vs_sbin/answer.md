Difference Between /bin and /sbin in Linux
FHS – Filesystem Hierarchy Standard Explanation

The Linux Filesystem Hierarchy Standard (FHS) separates /bin and /sbin based on their purpose and who should use them.

  /bin — Essential User Commands:

This directory contains basic executable programs required for the system to operate normally.
All users — including regular (non-root) users — must be able to run these commands.

Examples:

ls — list files

cp — copy files

mv — move/rename files

bash — the main shell

Available to everyone
Required for normal system operation

 /sbin — System Administration Commands:

This directory contains executables used for system management and maintenance.
Most commands here require root privileges.

Examples:

fdisk — disk partitioning

ifconfig — network configuration

reboot — restart the system

