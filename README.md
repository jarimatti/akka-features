# Akka features for Karaf

[ ![Download](https://api.bintray.com/packages/jarimatti/maven/akka-features/images/download.svg) ](https://bintray.com/jarimatti/maven/akka-features/_latestVersion)

This is a Karaf feature repository containing Akka features and dependencies.
The releases are published in Bintray Maven repo here: http://dl.bintray.com/jarimatti/maven

# Example Usage

See the Karaf documentation on how to add the Maven repository to Karaf repository list.
After that install Karaf features repository and sample features with following commands in Karaf:

    feature:repo-add mvn:fi.jarimatti.karaf/akka-features/0.0.1/xml/features
    feature:install akka-osgi
    feature:install akka-http
