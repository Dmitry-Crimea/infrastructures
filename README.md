## **Ansible роль по установке инфраструктуры проекта:**

+ __Postgres 13__
    + hstore
    + pg_trgm
+ __Python 3.9__
    + Пакетный менеджер Python - pipenv
    +  Django 3.2.5
    +  DRF 3.12.4
+ __NGINX__
+ __Let`s Encrypt__

>В ***inventories/dev/group_vars/all/vars.yml***  
можно менять следующие строки с переменными:
```YAML
domain_name: eco.sarawan.ru # для домена

project_email: info@sarawan.ru # для получения сертификат SSL
```
