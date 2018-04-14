# SOGo Docker with nginx

This project results in a Docker image with SOGo service, served by a nginx proxy.

Configuration options for SOGo can be specified as environment variables:

```
    - DB_USERPROFILES=mysql://sogo:pass@db:3361/sogo/sogo_user_profile
    - DB_FOLDERINFO=mysql://sogo:pass@db:3361/sogo/sogo_folder_info
    - DB_SESSIONSFOLDER=mysql://sogo:pass@db:3361/sogo/sogo_sessions_folder
    - DB_USERVIEW=mysql://sogo:pass@db:3361/sogo/sogo_view
    - IMAP_SERVER=imaps://mail.alb-tec.de:993
    - SIEVE_SERVER=sieve://mail.alb-tec.de:4190
    - SMTP_SERVER=mail.alb-tec.de
    - MAILDOMAIN=mail.alb-tec.de
    - TITLE=alb-TEC SOGO
    - LANGUAGE=English
    - TIMEZONE=Europe/Berlin
    - SUPERUSERS=christopher.hauser@alb-tec.de
```
