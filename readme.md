# How 

1. make sure you have nodejs and npm installed
2. `npm init directus-project <directory>` <-- flow the wizard
3. `npx directus bootstrap` <- in case you need demo tables and boilerplate


# Running

1. `npx directus start`

Default User: 
admin@example.com
Xjv2XCKnxwXV


# Project Settings

you can visit the following route `/admin/settings/project` to change the following settings

1. Project Name 
2. Project Description
3. Project URL 
4. Default Language
5. Brandings and Styling 
6. Custom CSS via Code 
7. Change Order/Location of pages on dashboard
8. Security 
9. Files and Storage
10. Mappings for access tokens
11. Image Editor Settings

you can visit `/admin/settings/data-model` to manage the collections / tables
you can visit `/admin/settings/roles` to manage the user roles 
you can visit `/admin/settings/presets` to manage the bookmarks
you can visit `/admin/settings/translations` to manage custom translations
you can visit `/admin/settings/webhooks` to manage the webhooks
you can visit `/admin/settings/flows` to manage the flows
you can visit `/admin/insights` to manage the insights and analytics
you can visit `/admin/files` to manage the files 
you can visit `/admin/users` to manage the users
you can visit `/admin/content` to manage the database/tables


# Migrations

```bash
npx directus database migrate:latest
npx directus database migrate:up
npx directus database migrate:down
```

Database install 
```
npx directus database install
```


more at: https://docs.directus.io/self-hosted/cli.html 


# Programmatical Customization

https://docs.directus.io/extensions/introduction.html 