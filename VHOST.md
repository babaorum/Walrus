VHOST :

<<<<<<< HEAD
  $ sudo nano /etc/apache2/sites-available/walrus.dev
=======
<<<<<<< HEAD
  $ sudo nano /etc/apache2/sites-available/walrus.dev
=======
<<<<<<< HEAD
  $ sudo nano /etc/apache2/sites-available/walrus
=======
  $ sudo nano /etc/apache2/sites-available/walrus.dev
>>>>>>> develop
>>>>>>> 697477664f275c75f8bbab0e6a558d68da270038
>>>>>>> e59d1be0daef143a2eafb3491d348a3b85f14569


	<VirtualHost *:80>
                ServerAdmin webmaster@localhost
<<<<<<< HEAD
                ServerName walrus.dev
                ServerAlias www.walrus.dev
=======
<<<<<<< HEAD
                ServerName walrus.dev
                ServerAlias www.walrus.dev
=======
<<<<<<< HEAD

                ServerName walrus
=======
                ServerName walrus.dev
                ServerAlias www.walrus.dev
>>>>>>> develop
>>>>>>> 697477664f275c75f8bbab0e6a558d68da270038
>>>>>>> e59d1be0daef143a2eafb3491d348a3b85f14569

                DocumentRoot /var/www/Walrus
                <Directory /var/www/Walrus>
                        Options Indexes FollowSymLinks MultiViews
                        AllowOverride All
                        Order allow,deny
                        allow from all
                </Directory>

<<<<<<< HEAD
=======
<<<<<<< HEAD
=======
<<<<<<< HEAD
                # Chroot PHP script to this path
                php_admin_value open_basedir "/var/www/Walrus"
                # Tmp upload directory
                php_admin_value upload_tmp_dir "/var/www/Walrus/tmp"

=======
>>>>>>> develop
>>>>>>> 697477664f275c75f8bbab0e6a558d68da270038
>>>>>>> e59d1be0daef143a2eafb3491d348a3b85f14569
                ScriptAlias /cgi-bin/ /usr/lib/cgi-bin/

                ErrorLog ${APACHE_LOG_DIR}/error.log

                # Possible values include: debug, info, notice, warn, error, crit,
                # alert, emerg.
                LogLevel warn

                CustomLog ${APACHE_LOG_DIR}/access.log combined
        </VirtualHost>

___

<<<<<<< HEAD
	$ sudo a2ensite walrus.dev
=======
<<<<<<< HEAD
	$ sudo a2ensite walrus.dev
=======
<<<<<<< HEAD
	$ sudo a2ensite walrus
=======
	$ sudo a2ensite walrus.dev
>>>>>>> develop
>>>>>>> 697477664f275c75f8bbab0e6a558d68da270038
>>>>>>> e59d1be0daef143a2eafb3491d348a3b85f14569
	$ sudo service apache2 reload

___

Host to add (Windows ou Mac) AND VM :

    127.0.0.1       walrus.dev

path VM :

<<<<<<< HEAD
    sudo nano /etc/hosts
=======
<<<<<<< HEAD
    sudo nano /etc/hosts
=======
<<<<<<< HEAD
    sudo nano /etc/hosts
=======
    sudo nano /etc/hosts
>>>>>>> develop
>>>>>>> 697477664f275c75f8bbab0e6a558d68da270038
>>>>>>> e59d1be0daef143a2eafb3491d348a3b85f14569
