SSH into docker host
Create directories:

    /var/docker
    /var/docker/wordpress

Create new file called uploads.ini in /var/docker/wordpress

    upload_max_filesize = 20M
    post_max_size = 20M
    Save file



Create environment variable called MYSQL_DATABASE_PASSWORD

    Set password to be a long complex password

Deploy stack
Navigate to newly created Wordpress site on the port number.
Follow steps to setup site
Verify the uploads.ini

    Log into the Wordpress Admin console
    Select Media on the left pane
    Select Upload > the upload limit should be 20MB

Enjoy!
