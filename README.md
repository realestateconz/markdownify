Markdownify
===========

## Getting Started ##

The easiest way to work with Markdownify is when it's installed as a
Composer package inside your project. 

If you're not familiar with Composer, please see <http://getcomposer.org/>.

1. Add realestateconz/markdownify to your application's composer.json.

        {
            ...
            "require": {
                "realestateconz/markdownify": "dev-master"
            },
            ...
        }

2. Run `composer install`.

3. If you haven't already, add the Composer autoload to your project's
   initialization file. (example)

        require 'vendor/autoload.php';
