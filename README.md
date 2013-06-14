# Shell Scripts
============

Various useful shell scripts.

## Scripts
### /CreatingNewSite/create-new-site.sh - Script for Bitnami that allows users to create a new apache site based on a template. Specificlaly, the script will copy a directory from "/opt/bitnami/apps/template" into another directory of your choosing (based on site_name param). It will then re-configure the app.conf accordingly (based on site_name, site_domain, and test_domain).

Look inside of the create-new-site.sh for common vars set including: 
app_dir="/opt/bitnami/apps"
apache_conf_dir="/opt/bitnami/apache2/conf"
apache_conf_file="httpd.conf"
bitnami_user="bitnami"
daemon_user="daemon"


    $ Usage: ./create-new-site.sh site_name site_domain test_domain



Contact
-------
Follow Vladimir Collak on Twitter @vcollak


License
-------

Copyright (c) 2013 Vladimir Collak

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
the documentation of any redistributions of the template files themselves
(but not in projects built using the templates).

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.



