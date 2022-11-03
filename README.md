Redirect
======================

**Important note**: Redirect module was moved into Backdrop core in version 
1.4.0. Use of this module is no longer necessary and no further changes will be 
made here. If you would like to report a bug or feature request against Redirect 
module, file an issue in the main Backdrop CMS core repository at https://github.com/backdrop/backdrop-issues.

This is the new module home for a unified redirection API (also replaces
path_redirect and globalredirect).

Requirements
------------

This module requires that the following modules are also enabled:

* field_ui

i.  Redirect module allows you to create 301 redirects inside the Backdrop GUI.
  * for example you can tell user request to the path /old-path to return /new-path to the user.
  
Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules

- Visit the Redirect listng page under Administration > Configuration > 
    URL Handling > URL Redirects (admin/config/urls/redirect).

- When adding content to your site you will see a Redirect Vertical tab where 
    you can add a redirect to the content.

     
Current Maintainers
-------------------

  *  [Geoff St. Pierre](https://github.com/serundeputy)
  
Credits
-------

  * Dave Reid maintained for Drupal.
  
   
License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.  
