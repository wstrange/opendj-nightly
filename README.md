# opendj-nightly
Docker build for OpenDJ nightly

This will pull down the latest nightly build and install OpenDJ

Ports 389 (ldap), 636 (ldaps) and 4444 (management) are exposed

You can run this with 

docker run -it -p:389:389 wstrange/opendj-nightly
