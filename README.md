# Off-Site-Pi-Backup
This program is intended to be used as an off-site backup automation tool.  Specifically this program will reach out to an openVPN server and use rsync to backup files to the Raspberry PI (or any NAS that runs Linux and can run an openVPN client).

Requirements:
Some type of Linux based host with the ability to run an OpenVPN client, and your own locally hosted openVPN server.

Basic idea:
The off-site Raspberry Pi is set up to periodically reache out to your local network via an OpenVPN server that you host, and it uses rsync to back-up files stored on a file server.  The point is to use the Raspberry Pi as an "off-site" file server to keep backups of your files.
