# Dashboard Sample

This is a showcase [CUBA](https://www.cuba-platform.com/) application which demonstrates how to customize system screens using CssLayout.

The application has fully customized dashboard which uses `CssLayout` with [Vaadin responsive extention](https://vaadin.com/wiki/-/wiki/Main/Responsive+layouts+using+the+Responsive+extension).

* The `ExtAppMainWindow` controller extends the `AppMainWindow` controller defined in the platform.
* The `BootstrapListener` class extends the `CubaBootstrapListener` to add `viewport` metatag with `device-width` option.
* The `ext-mainwindow.xml` screen extends the `mainwindow.xml` screen defined in the platform.
* Additional CSS rules for the dashboard are defined in `dashboard.scss` file.

To see the example in action, do the following:

* Open the project in Studio
* Click *Run > Start application server*
* If you see the warning *Database does not exist ...*, click *Create DB in background*
* Go to `http://localhost:8080/app` and log in as `admin` / `admin`

You can see this demo in action at [www.cuba-platform.com](https://demo.cuba-platform.com/dashboard/).

Based on CUBA Platform 6.1.5