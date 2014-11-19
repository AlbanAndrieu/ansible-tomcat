## tomcat

[![Travis CI](http://img.shields.io/travis/AlbanAndrieu/ansible-tomcat.svg?style=flat)](http://travis-ci.org/AlbanAndrieu/ansible-tomcat) [![Branch](http://img.shields.io/github/tag/AlbanAndrieu/ansible-tomcat.svg?style=flat-square)](https://github.com/AlbanAndrieu/ansible-tomcat/tree/master) [![Donate](https://img.shields.io/gratipay/AlbanAndrieu.svg?style=flat)](https://www.gratipay.com/AlbanAndrieu)  [![Platforms](http://img.shields.io/badge/platforms-debian%20/%20ubuntu-lightgrey.svg?style=flat)](#)

Ensures that tomcat is properly installed (using `apt`) and configured




### Role variables

List of default variables available in the inventory:

```yaml
    # Here are variables related to the Tomcat installation
    
    tomcat_http_port: 8280
    tomcat_https_port: 8443
    
    # This will configure a default manager-gui user:
    
    tomcat_admin_username: admin
    tomcat_admin_password: microsoft
```


### Detailed usage guide

Describe how to use tomcat...


### Authors and license

`tomcat` role was written by:
- [Alban Andrieu](fr.linkedin.com/in/nabla/) | [e-mail](mailto:alban.andrieu@free.fr) | [Twitter](https://twitter.com/AlbanAndrieu) | [GitHub](https://github.com/AlbanAndrieu)
- License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/AlbanAndrieu/ansible-tomcat/issues)!

***

README generated by [Ansigenome](https://github.com/nickjj/ansigenome/).
