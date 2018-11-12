
## Commands
After installing you will have access to the following commands to be used directly in terminal (as root)

* __changeUserpass__ - change users SSH/FTP/deluge/ruTorrent password
* __clean_mem__ - flushes servers physical memory cache (helps avoid swap overflow)
* __createSeedboxUser__ - creates a shelled seedbox user
* __deleteSeedboxUser__ - deletes a created seedbox user and their directories
<sup>**This is permanent, current data will be deleted - you can create them again at any time**</sup>
* __reload__ - restarts your seedbox services, i.e; rtorrent & irssi
* __removepackage-cron__ - upgrades your system to make use of systemd
* __setdisk__ - set your disk quota for any given user
* __showspace__ - shows amount of space used by each user
* __upgradeBTSync__ - upgrades btsync when new version is available
* __upgradeJackett__ - upgrades Jackett when new version is available
* __upgradeOmbi__ - upgrades Ombi when new version is available
* __upgradePlex__ - upgrades Plex when new version is available
* __upgradepyLoad__ - upgrades pyLoad when new version is available
* __box install letsencrypt__ used to install letsencrypt
* More commands detailed here: [DBox Seed Commands](https://quickbox.io/wiki/quickbox-commands/)

If your disk space widget is not showing the correct amount of space, run one of the following commands based on the mount you use:
* If you're using a /home mounted partition then run: __fix-disk_widget_home__
* If you're using a /(root) mounted partition then run: __fix-disk_widget_root__
<br/>
