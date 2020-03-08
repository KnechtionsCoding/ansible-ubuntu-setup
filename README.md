# ansible-ubuntu-setup
Setting up an Ubuntu Server with basic hardening

Sets up: 
* fail2ban
* sshd
* updates packages


For Minecraft servers:

* Allows port 25565
* Installs OpenJDK 8
* Downloads 1.8.8 Minecraft Spigot Server
* Configures user for minecraft to run as
* Configures sudoers minecraftadmins group to allow limited commands such to upload files for plugins, restart servers
* 