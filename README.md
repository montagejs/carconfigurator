Car Configurator
================

> Note that this code has not been updated to reflect the most recent changes in MontageJS. Although you will be able to run the application, it may not look or behave as intended.

[Live Demo](http://montagejs.org/apps/carconfigurator/)

The Car Configurator demo showcases an early implementation of the Montage 3D view component and its integration with the rest of a Montage application.

##Installation

To run the Car Configurator demo locally, you must have Node.js and npm installed. MontageJS application development depends on npm, the Node package manager, which is distributed with Node.js. If you haven't done so already, be sure to [download](http://nodejs.org/download/) and run the prebuilt Node.js installer for your platform from the Node.js website. Then follow these steps:

1. Clone the [carconfigurator repo](https://github.com/montagejs/carconfigurator) in your desktop.

2. Use your command line tool to navigate to the cloned directory and then install the modules required to run the demo:
        
   ```
   cd carconfigurator
   npm update
   ```
    
3. Spin up your preferred HTTP server and point your browser to the associated port.

    > During development MontageJS applications rely on XHR to load their various components and modules, which is why you will need a web server to serve the demo.
    > If you happen to have [minit](https://github.com/montagejs/minit), the Montage Initializer, installed (`npm install minit -g`) you can run `minit serve` from within the demo directory to set up a server on demand.


## Application Structure

Folder / File | Description |
------------ | ------------- 
assets | Contains global styles and images for the application.
node_modules | Contains the packages required to run the demo.
index.html | Is the entry-point HTML document.
LICENSE.md | Contains copyright information.
package.json | Describes your app and its dependencies.
README.md | Provides information about the demo application and how to install it.
ui | Contains the user interface components of the demo application.

## Contact Us

Got questions? Join us on [irc.freenode.net#montage](http://webchat.freenode.net/?channels=montage).

Got feedback or want to report a bug? Let us know by creating a new [GitHub issue](https://github.com/montagejs/carconfigurator).

## Credit

This demo application was created by [MontageJS](http://montagejs.org).

