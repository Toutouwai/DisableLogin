# Disable Login

A module for ProcessWire CMS/CMF. Allows you to prevent selected roles from logging in. Logged-in users with those roles will be automatically logged out after the next page render, so that if they are in the process of submitting a form the data will not be lost. If the user was logged out while using the ProcessWire admin then a configurable message is shown to the user after logout.

Requires ProcessWire >= v3.0.62

## Usage?

[Install](http://modules.processwire.com/install-uninstall/) the Disable Login module.

In the module config select one or more roles to disable login for, or select "All non-superuser roles" if desired. Tip: to disable login for specific users, create a new role and give that role to the users, then select the role in the module config.
