oioswift
========

OpenIO SDS Swift Gateway.

Features
--------
Included:
*   Basic operations on objects and containers
*   Authentication support
*   Metadata support
*   Swift Middleware support
*   Partial account support

Installation
------------

If you want to work with the current development version you can:

You can install directly from trunk on GitHub:

    pip install git+git://github.com/open-io/oio-swift.git

Download and install from source by running:

    python setup.py install
    
Updates
-------

From GitHub:

    pip install --upgrade git+git://github.com/open-io/oio-swift.git
    
Configuration
-------------

The SDS Swift Gateway uses the OpenStack Swift Proxy.

There is a sample configuration in `conf/default.cfg`.

Configuration items:
*   `sds_namespace` - the SDS Namespace to serve. Example: `NS`
*   `sds_proxy_url` - the URL of the SDS proxy. Example: `http://127.0.0.1:6000`
    
Run
---
        
Use the proxy-server launch script from Swift. 

Alternatively you can simply use:
    
    # for development only
    python runserver.py
    

Links
-----
Resources:
*   [OpenIO SDS](https://github.com/open-io/oio-sds)
*   [OpenIO SDS Python API](https://github.com/open-io/oiopy)
*   [OpenStack Swift API](http://developer.openstack.org/api-ref-objectstorage-v1.html)


    
