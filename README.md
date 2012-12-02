DjangoPi Basic Installer
=
A one-click Django installer for Raspberry pi.

----------

This package provides an easy way for beginners to install Django on the Raspberry pi.


The Djangopi Project
=
This package is part of the larger #djangopi project - an educational website running on a Raspberry Pi.
You can find out more and contribute at:

https://sponsorcraft.com/p/djangopi

Usage
=

This setup script has been updated to work on the Raspbian release

To start:

* Start your Raspberry Pi
* Log in as ROOT - this is important
* Download this package
* Navigate to this package folder, this can be done via:


```Python
cd ~/path/to/package
```

Where path/to/package is replaced by the path. If you are unsure: ask for help or use the tab key to show a list of options.

 - Type:

```Python
sudo chmod +x setup.sh
```

to make the file executable

- This installer only takes one line of code to set up:

```Python
./setup.sh
```

NOTE: this will take a long time if you're running it on a clean install, so go grab a cup of tea!

Adding your other packages
=

You can add your own packages to the installation by typing the package name at the bottom of the requirements.txt and running setup.sh again.


Authors
=

Paul Hallett www.phalt.co.uk

Contributors
=

Ross Masters http://www.rossmasters.com

Danilo Bargen https://github.com/dbrgn
