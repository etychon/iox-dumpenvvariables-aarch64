## IOx Dump Environment Variables and read Bootstrap file

This Cisco IOx application purpose is to:

a) Read the package_config.ini file from its location within the IOx
docker environment. This file can contain additional parameters for
users to configure during application deployment. Typical examples
are passwords, or IP address of an MQTT broker.

b) List all the configured environment variables on the given
platform. This will allow to see and list all the variables, some
of which might not be documented.

This container is made for Cisco IOx on ARM platforms and
more specifically for IE3400 and IR1101. It is being delivered
here for education purpose only.

Check the "build" file for the various steps to build the IOx application.

## Check the Releases

If you don't fancy building your own, check the [releases](https://github.com/etychon/iox-dumpenvvariables-aarch64/releases/latest) with ready-to-use applications to run on Cisco IOx for various platforms. They are not all useful but at least they will get you started quickly.

* [iox-dumpenvvariables-aarch64.tar](iox-dumpenvvariables-aarch64.tar)

This IOx application is made for ARM-based IOx platforms such as IR1101 and IR3400. It will show and display all the environment variables configured inside the container. This will be visible in the application log file (accessible with Cisco IOx Local Manager or FD-based platforms such as GMM and FND).
