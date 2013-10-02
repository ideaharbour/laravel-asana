laravel-asana
=============

A wrapper for [ajimix's asana-api](https://github.com/ajimix/asana-api-php-class) for use with laravel.

#Usage

As per normal laravel package usage, you'd do something like 

<code>$asana = new Smo\Asana\Asana('apikey');
$asana->getProjects() // retrieves all the projects for your asana api key</code>

##Notes

This wrapper was created in much haste, will be updated for use with a Facade for ease of use.

