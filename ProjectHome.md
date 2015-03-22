## General purpose Amateur Radio logging application, written in Gambas2. ##

This is a simple Ham Radio Logbook, which can import and export ADIF files, show maps based in cluster activity and Maidenhead Locators, show statistics, print labels and QSLs, access to QRZ.com XML subscription, and to the new **free** callsign database [HamQTH](http://www.hamqth.com), etc.

  * Please, check the latest [ChangeLog](http://code.google.com/p/dfhlog/source/browse/branches/dfhlog1.1/CHANGELOG). Current version is 1.1.0.

If you are an Ubuntu user, you can add a repository to install the latest dfhlog:

`sudo add-apt-repository ppa:jguardon/dfhlog`

which also imports the signatures.

Or alternatively add this line to your sources.list:

`deb http://ppa.launchpad.net/jguardon/dfhlog/ubuntu YOUR_UBUNTU_VERSION_HERE main`

...and then update your repositories.


---


If you get an ugly interface like [this](http://dl.dropbox.com/u/12230896/ugly_dfhlog.png) you probably need to install some missing libraries in your system. This is the case in Debian, so it is easy to fix:
```
$ su
# apt-get install polymer qt3-qtconfig
```

Now open the config tool by typing "qtconfig" (or "qtconfig-qt3") in your terminal and select "Polymer" as your theme and choose an appropriate font and size.

Also you may need to install some optional packages, like xplanet, portmap and hamlib-utils. Look for similar names in your specific distribution's repositories.

`('portmap' allows RPC connectivity along hamlib and fldigi. hamlib must be >= 1.2.8)`



---


![http://ea7dfh.com/imagenes/dfhlog.jpg](http://ea7dfh.com/imagenes/dfhlog.jpg)
General view, showing DXCC resolution and HamQTH lookup.

![http://ea7dfh.com/imagenes/dfhlog1.jpg](http://ea7dfh.com/imagenes/dfhlog1.jpg)
Callbook settings.

![http://ea7dfh.com/imagenes/dfhlog2.jpg](http://ea7dfh.com/imagenes/dfhlog2.jpg)
Grid map showing worked ones.

![http://ea7dfh.com/imagenes/dfhlog3.jpg](http://ea7dfh.com/imagenes/dfhlog3.jpg)
Search form in action.