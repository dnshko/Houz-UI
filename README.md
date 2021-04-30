# Houz-UI

### Setup:

```sh
npm init

npm install node-sass --save-dev
```

#### Frontend Development Workflow
```sh
npm run compile:sass
```

#### Folder Structure
```
📦sass
 ┣ 📂abstracts
 ┃ ┣ 📜_functions.scss
 ┃ ┣ 📜_mixins.scss
 ┃ ┗ 📜_variables.scss
 ┣ 📂base
 ┃ ┣ 📜_animation.scss
 ┃ ┣ 📜_base.scss
 ┃ ┣ 📜_typography.scss
 ┃ ┗ 📜_utilities.scss
 ┣ 📂components
 ┃ ┣ 📜_breadcrumb.scss
 ┃ ┣ 📜_buttons.scss
 ┃ ┗ 📜_tabs.scss
 ┣ 📂layout
 ┃ ┣ 📜_footer.scss
 ┃ ┣ 📜_grid.scss
 ┃ ┣ 📜_header.scss
 ┃ ┣ 📜_navigation.scss
 ┃ ┗ 📜_screen.scss
 ┣ 📂pages
 ┃ ┗ 📜_home.scss
 ┣ 📂themes
 ┃ ┗ 📜_theme.scss
 ┣ 📂vendors
 ┗ 📜main.scss              // Main Sass file
```