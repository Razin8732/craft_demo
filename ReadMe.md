sudo a2ensite craft_demo.local.conf
sudo a2enmod rewrite
sudo systemctl restart apache2.service
sudo systemctl reload apache2

