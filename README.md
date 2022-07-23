# mykteam.com
<p align="center"><strong>Auto Install & Optimize LEMP Stack on Ubuntu (18.04, 20.04)</strong></p>
<p align="center"><strong>Author: Admin - MYKTEAM</strong></p>
<p align="center"><strong>Home Page: <a href="https://mykteam.com">MYKTEAM Home page</a> , <a href="https://mykteam.com">mykteam.com - Share tips, resources, giftcode</a></strong></p>
<p align="center"><strong>Facebook : https://www.facebook.com/mykitteam</strong></p>

<p align="center"> <img src="https://" /> </p>

########################################################################################

Script written in shell to install LEMP Stack (Nginx - MariaDB - PHP-FPM) on Ubuntu (18.04, 20.04)
111111111111

## 1. Script details:

### 1.1. Setting
- Continuously updated, providing Menu for easy operation, automatic installation.
- Install the software with the latest version from the main homepage.
- Mariadb: 10.5.
- Nginx Stable version.
- Allow to choose PHP version: 5.6, 7.0, 7.1, 7.2, 7.3, 7.4, 8.0
- phpMyAdmin 4.9.x if default PHP installation is 5.6, phpMyAdmin 5.0.x if default PHP installation is 7.x.
- Configure Nginx FastCGI cache
- Configure Nginx Pagespeed
- Install PHPMemcachedAdmin, phpRedisAdmin, Opcache Dashboard.
- Install memcached, redis cache. (Default won't turn on).
- Install CSF
- Integrated Let's Encrypt SSL.
- Integrated CloudFlare DNS API for faster SSL authentication.
- Provide Upgrade Menu Nginx, MariaDB, PHP, Redis, Memcached, phpMyAdmin.
- Install WP-CLI, Composer, supervisor, Rclone.
- Install: ClamAV, ImunifyAV.
- DO NOT COLLECT ANY INFORMATION ON YOUR VPS.

### 1.2. Optimal
- Optimally configure MySQL, Nginx, PHP, Opcache, Memcached, Redis in accordance with VPS's parameters.
- Configure Brotli Compress.
- Configure URL rewrite with some popular source code: WordPress, Laravel, Opencart, Magento, Drupal...
- Allows running two versions of PHP in parallel.
- Easy FTP management in case you hire coders and only want them to have access to certain folders.
- Allows you to choose Redis Cache or Memcached to help speed up your website.
- Allows configuration of Let's Encrypt auto-renewal.
- The menu supports paid SSL configuration.
- Menu view error log Nginx, Mysql, PHP and view by specific domain.
- Cronjob automatically updates Cloudflare's latest IP range for Nginx and CSF Firewall.
- And More...

### 1.3. Security
- Configure enhanced security from the webserver layer.
- Configure the website to run with different users to limit the spread of malicious code between websites.
- Disable dangerous functions, enable open_basedir and some other configs to enhance security.
- Auto block bruteforce SSH, SFTP, Admin Tool .... with Fail2ban.
- Block run shell in WordPress uploads folder. Block access to sensitive folders and files on WordPress.
- Anti Bruteforce wp-admin.
- Block, Unblock IP easily with Firewall management menu.
- Disable User API - /wp-json/wp/v2/users - on WordPress to avoid revealing User information.
- Change SSH Port to avoid SSH scanning.
- Allow to change Admin port.
- Allow to change SSH/SFTP port.
- Automatically generate strong passwords.
- Scan Malware with Clamav, ImunifyAV.
- And More...

### 1.4. Manage WordPress
- Check the WordPress version in use.
- Update WordPress.
- Update plugins.
- Database optimization.
- Repair Database.
- Backup data (Local/GG Drive).
- Data recovery (Local/GG Drive).
- Change domain name.
- Change admin password (wp-admin).
- Automatic WordPress installation.
- Enable/disable Yoast Seo config.
- Enable/Disable Rank Math Seo config.
- Configure Nginx with some popular cache plugins: WP-Rocket, w3 total cache, wp supercache, Cache Enabler, Swift Performance, Fast cache.
- Add cache key to avoid duplicate content between sites when using memcached or redis.
- Enable/disable Debug.
- Enable/disable maintenance mode.
- Enable/Disable disable xmlrpc (Default will disable xmlrpc to avoid DDOS exploit).
- Deactivate all plugins.
- Random database prefix when using automatic installation function.
- And more...

### 1.5. Backup/Restore data
- Backup and restore data from Google Drive with Rclone.
- Backup, restore at Local.
- Set the number of archived backups.
- Manage backups.
- Allows connecting multiple Google Drive accounts.

## 2. Request
- VPS at least 512MB ram and have not installed any services.
- Ubuntu 18.04, 20.04.

## 3. How to install
`curl -sO https://pa.mykteam.com/step1 && chmod +x step1 && ./step1`

## 6. Software download source
- Nginx: http://nginx.org/en/download.html
- MariaDB: https://downloads.mariadb.org/
- PHP: https://www.php.net/
- phpMyAdmin: https://www.phpmyadmin.net/
- PHPMemcachedAdmin: https://github.com/elijaa/phpmemcachedadmin
- phpRedisAdmin: https://github.com/erikdubbelboer/phpRedisAdmin
- Rclone: https://rclone.org/
- WP-CLI: https://wp-cli.org/
- Composer: https://getcomposer.org/
- ClamAV: https://www.clamav.net/
- ImunifyAV: https://www.imunify360.com/antivirus
- CSF: https://configserver.com/

## 7. Contact
- Homepage: https://mykteam.com
- Facebook: https://www.facebook.com/mykitteam
- Email: admin@mykteam.com

## 8. Contributors & Credits
Thanks to Sanvv and Hostvn for developing the original script. I only custom for personal use and friends. Not for commercial use
