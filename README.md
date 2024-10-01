# Reverse Shell
A simple python program to create a reverse shell from a client to a server.
This makes it possible to open a shell on a machine behind a NAT or firewall.


## Usage
Server:

    reverse_shell -a 1.2.3.4 -p 1234

Client:

    reverse_shell -c -a 1.2.3.4 -p 1234

