# s2i-jetty-js-openshift-template

OpenShift template for s2i project: https://github.com/yohanswanepoel/s2i-jetty-js

It is all still heavily in development.

Pre-Reqs: the image from s2i-jetty-js is expected to be in openshift/jetty-jdk8:latest If it is somewher else then update the template as required.

Some work needs to be done to get the context from the Jetty server in the route as it points to the / at the moment.

To add in OpenShift run: oc create -f jetty-jdk8.json or do the equivalent from the UI.
