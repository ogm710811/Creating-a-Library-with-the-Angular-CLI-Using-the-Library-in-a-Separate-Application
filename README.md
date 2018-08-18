# Example Angular 6 Library App Part 2 Repository

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Project Description

Now that we know how to build and package an Angular library, let’s create another test workspace so we can see what it looks like for people to actually use the library in their own application.

## Project WorkSpace

Create a test workspace so you can use the library in that application.

## Using the Library in a Separate Application

To use the library in the new application >>> npm install ../example-ng6-lib/dist/example-ng6-lib/example-ng6-lib-0.0.1.tgz

## Tips

1. ALWAYS: Install the library’s .tgz package and NOT the directory.
2. In order to actually use a component from the library we need to add the library’s module to our App Module. To do this we make two changes in: src\app\app.module.ts
   2.1. Import the ExampleNg6LibModule >>> import { ExampleNg6LibModule } from 'example-ng6-lib';
   2.2. Add the ExampleNg6LibModule to the imports array in our AppModule.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
