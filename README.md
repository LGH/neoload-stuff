neoload-stuff
===============

These scripts intend to greatly speed up Neoload installation and deployment.

* **neoload.service**: The systemd script that makes it possible for systemd to manage  Neoload. To manually install
 the service, copy it to /etc/systemd/system/, execute `sudo systemctl enable neoload`, followed by `sudo systemctl
 start neoload`. Requires the user "neoload" to be present (or replace with your own), and make sure the ExecStart
 part is correct for your installation.
