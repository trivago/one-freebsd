# one-freebsd

> [!CAUTION]
> This repository has been archived as of October 2025.  
> If you wish to update or extend this project, please create a fork.

Opennebula contextulization for FreeBSD (tested with 10.3)

To install simply clone the repo and copy the vmcontext into /etc/rc.d and the one-context.d folder into /etc making sure all the scripts are chmod +x
then echo 'vmcontext_enable="YES"' >> /etc/rc.conf
