Automatic generation of vhosts with subdomains for Nginx
===================

Are you tired of creating new site-available configuration files in your nginx server, every time you launch a new PHP project?

With this template, you only need to enable the default site-available configuration and set a local domain just once.

For example, if your local domain is **domain.local** and you host in /var/www/, it automatically sets new virtual hosts with a dynamic subdomain based in domain.local and in the folder name of each project. So, every project would have the next domain:

- **Path:** /var/www/project1 --> **Url:** project1.domain.local
- **Path:** /var/www/project2 --> **Url:** project2.domain.local
- **Path:** /var/www/project3 --> **Url:** project3.domain.local

And the files or subfolders:

- **Path:** /var/www/project1/index.html   --> **Url:** project1.domain.local/index.html
- **Path:** /var/www/project3/css/main.css --> **Url:** project3.domain.local/css/main.css


Isn’t it nice?
