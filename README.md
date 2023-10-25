# ProductsUp
After unzipping the folder run the following commands
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

# Sidebar Component

## Location
`src/app/sidebar/`

## Purpose

The Sidebar Component provides a user interface for filtering data in the table component.

## Usage

To use the Sidebar Component, include it in your application's HTML templates using the following tag:

```html
<app-sidebar (filterApplied)="applyFilter($event)"></app-sidebar>


The (filterApplied) event is emitted when a filter is applied in the Sidebar Component. You should handle this event in your parent component (e.g., the component that uses the TableComponent) to update the data based on the applied filter.

Dependencies
No external dependencies are required to use the Sidebar Component

# Table Component

## Location
`src/app/table/`

## Purpose

The Table Component is responsible for rendering and managing tabular data in your Angular application. It provides features for sorting, paginating, and filtering data.

## Usage

To use the Table Component, include it in your application's HTML templates using the following tag:

```html
<app-table></app-table>

Dependencies
The Table Component depends on Angular core and RxJS for data manipulation and rendering.

