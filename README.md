Este solo es el rsc de una sitema mas grande, esta es la distribucion de archivos

ESTRUCTURA DE CARPETAS Y ARCHIVOS:

|-- src/
|   |-- app/
|   |   |-- components/
|   |   |   |-- mathew-anderson/
|   |   |   |   |-- mathew-anderson.component.html
|   |   |   |   +-- mathew-anderson.component.ts
|   |   |   |-- monthly-earnings/
|   |   |   |   |-- monthly-earnings.component.html
|   |   |   |   +-- monthly-earnings.component.ts
|   |   |   |-- recent-transactions/
|   |   |   |   |-- recent-transactions.component.html
|   |   |   |   +-- recent-transactions.component.ts
|   |   |   |-- revenue-updates/
|   |   |   |   |-- revenue-updates.component.html
|   |   |   |   +-- revenue-updates.component.ts
|   |   |   |-- top-cards/
|   |   |   |   |-- top-cards.component.html
|   |   |   |   +-- top-cards.component.ts
|   |   |   |-- top-projects/
|   |   |   |   |-- top-projects.component.html
|   |   |   |   +-- top-projects.component.ts
|   |   |   +-- yearly-breakup/
|   |   |       |-- yearly-breakup.component.html
|   |   |       +-- yearly-breakup.component.ts
|   |   |-- layouts/
|   |   |   |-- blank/
|   |   |   |   |-- blank.component.html
|   |   |   |   +-- blank.component.ts
|   |   |   +-- full/
|   |   |       |-- header/
|   |   |       |   |-- header.component.html
|   |   |       |   +-- header.component.ts
|   |   |       |-- sidebar/
|   |   |       |   |-- nav-item/
|   |   |       |   |-- branding.component.ts
|   |   |       |   |-- sidebar.component.html
|   |   |       |   |-- sidebar.component.ts
|   |   |       |   +-- sidebar-data.ts
|   |   |       |-- full.component.html
|   |   |       +-- full.component.ts
|   |   |-- pages/
|   |   |   |-- authentication/
|   |   |   |   |-- side-login/
|   |   |   |   |   |-- side-login.component.html
|   |   |   |   |   +-- side-login.component.ts
|   |   |   |   |-- side-register/
|   |   |   |   |   |-- side-register.component.html
|   |   |   |   |   +-- side-register.component.ts
|   |   |   |   +-- authentication.routes.ts
|   |   |   |-- extra/
|   |   |   |   |-- icons/
|   |   |   |   |   |-- icons.component.html
|   |   |   |   |   +-- icons.component.ts
|   |   |   |   |-- sample-page/
|   |   |   |   |   |-- sample-page.component.html
|   |   |   |   |   +-- sample-page.component.ts
|   |   |   |   +-- extra.routes.ts
|   |   |   |-- mapa-territorial/
|   |   |   |   |-- components/
|   |   |   |   |   |-- anotacion-detalle/
|   |   |   |   |   +-- filtros-panel/
|   |   |   |   |-- models/
|   |   |   |   |   |-- annotation.model.ts
|   |   |   |   |   |-- annotation-category.model.ts
|   |   |   |   |   +-- category.model.ts
|   |   |   |   |-- services/
|   |   |   |   |   |-- annotation-categories.service.spec.ts
|   |   |   |   |   |-- annotation-categories.service.ts
|   |   |   |   |   |-- annotations.service.spec.ts
|   |   |   |   |   |-- annotations.service.ts
|   |   |   |   |   |-- categories.service.spec.ts
|   |   |   |   |   +-- categories.service.ts
|   |   |   |   |-- mapa-territorial.component.html
|   |   |   |   |-- mapa-territorial.component.scss
|   |   |   |   |-- mapa-territorial.component.spec.ts
|   |   |   |   |-- mapa-territorial.component.ts
|   |   |   |   +-- mapa-territorial.routes.ts
|   |   |   |-- starter/
|   |   |   |   |-- starter.component.html
|   |   |   |   +-- starter.component.ts
|   |   |   |-- ui-components/
|   |   |   |   |-- badge/
|   |   |   |   |   |-- badge.component.html
|   |   |   |   |   +-- badge.component.ts
|   |   |   |   |-- chips/
|   |   |   |   |   |-- chips.component.html
|   |   |   |   |   |-- chips.component.scss
|   |   |   |   |   +-- chips.component.ts
|   |   |   |   |-- forms/
|   |   |   |   |   |-- forms.component.html
|   |   |   |   |   +-- forms.component.ts
|   |   |   |   |-- lists/
|   |   |   |   |   |-- lists.component.html
|   |   |   |   |   +-- lists.component.ts
|   |   |   |   |-- menu/
|   |   |   |   |   |-- menu.component.html
|   |   |   |   |   +-- menu.component.ts
|   |   |   |   |-- tables/
|   |   |   |   |   |-- tables.component.html
|   |   |   |   |   +-- tables.component.ts
|   |   |   |   |-- tooltips/
|   |   |   |   |   |-- tooltips.component.html
|   |   |   |   |   +-- tooltips.component.ts
|   |   |   |   +-- ui-components.routes.ts
|   |   |   |-- users/
|   |   |   |   |-- list/
|   |   |   |   |   |-- list.component.html
|   |   |   |   |   |-- list.component.scss
|   |   |   |   |   |-- list.component.spec.ts
|   |   |   |   |   +-- list.component.ts
|   |   |   |   +-- users.routes.ts
|   |   |   +-- pages.routes.ts
|   |   |-- pipe/
|   |   |   +-- filter.pipe.ts
|   |   |-- services/
|   |   |   |-- core.service.ts
|   |   |   +-- nav.service.ts
|   |   |-- app.component.html
|   |   |-- app.component.spec.ts
|   |   |-- app.component.ts
|   |   |-- app.config.ts
|   |   |-- app.routes.ts
|   |   |-- config.ts
|   |   +-- material.module.ts
|   |-- assets/
|   |   |-- i18n/
|   |   |   |-- de.json
|   |   |   |-- en.json
|   |   |   |-- es.json
|   |   |   +-- fr.json
|   |   |-- images/
|   |   |   |-- backgrounds/
|   |   |   |   |-- bronze.png
|   |   |   |   |-- customer-support-img.png
|   |   |   |   |-- error404page.gif
|   |   |   |   |-- gold.png
|   |   |   |   |-- laptop-desk.webp
|   |   |   |   |-- login-bg.svg
|   |   |   |   |-- maintenance.gif
|   |   |   |   |-- onlinedoctor.gif
|   |   |   |   |-- piggy.png
|   |   |   |   |-- profilebg.jpg
|   |   |   |   |-- rocket.png
|   |   |   |   |-- silver.png
|   |   |   |   +-- welcome-bg2.png
|   |   |   |-- breadcrumb/
|   |   |   |   |-- ChatBc.png
|   |   |   |   +-- emailSv.png
|   |   |   |-- flag/
|   |   |   |   |-- icon-flag-de.svg
|   |   |   |   |-- icon-flag-en.svg
|   |   |   |   |-- icon-flag-es.svg
|   |   |   |   +-- icon-flag-fr.svg
|   |   |   |-- logos/
|   |   |   |   |-- dark-logo.svg
|   |   |   |   +-- light-logo.svg
|   |   |   |-- products/
|   |   |   |   |-- product-1.jpg
|   |   |   |   |-- product-2.jpg
|   |   |   |   |-- product-3.jpg
|   |   |   |   +-- product-4.jpg
|   |   |   |-- profile/
|   |   |   |   |-- user-1.jpg
|   |   |   |   |-- user-10.jpg
|   |   |   |   |-- user-11.jpg
|   |   |   |   |-- user-12.jpg
|   |   |   |   |-- user-2.jpg
|   |   |   |   |-- user-3.jpg
|   |   |   |   |-- user-4.jpg
|   |   |   |   |-- user-5.jpg
|   |   |   |   |-- user-6.jpg
|   |   |   |   |-- user-7.jpg
|   |   |   |   |-- user-8.jpg
|   |   |   |   +-- user-9.jpg
|   |   |   +-- svgs/
|   |   |       |-- facebook-icon.svg
|   |   |       |-- github-icon.svg
|   |   |       |-- google-icon.svg
|   |   |       |-- icon-account.svg
|   |   |       |-- icon-briefcase.svg
|   |   |       |-- icon-connect.svg
|   |   |       |-- icon-dd-application.svg
|   |   |       |-- icon-dd-cart.svg
|   |   |       |-- icon-dd-chat.svg
|   |   |       |-- icon-dd-date.svg
|   |   |       |-- icon-dd-invoice.svg
|   |   |       |-- icon-dd-lifebuoy.svg
|   |   |       |-- icon-dd-message-box.svg
|   |   |       |-- icon-dd-mobile.svg
|   |   |       |-- icon-favorites.svg
|   |   |       |-- icon-inbox.svg
|   |   |       |-- icon-mailbox.svg
|   |   |       |-- icon-master-card.svg
|   |   |       |-- icon-master-card-2.svg
|   |   |       |-- icon-nextjs.svg
|   |   |       |-- icon-office-bag.svg
|   |   |       |-- icon-office-bag-2.svg
|   |   |       |-- icon-paypal.svg
|   |   |       |-- icon-pie.svg
|   |   |       |-- icon-react.svg
|   |   |       |-- icon-speech-bubble.svg
|   |   |       |-- icon-tailwind.svg
|   |   |       |-- icon-tasks.svg
|   |   |       |-- icon-typescript.svg
|   |   |       |-- icon-user-male.svg
|   |   |       |-- mastercard.svg
|   |   |       +-- paypal.svg
|   |   |-- scss/
|   |   |   |-- dark/
|   |   |   |   +-- _dark.scss
|   |   |   |-- layouts/
|   |   |   |   |-- _header.scss
|   |   |   |   |-- _layouts.scss
|   |   |   |   |-- _sidebar.scss
|   |   |   |   +-- _transitions.scss
|   |   |   |-- override-component/
|   |   |   |   |-- _autocomplete.scss
|   |   |   |   |-- _badge.scss
|   |   |   |   |-- _button.scss
|   |   |   |   |-- _button-toggle.scss
|   |   |   |   |-- _card.scss
|   |   |   |   |-- _checkbox.scss
|   |   |   |   |-- _chip.scss
|   |   |   |   |-- _datepicker.scss
|   |   |   |   |-- _dialog.scss
|   |   |   |   |-- _drawer.scss
|   |   |   |   |-- _expansion.scss
|   |   |   |   |-- _fab.scss
|   |   |   |   |-- _form-field.scss
|   |   |   |   |-- _index.scss
|   |   |   |   |-- _list.scss
|   |   |   |   |-- _menu.scss
|   |   |   |   |-- _paginator.scss
|   |   |   |   |-- _progress.scss
|   |   |   |   |-- _radio.scss
|   |   |   |   |-- _stepper.scss
|   |   |   |   |-- _table.scss
|   |   |   |   |-- _theme.scss
|   |   |   |   |-- _tree.scss
|   |   |   |   +-- _typography.scss
|   |   |   |-- pages/
|   |   |   |   |-- _auth.scss
|   |   |   |   +-- _dashboards.scss
|   |   |   |-- themecolors/
|   |   |   |   |-- _aqua_theme.scss
|   |   |   |   |-- _blue_theme.scss
|   |   |   |   |-- _cyan_theme.scss
|   |   |   |   |-- _green_theme.scss
|   |   |   |   |-- _orange_theme.scss
|   |   |   |   +-- _purple_theme.scss
|   |   |   |-- theme-variables/
|   |   |   |   |-- _dark-theme-variables.scss
|   |   |   |   |-- _default-variables.scss
|   |   |   |   +-- _light-theme-variables.scss
|   |   |   |-- _container.scss
|   |   |   |-- _variables.scss
|   |   |   +-- style.scss
|   |   |-- .gitkeep
|   |   |-- marker-icon.png
|   |   |-- marker-icon-2x.png
|   |   +-- marker-shadow.png
|   |-- environments/
|   |   |-- environment.prod.ts
|   |   +-- environment.ts
|   |-- favicon.ico
|   |-- globals.css
|   |-- index.html
|   |-- main.ts
|   +-- styles.scss
|-- .editorconfig
|-- .gitignore
|-- .npmrc
|-- .postcssrc.json
|-- angular.json
|-- netlify.toml
|-- package.json
|-- package-lock.json
|-- project-structure.js
|-- project-structure.ps1
|-- README.md
|-- run-structure.bat
|-- STRUCTURE-SCRIPT-README.md
|-- tsconfig.app.json
|-- tsconfig.json
+-- tsconfig.spec.json
