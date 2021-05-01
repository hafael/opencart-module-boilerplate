opencart-module-boilerplate
===========================

Creates all needed files for new OpenCart 3+ module.

I mean this ones:

install.xml

upload/catalog/controller/extension/module/module_name.php 

upload/catalog/language/en-gb/extension/module/module_name.php

upload/catalog/view/theme/default/template/extension/module/module_name.twig

upload/admin/controller/extension/module/module_name.php

upload/admin/language/en-gb/extension/module/module_name.php

upload/admin/view/template/extension/module/module_name.twig

README.md

LICENSE (GNU 3)

module_name.ocmod.zip


===========================

Usage:

* Copy oc-module.php to OpenCart root folder
* execute from console 
  *  ```php-cli oc-module.php <module_name> <optional_dir_prefix>``` in linux
  *  ```php.exe oc-module.php <module_name> <optional_dir_prefix>``` in windows
* That's it.

===========================

However, be careful: this script will overwrite any existing files (if modulename clashes e.g.)
