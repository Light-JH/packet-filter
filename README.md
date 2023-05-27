# packet-filter

* `index.html` - A simple web-page to be served using Apache2
    - Expected to be located at `/var/www/test/html/index.html`
* `ports.conf` - Ports to serve for Apache2
    - Expected to be located at `/etc/apache2/ports.conf`
* `rc.sh` - A shell script used to set up linux ip tables. Run to setup packet filter firewall.
* `test-and-demo.conf` - Configuration for Apache2 web service
    - Expected to be located at `/etc/apaceh2/sites-available/test-and-demo.conf`
    - Added to service by running `$ as2ensite test-and-demo`. The service can be relaunched by running `$ systemctl restart apache2.service`
