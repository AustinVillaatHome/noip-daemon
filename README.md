# NoIP Daemon

Automatic Update Daemon for the NoIP service. NAT translation was removed from the original to broadcast the HSR's local IP.

## Installation

Clone the repo.

    make
    sudo make install
    
Enter the username and password from the team documentation. There are multiple accounts (one for each HSR), so just update the one associated with your robot. Default interval is fine. Don't run anything on successful update.

Install the init script from Villa Tools to run the daemon on boot
