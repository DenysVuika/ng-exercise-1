# Angular Exercise 1

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.3.

## Tasks

### Part 1

- have a quick overview of the project structure
- start the application
- integrate [Angular Material](https://material.angular.io/) components with the project
- integrate [Material Theming](https://material.angular.io/guide/theming#using-a-pre-built-theme) for the components
- integrate the [Toolbar](https://material.angular.io/components/toolbar/overview) component to the app home page
- integrate the [Tabs](https://material.angular.io/components/tabs/overview) component that takes the whole space on the page

### Part 2

- add a new [Button](https://material.angular.io/components/button/overview) to the application toolbar, with the `Notify` caption and `Send Notification` [Tooltip](https://material.angular.io/components/tooltip/overview)
- introduce a new Angular service `NotificationService` as `src/app/services/notification.service.ts`
- provide a public method to display a simple [Snackbar](https://material.angular.io/components/snack-bar/overview) with the provided message
- inject the `NotificationService` into the main application component
- for the click handler of the `Notify` button, invoke your custom `NotificationService` to display the notification message.

### Part 3

- run application unit tests
- create a unit test for the `NotificationService` to cover the sending messages functionality

## Resources

### Development server

Run `npm start` for a dev server, it will automatically navigate to `http://localhost:4200/`.
The application will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
