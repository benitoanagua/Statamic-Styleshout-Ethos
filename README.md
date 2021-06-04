<p align="center"><img src="https://statamic.com/assets/branding/Statamic-Logo+Wordmark-Rad.svg" width="400" alt="Statamic Logo" /></p>

## About Statamic 3

Statamic 3 is the flat-first, Laravel + Git powered CMS designed for building beautiful, easy to manage websites.

## Quick Start

**1. Create a new site** cloning the repo and removing the origin repo.

```
git clone https://github.com/benitoanagua/Statamic-Styleshout-Ethos ethos
cd ethos
composer install
cp .env.example .env && php artisan key:generate
php -S localhost:3000 -t public
```

**2. Make a new user** – you'll want it to be a `super` so you have access to everything.

```
php please make:user
```

Now heading to [localhost:3000/cp](http://localhost:3000/cp "Control Panel").

## Static site generator

```bash
composer require statamic/ssg
php please ssg:generate
```

The official Statamic 3 [static site generator package](https://github.com/statamic/ssg).

## Important Links

-   [Statamic Main Site](https://statamic.com)
-   [Statamic 3 Documentation][docs]
-   [Statamic 3 Core Package Repo][cms-repo]
-   [Statamic 3 Migrator](https://github.com/statamic/migrator)
-   [Statamic Discord][discord]

[docs]: https://statamic.dev/
[discord]: https://statamic.com/discord
[cms-repo]: https://github.com/statamic/cms
