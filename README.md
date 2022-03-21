## Utah Museum of Fine Arts and Marriott Library OmekaS Theme

OmekaS is a web publication system for universities, galleries, libraries, archives, and museums. It consists of a local network of independently curated exhibits sharing a collaboratively built pool of items, media, and their metadata.

See [OmekaS Developer Documentation](https://omeka.org/s/docs/developer/), [OmekaS user manual](https://omeka.org/s/docs/user-manual), and [UMFA user documentation](https://exhibits.lib.utah.edu/s/umfa-theme/page/getting-started) for more information.


## Installing this Theme

Themes must be manually added to the themes folder of the installation, using an FTP program or an ssh connection.

To add this theme to the site using FTP

* Download the zipped theme to your computer.
* Open your FTP client, log on to the server that houses the Omeka S install and navigate to the /themes folder (this should be located in the main folder of the install).
* Upload the zipped theme to the /themes folder
* Unzip the module

## Theme Usage

The UMFA theme uses a licensed copy of the [Univers](https://www.myfonts.com/fonts/linotype/univers/) font. All hosted Univers webfont files and license scripts/keys have been removed from the public repository. 

### User Documentation

* [UMFA user documentation](https://exhibits.lib.utah.edu/s/umfa-theme/page/getting-started)

### Modifying Theme Styles

This theme uses custom styles found in `umfa-default.css`, `absolute-topNav.css`, `item-meta-layout-condensed.css`, `left-header.css`,  from `asset/css/`

* Modify desired theme style file from `asset/css/`
* Add your own custom stylesheets by appendStylesheet in the main `layout.phtml` from `view/layout/` and create a new css file in `asset/css/`

## Libraries

The UMFA Theme uses the following libraries:

* [Font Awesome](https://fontawesome.com/)
* [Bootstrap Grid](https://getbootstrap.com/docs/4.0/layout/grid/)


Omeka uses the following libraries, among others:

* [Zend Framework 3](http://framework.zend.com/)
* [Doctrine 2](http://www.doctrine-project.org/)
* [EasyRdf](http://www.easyrdf.org/)
* [PHPUnit](https://phpunit.de/)
* [jQuery](http://jquery.com/)

## Coding Standards

Omeka development adheres to the [Zend Framework 2 Coding Standards](https://zf2-docs.readthedocs.org/en/latest/ref/coding.standard.html)
and uses the [git-flow](http://nvie.com/posts/a-successful-git-branching-model/) branching model.
