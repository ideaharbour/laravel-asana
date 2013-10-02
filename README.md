laravel-asana
=============

A wrapper for [ajimix's asana-api](https://github.com/ajimix/asana-api-php-class) for use with laravel.

#Usage

As per normal laravel package usage, you'd do something like 

<pre><code>/* retrieve all asana projects */
$asana = new Smo\Asana\Asana('apikey');
$asana->getProjects();
</code></pre>

##Notes

This wrapper was created in much haste, will be updated for use with a Facade for ease of use.

