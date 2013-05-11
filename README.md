# Phabber

Jabber bot for PHP.

Phabber cannot currently do anything at all.

Phabber will (hopefully) be an Jabber/XMPP bot built on the non-blocking React framework. It will be able to listen to notifications from third party services such as Github and broadcast these to users on a Jabber server. It will also be able to receieve commands from other Jabber users and use these to fetch information from third party services.

## Installation

This project uses [composer](http://getcomposer.org/) for dependency management. To load dependencies just run 'composer install' in the root directory of the project. If you want to install development dependencies run "composer install --dev" instead.

A Vagrant development environment is included as a git submodule. If you wish to use this you will need to initialise the submodule either after cloning the repo or when cloning it using the --recurisve option. Since the submodule also has its own submodules you'll also need to run 'git submodule update --recursive' after initialising the submodule. Once you have the submodule cd into the react-vagrant directory and run 'vagrant up'. This should install a complete vagrant development VM and will also install all composer dependencies for the project in shared directories between the host and the guest. For more information on the setup of the VM see [this repo](https://github.com/JCook21/react-vagrant).
