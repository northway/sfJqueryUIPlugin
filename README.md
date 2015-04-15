# sfJqueryUIPlugin
jQuery UI plugin for Symfony 1.4

Contains:
 - jQuery UI 1.11.4 compressed with all optional components

##  Git

Git submodule add:

	$ git submodule add https://github.com/northway/sfJqueryUIPlugin.git plugins/sfJqueryUIPlugin

Git submodule update:

	$ git submodule update --remote

## Install

You need to add this line to ProjectConfiguration.class.php:

    $this->enablePlugins('sfJqueryUIPlugin');

Then a Symfony cache clear:

		$ php symfony cc

## Usage

  view.yml

    default:
      stylesheets:
        - /sfJqueryUIPlugin/css/jquery-ui.min.css
      javascripts:
        - /sfJqueryUIPlugin/js/jquery-ui.min.js

If you run into some error, check symfony logs and script logs.

If you think you can improve this plugin or found some error, feel free to fork and create a pull request.