# ReverseDNS
Reverse DNS tool

Reverse DNS tool Script that takes a CIDR or a file with a list of CIDRs, performs reverse DNS with hakrevdns, dnsx, cero, and gdn, and then runs httprobe on the results

credits to original creator of the tool

@hakluke @glebarez @kmskrishna @ipk1 Krishna Iyengar

Usage: chmod +x install.sh

bash install.sh

go build -o revdns main.go

chmod +x revdns

./revdns CIDR or CIDR list
