# R shiny and electron

This is a work in progress template for RInno, shiny and electron integration.

## Quickstart

Fork this template and customize it to meet your needs.

## App

The app currently starts with a loading screen while trying to start the shiny app as a seperate process. If successful, it will switch to the shiny app once it is loaded. If not successful after 3 trys, an error is shown.

Loading:
![loading](docs/screenshot-loading.png)

App:
![app](docs/screenshot-app.png)


## References

* The initial javascript template is based on the template from `electron-forge`
* This project is an extension of the work of [@ksasso](https://github.com/ksasso/useR_electron_meet_shiny) and [@dirkschumacher](https://github.com/dirkschumacher/r-shiny-electron). RInno v1.0.0 uses [nativefier](https://github.com/jiahaog/nativefier), but this will be merged into RInno v1.1.0 in order to integrate with a more open Electron framework that is easier to customize.
