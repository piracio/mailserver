# mailserver
This build have all the components needed to deploy a mailserver, 

webmail - roundcube
postfix - ports 25 and 465
mysql - to Store and manage the accounts.
AV - ClamAV
postfixadmin - Webconsole to manage all the accounts.
fail2ban- ( to block ssh access from dictionary attacks ).
Dovecot - IMAPS and POPS
Mailgraph - (To collect Statistics ).
vnstat - This tool collects network statistics. 
Filesystem XFS ( I like this filesystem ).

TODO: Configure a replication across two servers using dovecot features.
