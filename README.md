# HelloAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Installing bootstrap

1. Run `npm i bootstrap -S`

2. In `styles.scss`, add the line

```scss
@import "~bootstrap/dist/css/bootstrap.css";
```

---

## Theming with bootstrap

1. Create `variables.scss` file in `/src` directory.

2. Make sure the `styles.scss` file contains the following imports:

```scss
@import "~bootstrap/dist/css/bootstrap.css";
@import "variables";
@import "../node_modules/bootstrap/scss/bootstrap";
```

3. To verify, add the following inside `variables.scss`:

```scss
$primary: red;
```

4. Adding a button with `btn-primary` class should display a red-button

5. To get the full list of variables, go to `../node-modules/bootstrap/scss/_variables.scss`

---
