# PWCI BackUp Script
Backup Script for Perfect World Classic Indonesia

# Set Default Variable
```
backup_root=/backup			                  # root directory for all backups
v=true					                  # verbose output
keep=5					                  # number of old backups to keep
hash=sha256				                  # crypto hash to use for checksums
costumfilename=PWCI                                       # backup file name
target_backup=/home                                       # backup target
target_backup2=/root                                      # backup target 2
pwlogs_folder=/home/logs                                  # pw logs folder
weblogs_folder=/var/logs/nginx                            # website logs folder
webconfigs=/etc/nginx					  # Website Configuration
webdata=/var/www					  # Website Data
mysqlconf=/etc/my.cnf.d                                   # Mysql Config
gdrive_folder=PWCI_155                                    # google drive folder ID
phpfpm=/etc/php-fpm.d				          # PHP FPM CONFIG
```

# Requirement
- Install [rclone](https://rclone.org)
- [Google Drive](https://drive.google.com/) Account
