# Installation

````
gem install shopify_theme
````

# Usage

Generate the config file. Go get a valid api_key and password for your store head to https://[your store].myshopify.com/admin/api and generate a private application. 

````
theme configure api_key password store_url
````

Download all the theme files

````
theme download
````

Upload a theme file

````
theme upload assets/layout.liquid
````

Remove a theme file

````
theme remove assets/layout.liquid
````

Completely replace shop theme assets with the local assets

````
theme replace
````

Watch the theme directory and upload any files as they change

````
theme watch
````
