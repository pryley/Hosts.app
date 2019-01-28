Hosts, a native macOS application to manage your hosts file.
----------------------------------------------------------

Hosts lets you toggle your host file entries on and off, as well as add and remove them.

Hosts likes to keep your hosts file clean. When an entry is toggled off, it is not commented out in the hosts file, but instead stored in the app's preferences storage. This means you will have to uncomment all your unused host entries and untoggle them in the prefpane if you want to use them. Comments are treated as comments and will never show up in the list of host entries!

Hosts will also detect edits you made to the ``/etc/hosts`` directly and merge them into the listing.

Backups of your hosts file is made in ``~/Library/Application Support/Hosts``. The backup or your hosts file from before you started using Hosts is called *hosts.orig* and each session a backup is made called *hosts.session*.

The default host entries that are needed by the OS are hidden and can not be edited using Hosts.
 
![](https://github.com/pryley/Hosts.app/raw/master/edit.png)

Licence: GPL-3.0
