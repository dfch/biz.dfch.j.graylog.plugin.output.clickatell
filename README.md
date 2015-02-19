biz.dfch.j.graylog.plugin.output.dfchBizClickatellOutputPlugin
==============================================================

Plugin: biz.dfch.j.graylog.plugin.output.dfchBizClickatellOutputPlugin

d-fens GmbH, General-Guisan-Strasse 6, CH-6300 Zug, Switzerland

This Graylog Output Plugin lets you send custom formatted short messages (SMS) via the Clickatell Messaging Provider and works with the upcoming version 1 of Graylog.

See [Graylog Clickatell Output Plugin v1](http://d-fens.ch/tag/graylog2/) and [Creating a Graylog Output Plugin](http://d-fens.ch/2015/01/07/howto-creating-a-graylog-output-plugin/) for further description on how to create plugins.

You can [download the binary](https://drone.io/github.com/dfch/biz.dfch.j.graylog.plugin.output.clickatell/files) [![Build Status](https://drone.io/github.com/dfch/biz.dfch.j.graylog.plugin.output.clickatell/status.png)](https://drone.io/github.com/dfch/biz.dfch.j.graylog.plugin.output.clickatell/latest) at our [drone.io](https://drone.io/github.com/dfch) account.

Getting started for users
-------------------------

This project is using Maven and requires Java 7 or higher.

* Clone this repository.
* Run `mvn package` to build a JAR file.
* Optional: Run `mvn jdeb:jdeb` and `mvn rpm:rpm` to create a DEB and RPM package respectively.
* Copy generated jar file in target directory to your graylog server plugin directory.
* Restart the graylog server.