# mage-mediawiki

Deploys mediawiki. Example config:

```
mediawiki:
  - root: /var/www/vhosts/labs.example.com/wiki
    uri: https://labs.example.com
    scriptpath: /wiki
    version: 1.31.0
    db_user: labs_mediawiki
    db_pass: supersecret
    db_name: labs
    admin_email: root@example.com
    admin_user: exroot
    admin_pass: megasecret
  - root: /var/www/vhosts/wiki.org
    uri: https://wiki.org
    scriptpath: /
    db_user: wikiorg
    db_pass: supersecret2
    db_name: wikiorgdb
    admin_email: root@wikiorg
    admin_user: exroot
    admin_pass: megasecret2
```

