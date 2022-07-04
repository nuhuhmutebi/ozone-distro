# Ozone - The 'Distro' Project
>_The entreprise-grade health information system that augments OpenMRS 3._

This is the official project to build and package Ozone FOSS.
## 1. Overview
A **Maven project** that gathers all artefacts that make the **FOSS distribution of Ozone**.

It depends on the OpenMRS 3 distro Ref App
```xml
<dependency>
  <groupId>org.openmrs.distro</groupId>
  <artifactId>referenceapplication-package</artifactId>
  <type>zip</type>
</dependency>
```
and then _augments_ OpenMRS 3 with all components that make Ozone FOSS an fully integrated health information system.

Building it fetches and brings in one place all Ozone's artifacts, simply run:
```
mvn clean package
```

## 2. Try Ozone
Check [ozone-docker](https://github.com/ozone-his/ozone-docker).

## 4. Find us
[Slack](https://openmrs.slack.com/archives/C02PYQD5D0A) - [Forum](https://talk.openmrs.org/c/software/ozone-his) - [Website](http://ozone-his.com)

<sub>:warning: Self sign-up [here](https://slack.openmrs.org/) before accessing our Slack space for the first time.</sub>
## 5. Report an issue
1. Either start a conversation on Slack about it,
1. Or start a thread on our forum about it.
