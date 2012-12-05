# FCS SDK for PHP

The FCS SDK for PHP enables PHP developers to build solutions with Firebrand Cloud Services (FCS).
With the FCS SDK for PHP, developers can get started in minutes by using [Composer](http://getcomposer.org).

This new version is built on top of [Guzzle](http://guzzlephp.org), a PHP HTTP client
framework, which provides increased performance.  The FCS SDK for PHP requires PHP 5.3.2.

## Before Using the SDK

There is some basic information you need to know before you get started using the SDK.

### Signing Up for FCS

First your organization must be setup with Firebrand Technologies Title Management and
Content Services.

### Configuration Settings for FCS

Your FCS Configuration Settings will be sent to your organization.

## Installing the SDK

Using [Composer](http://getcomposer.org) is the recommended way to install the FCS SDK for PHP . Composer is
dependency management tool for PHP that allows you to declare the dependencies your project needs and installs them into
your project. In order to use the FCS SDK for PHP through Composer, you must do the following:

1. Add `"fcs/fcs-sdk-php"` as a dependency in your project's `composer.json` file.

    ```json
        {
            "require": {
                "fcs/fcs-sdk-php": "*"
            }
        }
    ```

1. Download and install Composer.

        curl -s "http://getcomposer.org/installer" | php

1. Install your dependencies.

        php composer.phar install

1. Require Composer's autoloader.

    Composer also prepares an autoload file that's capable of autoloading all of the classes in any of the libraries that
    it downloads. To use it, just add the following line to your code's bootstrap process.

        require '/path/to/sdk/vendor/autoload.php';

You can find out more on how to install Composer, configure autoloading, and other best-practices for defining
dependencies at [getcomposer.org](http://getcomposer.org).