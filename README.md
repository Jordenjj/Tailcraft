# Tailcraft
CraftCMS + Tailwind boilerplate

A pre-configured CraftCMS installation that employs TailwindCSS' CLI build process.

## Installation
- Install Composer
- Run `composer install` & `composer update`
- Since CraftCMS is pre-installed, it might not be the latest version when the repo is cloned. Use ```php craft update all``` to ensure the latest version of CraftCMS
- Run
```
npm install -D tailwindcss
npx tailwindcss init
```

- Crate database and point .env to it
- Configure webserver to /web
- Configure Craft by going to <domain.com>/admin

## Use
When building, use TailwindCSS styles in the templates, and make sure the build server is running.
