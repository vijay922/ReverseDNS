
# Reverse DNS Tool Script
This script takes a CIDR or a file with a list of CIDRs,
performs reverse DNS using hakrevdns, dnsx, cero, gdn and then runs httprobe on the results.
Credits to the original creator: @projectdiscovery @hakluke @glebarez @kmskrishna @ipk1 Krishna Iyengar

Usage: chmod +x install.sh
bash install.sh
go build -o ReverseDNS main.go
chmod +x ReverseDNS
./ReverseDNS 104.85.4.91/24 or CIDR list

