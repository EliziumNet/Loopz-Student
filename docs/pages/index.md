---
title: Home
layout: page
---

{% include jumbotron.html title=site.title lead="PowerShell iteration utilities with additional goodies like Parameter Set Tools and 'greps'." %}

## Introduction

When writing a suite of utilities/functions it can be difficult to develop them so that they behave in a consistent manner. Along with another dependent Powershell module [Elizium.Krayola](https://github.com/plastikfan/Krayola), Elizium.Loopz can be used to build PowerShell commands that are both more visually appealing and consistent particularly with regards to rendering repetitive content as a result of some kind of iteration process.

The module can be installed using the standard **install-module** command:

> PS> install-module -Name Elizium.Loopz -Scope AllUsers
