# Logs

## Purchase
- Created an account on `namecheap.com`. I did not like the fact that bigrocks validation errors were not making any sense to me.
- Purchased `headingtag.com` domain.
- Created account on `vultr.com` to purchase a server.
- Deployed a $5 server with ubuntu
- Added A records on `namecheap.com` to point `headingtag.com` to my server IP
- Waited for the server to be ready for use.

## Security
- Logged in as root user and created a sudo user vishnu - https://www.digitalocean.com/community/tutorials/how-to-create-a-sudo-user-on-ubuntu-quickstart
- Login as vishnu user and confirm access
- Follow few steps here to https://www.liquidweb.com/kb/things-to-do-after-installing-a-ubuntu-server/
    - Secure the Root User
    - Secure SSH Access
    - Install a Firewall
    - sudo ufw allow ssh
    - sudo ufw allow http
    - Keep the File System Up-To-Date

## TODO - More Security
- https://askubuntu.com/a/158631

## Apache Installing

- Follow the steps added here https://phoenixnap.com/kb/how-to-install-apache-web-server-on-ubuntu-18-04
- Install apache
- Verify Apache Installation

## Dummy website setup

- https://www.digitalocean.com/community/tutorials/how-to-set-up-apache-virtual-hosts-on-ubuntu-18-04
- Create the Directory Structure
- Grant Permissions
- Create Demo Pages for Each Virtual Host
- Create New Virtual Host Files
- Enable the New Virtual Host Files
- Verify that the dummy web page is shown

## SSL - Lets Encrypt

- https://www.digitalocean.com/community/tutorials/how-to-secure-apache-with-let-s-encrypt-on-ubuntu-20-04
- Installing Certbot
- Checking your Apache Virtual Host Configuration
- Allowing HTTPS Through the Firewall
- Obtaining an SSL Certificate
- Setup auto renewal
