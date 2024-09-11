# Mail Relay Configuration with Exim and Firewall Rules

## Overview

This repository provides a step-by-step guide to configure a mail relay on a WHM/cPanel server using Exim and set up the necessary firewall rules to ensure proper email relaying. This setup is useful for routing outgoing emails through an external mail server.

## Documentation

### Configuring Mail Relay

The detailed guide for configuring a mail relay using Exim on a WHM/cPanel server can be found in the `MAIL_RELAY_SETUP.md` file. This guide includes:

- How to configure Exim to use a smarthost for relaying emails.
- Steps to set up smarthost support in both the basic and advanced editors of Exim.
- Authentication configuration if required by the smarthost.

### Configuring Firewall Rules

Instructions for setting up firewall rules to allow the new server's IP address to relay emails through the existing mail server are also included in the `MAIL_RELAY_SETUP.md` file. This section covers:

- How to access and modify firewall settings in WHM.
- Adding rules to allow traffic on the required SMTP ports from the new server’s IP address.
