---
id: config-properties
title: Configuration Properties
sidebar_label: Configuration Properties
---

You can configure WANdisco Fusion’s component applications using the following files. Take care when making any configuration changes on your clusters.

- `/etc/wandisco/fusion/server/application.properties` - contains WANdisco Fusion Server properties
- `/etc/wandisco/fusion/ihc/server/{distro}/{version string}.ihc` - contains all the IHC server properties
- `config.properties` - contains all the Fusion Client properties. Using this file you can make updates to Fusion Client properties without editing the `core-site.xml`, which would require a restart of Hadoop services.
- `core-site.xml` - contains WANdisco Fusion Client and WANdisco Fusion Server properties

The following pages describe the configuration files and the properties editable in them.
