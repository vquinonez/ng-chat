# NgChat

## Project Description

### Description

This project will emulate a chat. You can add new members to the chat, and save the conversation.

## Objective

You need to create all the components using Kendo UI and expecting to reuse the components as much as posible:

- You won't use the Kendo's chat component, you need to create a new one using the kendo forms components.
- The chat window will contain a text input, a send button and a chat viewer.
- It should create a new chat window for all the users that are on the chat.
- You need to add a new user modal that will ask for a name, and a color in order to add the new chat.
- Everyone a user send a message it will appear at other windows with the color selected.
- Every message you send will appear on grey color.
- A use can close the window and a message will throw to the other users.
- When a user send one of the following words, it will be replace for `*`
    - vue
    - react
    - angularjs

## Optional

- You need to add a save button that will save the conversation history and the users involved on a API.
- When you start the application you will pull the values from a API and restored the session.

---

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
