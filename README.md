# Perl6 dyndns
Perl 6 version of Perl 5 dyndns (from 2008 version of http://download.savannah.nongnu.org/releases/perl-dyndns/)

Any dynamic dns client needs to get the public IP of its host. One way to get it on a Linux
host is:

    $ dig +short myip.opendns.com
    32.45.62.7
    
Then your dynamic dns client updates the remote host dns service with that address.
