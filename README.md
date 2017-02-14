# one-freebsd
Opennebula contextulization for FreeBSD (tested with 10.3)

To install simply clone the repo and copy the vmcontext into /etc/rc.d and the one-context.d folder into /etc making sure all the scripts are chmod +x
then echo 'vmcontext_enable="YES"' >> /etc/rc.conf
