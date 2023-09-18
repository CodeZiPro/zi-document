#ZiDocument
ZiDocument is a web-based document management system, built using the latest version of the Laravel (10.x) , designed to help organizations, companies, and teams store, track, modify, and manage Document management on a centralized platform.

Its features include: Post documents, share documents, manage personal documents, shared documents,... user management, batch document authorization, download documents, Preview documents, view online DOC, EXCEL, PDF, PPT files... support sending documents via email, comment on documents and multi-language support.

It allows you to upload multiple documents and share them with an unlimited number of system users. Additionally, it provides the option to share documents up to a specific time and gives optional permissions to view or edit the document.

In the future we will continuously upgrade and add many other useful features.

https://zicms.pro/doc/zi-document-introduce.faq12.html?mid=9&menu=70


#Step by step setup project
#Step 1: install software
- install nginx
- install mysql
- install php8.1 and extension https://laravel.com/docs/10.x/deployment#server-requirements
- install composer

#Step2: install vendor
- composer install
- config database .env (rename [.env.example](.env.example)) to .env and change database config

#Step4: set permission folders

- chmod -R 777 storage
- chmod -R 777 bootstrap/cache
- chmod -R 777 public/assets

#Step4: run command
- php artisan zi:help (show full supported command)

#step5: setting cronjob and queue service

https://laravel.com/docs/10.x/queues#supervisor-configuration

#step6: run webserver local to test
- php artisan serve

