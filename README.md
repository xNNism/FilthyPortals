# PiPortal
### Webinterface to access serveral various control panels.

#### Installation:

1. **First you'll need to have a webserver up and running on your Pi. The following will install and setup lighttp on your Raspberry Pi.**
  
` $ sudo apt-get install lighttpd php7.0-cgi`
  
` $ sudo lighttpd-enable-mod fastcgi fastcgi-php`
  
` $ sudo service lighttpd force-reload`
  
2. **Add ip/port or the path to the index.php/index.html to the body section in the index.html.**  
  
  
3. **Clone this repo and copy the files inside somewhere your webserver can see it, i.e.:**
  
` $ cd /tmp/`
  
` $ git clone https://github.com/xNNism/Pi-Portal`
  
` $ sudo cp -r Pi-Portal/* /var/www/html/`

