# service-virtualization-ui
UI of Service Virtualization.

## Configuration
contextpath is derived from the url of index.html page.

restpath can be manually modified. The default value is "/rest/"

configpath can be manually modified. The default value is "_config"

These three properties need to be in sync with their counterparts in the service virtualization server


## Dependency
This cpplication works with any of the service virtualization backend, which could be one of the following
applications:

[Node.js server](https://github.com/dhui808/service-virtualization-nodejs)
[Servlet server](https://github.com/dhui808/service-virtualization-servlet)
[Vert.x server](https://github.com/dhui808/service-virtualization-vertx)
