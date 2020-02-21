APM
===

This project was generated with [Angular
CLI](https://github.com/angular/angular-cli) version 8.1.2.

Development server
------------------

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app
will automatically reload if you change any of the source files.

Code scaffolding
----------------

Run `ng generate component component-name` to generate a new component. You can
also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

Build
-----

Run `ng build` to build the project. The build artifacts will be stored in the
`dist/` directory. Use the `--prod` flag for a production build.

Running unit tests
------------------

Run `ng test` to execute the unit tests via
[Karma](https://karma-runner.github.io).

Running end-to-end tests
------------------------

Run `ng e2e` to execute the end-to-end tests via
[Protractor](http://www.protractortest.org/).

Further help
------------

To get more help on the Angular CLI use `ng help` or go check out the [Angular
CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

**01-Introduction**

**Anatomy of an Angular Application**

In Angular, an application is comprised of a set of components and services that
provide functionality across those components. So, what is an Angular component?
Each component is comprised of a template, which is the HTML for the user
interface fragment defining a view for the application. Add to that a class for
the code associated with the view. The class contains the properties or data
elements available for use in the view, and methods which perform actions for
the view such as responding to a button click. A component also has metadata,
which provides additional information about the component to Angular. It is this
metadata that identifies the class as an Angular component. *So a component is a
view defined with a template, its associated code defined with a class, and
additional information defined with metadata.* As we build these components, how
do we pull them together into an application? We define Angular modules.
*Angular modules help us organize our application into cohesive blocks of
functionality. Every Angular application has at least one Angular module called
the application's root Angular module*. An application can have any number of
additional Angular modules, including feature modules that consolidate the
components for a specific application feature.
