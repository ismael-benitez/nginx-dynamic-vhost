Automatic generation of vhosts with subdomains for Nginx
===================

Are you tired of creating a new site-avaible configuration file in your nginx server every time you lanch a new PHP project?

With this template, you only need to enable the default site-avaible configuration and set a local domain one only time.

For example, if your local domain is **domain.local** and you host three projects in **/var/www/**, automatically it sets three new virtual hosts with a dinamic subdomian based in domain.local and in the folder name of each project. So, every project would have the next domain: 

- **Path:** /var/www/project1 --> **Url:** project1.domain.local
- **Path:** /var/www/project2 --> **Url:** project2.domain.local
- **Path:** /var/www/project3 --> **Url:** project3.domain.local

And the files or subfolders:

- **Path:** /var/www/project1/index.html   --> **Url:** project1.domain.local/index.html
- **Path:** /var/www/project3/css/main.css --> **Url:** project3.domain.local/css/main.css


Nice!

