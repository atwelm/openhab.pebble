# OpenHAB for Pebble
An OpenHAB client for Pebble, written using the Pebble.js framework.

## Configuration
After installing the application on your Pebble via the Pebble app on your phone,
go to the Configuration screen for the app on your phone to enter the necessary
information below.

### Local URL
This is the URL that you use to contact your OpenHAB server when within your home 
network (i.e. behind your firewall).  Typically, this connection can be left 
unsecured.  On first launch, this url is set to http://demo.openhab.org:8080.

### Remote URL
This is the URL that you use to contact your OpenHAB server when you are away from
 your home, outside your firewall (i.e. from the Internet).  This connection should
 be highly secured with SSL (e.g. https://)  and authentication.  If you don't plan
 to access your server from the Internet, this field can be left blank.

### Username
If you have secured your server using authentication, enter your username here.  
Otherwise, this field can be left blank.

### Password
The password for servers using authentication, otherwise blank.

### Sitemap
If you have more than one sitemap, you can set the default one with this field.  
If you only have one sitemap, this field can be left blank, and your sitemap will
 be auto selected by the Pebble app.  If your preconfigured sitemap cannot be found,
 or if you have more than one sitemap and have not specified a default, the sitemap
 list will be shown when you launch the app.  The sitemap list can also be show by
 long pressing the SELECT button from an items page.

## History
This application was inspired by the PebbleHAB app written by Alex Bartis 
(www.alexbartis.com)
