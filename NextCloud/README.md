POST INSTALL: change default files for new users

    SSH into server and navigate into the /var/docker/nextcloud/config
    nano config.php
    add line 'skeletondirectory' => '', at the end of the config within the end bracket. 
    save and exit file


Edit config.php to setup cloudflare tunnel: (overwrite protocol)

'overwriteprotocol' => 'https',

