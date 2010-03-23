Requirements:
-----------------------------------------------------------------------------
- jekyll (0.5.7)
- compass (0.10.0.rc1)


Develop:
-----------------------------------------------------------------------------
Jekyll is responsible for building the site, the current target is the _site
directory. To get jekyll to auto update the site on your local machine run:

  jekyll --auto --server

Compass is there for the stylesheets, the current target is the stylesheets 
directory. For compass to keep the stylesheets updated run:

  compass --watch

