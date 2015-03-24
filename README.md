#BUI - Beacon User Interface

To add BUI styles to your application, just link to the bui-styles.css file in. The BUI style overrides have been built on top of bootstrap 3.2.0. Bootstrap is already included in the bui-styles.css file so there is no need to include it seperatly.

## Demo
 
[http://decipherinc.github.io/bui]()

## Pre-requsits

1. You'll need [Node.js](http://nodejs.org) installed, so [download and install it](http://nodejs.org/download/).

2. If you do not have [Bower](http://bower.io/) installed, install it via `npm`:

    ```sh
    npm install -g bower
    ```

## Installation

1. To install:

    ```sh
    bower install bui
    ```

2. Add to your application:
    ```
    <link rel="stylesheet" href="bower_compenents/bui/dist/bui-styles.min.css">
    ```


### Development Installation (for Non-[FocusVision](http://www.focusvision.com) Employees)

1.  Clone

    ```sh
    $ git clone git://github.com/decipherinc/bui.git && cd bui
    ```
    
2.  Install development dependencies

    ```sh
    $ npm install
    ```
 
3.  Build the `.css` files by executing:

    ```sh
    $ grunt
    ```

4.  To automatically compile `.less` files as you work, execute:

    ```sh
    $ grunt watch:main
    ```

## Notes

TDB
    
## Copyright

2014-2015 FocusVision Worldwide

## License

MIT

## Author

[Dick DeLeon](https://github.com/dickdeleon)
[Dan Mendoza](https://github.com/decipherdan)
