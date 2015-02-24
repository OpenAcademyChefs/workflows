
#New Cookbooks

##Application vs. Library Cookbooks

The distinction I make between the two of these is that an 'application' cookbook is a cookbook meant for the management of a node, while a 'library' cookbook is one used for managing/configuring a particular program or resource, and is used as a dependency for application cookbooks.

##Creation

There are a few ways to create cookbooks. I have been using `berks cookbook <cookbook name>` to create the cookbooks.

##Configuration

Berkshelf takes its default settings from the knife configuration provided in `~/.chef/knife.rb`. These settings can be overridden in `~/.berkshelf/config.json`. The recommended cookbook workflow provided in these docs will make use of both knife and berkshelf in different capacities, so any settings shared between the two should be in `knife.rb`.


