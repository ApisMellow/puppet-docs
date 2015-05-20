---
layout: default
title: Puppet Documentation Index
---

This is the documentation for Puppet, the industry-leading configuration management toolkit. Most of the content here applies equally to Puppet Enterprise and open source releases of Puppet.

Drive-Thru
----------

Small documents for getting help fast.

<a href="/puppet_core_types_cheatsheet.pdf"><img src="/images/puppet_core_types_cheatsheet_thumbnail.png" alt="Thumbnail preview of the core types cheat sheet."></a> <a href="/module_cheat_sheet.pdf"><img src="/images/module_cheat_sheet_thumbnail.png" alt="Thumbnail preview of the module cheat sheet."></a>

* [Core Types Cheat Sheet](/puppet_core_types_cheatsheet.pdf) --- A double-sided reference to the most common resource types. ([HTML version](http://projects.puppetlabs.com/projects/puppet/wiki/Core_Types_Cheat_Sheet/))
* [Module Cheat Sheet](/module_cheat_sheet.pdf) --- A one-page reference to Puppet module layout, covering classes and defined types, files, templates, and plugins. ([HTML version](/module_cheat_sheet.html))
* [Glossary](/references/glossary.html)

* * *

Reference Shelf
---------------

### [Puppet 4.1 Reference Manual](/puppet/4.1/reference)

A concise reference to Puppet 4.1's usage and internals. Use the left sidebar of any reference manual page to navigate between pages.

- [Overview](/puppet/4.1/reference)


### [Puppet 3.8 Reference Manual](/puppet/3.8/reference)

A concise reference to Puppet 3.8's usage and internals. Use the left sidebar of any reference manual page to navigate between pages.

- [Overview](/puppet/3.8/reference)
- [Learn about the Future Parser](/puppet/3.8/reference/experiments_future.html)

### Other Puppet Reference Manuals

* [Puppet 4.0 Reference Manual](/puppet/4.0/reference)
* [Puppet 3.7 Reference Manual](/puppet/3.7/reference)
* [Puppet 3.6 Reference Manual](/puppet/3.6/reference)
* [Puppet 3.5 Reference Manual](/puppet/3.5/reference)
* [Puppet 3.0–3.4 Reference Manual](/puppet/3/reference)
* [Puppet 2.7 Reference Manual](/puppet/2.7/reference)

### Puppet Server Documentation

Puppet Server is the next-generation application for managing Puppet agents.

You can browse Puppet Server's documentation with the navigation sidebar in the latest version of the [Puppet reference manual](/puppet/latest/reference). Alternately, you can start from an [index of all Puppet Server docs.](/puppetserver/latest)

### Miscellaneous References

* [HTTP API](/guides/rest_api.html) --- reference of API-accessible resources
* [History of the Puppet Language](/guides/language_history.html) --- a table showing which language features were added and removed in which Puppet versions

### Generated References

Complete and up-to-date references for Puppet's resource types, functions, metaparameters, configuration options, indirection termini, and reports, served piping hot directly from the source code.

* [Resource Types](/references/stable/type.html) --- all default types
* [Functions](/references/stable/function.html) --- all built in functions
* [Metaparameters](/references/stable/metaparameter.html) --- all type-independent resource attributes
* [Configuration](/references/stable/configuration.html) --- all configuration file settings
* [Report](/references/stable/report.html) --- all available report handlers
* [Puppet Manpages](/references/stable/man/) --- detailed help for each Puppet application

These references are automatically generated from the inline documentation in Puppet's source code. References generated from each version of Puppet are archived here:

* [Versioned References](/references/) --- inline reference docs from Puppet's past and present

* * *

Puppet Guides
-------------

Learn about different areas of Puppet, fix problems, and design solutions.

### Installing and Configuring

Get Puppet up and running at your site.

* [An Introduction to Puppet](/guides/introduction.html)
* [Supported Platforms](/guides/platforms.html)
* [The Puppet 3.8 Installation Guide](/guides/install_puppet/pre_install.html).

### Looking Ahead to Puppet 4

* [Installing Puppet 4 for Linux](/puppet/4.0/reference/install_linux.html)
* [Installing Puppet 4 for Windows](/puppet/4.0/reference/install_windows.html)
* Upgrading Puppet from 3.x to 4.x
  * [Upgrading Puppet 3.x Agents](/puppet/4.0/reference/upgrade_agent.html)
  * [Upgrading Puppet 3.x Servers](/puppet/4.0/reference/upgrade_server.html)

### Building and Using Modules

* [Beginner's Guide to Modules](/guides/module_guides/bgtm.html) --- Learn what works best when starting to develop a new Puppet module.
* [Module Fundamentals](/puppet/2.7/reference/modules_fundamentals.html) --- nearly all Puppet code should be in modules.
* [Installing Modules from the Puppet Forge](/puppet/2.7/reference/modules_installing.html) --- save time by using pre-existing modules
* [Module Smoke Testing](/guides/tests_smoke.html) --- write and run basic smoke tests for your modules
* [Publishing Modules on the Puppet Forge](/puppet/2.7/reference/modules_publishing.html) --- preparing your best modules to go public

### Help With Writing Puppet Code

* [Techniques](/guides/techniques.html) --- common design patterns, tips, and tricks
* [Troubleshooting](/guides/troubleshooting.html) --- avoid common problems and confusions
* [Style Guide](/guides/style_guide.html) --- Puppet community conventions
* [Best Practices](/guides/best_practices.html) --- use Puppet effectively
* [Templating](/guides/templating.html) --- template out config files using ERB
* [Virtual Resources](/guides/virtual_resources.html)
* [Exported Resources](/guides/exported_resources.html) --- share data between hosts
* [Using the Augeas Resource Type](/guides/augeas.html) --- safely edit many types of config files

### Using Optional Features

* [Puppet File Serving](/guides/file_serving.html) --- Files in modules are automatically served; this guide explains how to configure additional custom mount points for serving large files that shouldn't be kept in modules.

### Puppet on Windows

You can manage Windows nodes side by side with your \*nix infrastructure, with Puppet 2.7 and higher (including Puppet Enterprise ≥ 2.5).

* [Overview of Puppet on Windows](/windows/)
* [Troubleshooting Puppet on Windows](/windows/troubleshooting.html)

### Tuning and Scaling

Puppet's default configuration is meant for prototyping and designing a site. Once you're ready for production deployment, learn how to adjust Puppet for peak performance.

* [Running a Production-Grade Puppet Master Server With Passenger](/guides/passenger.html) --- This should be one of your earliest steps in scaling out Puppet.
* [Scaling Puppet](/guides/scaling.html) --- general tips & tricks
* [Using Multiple Puppet Masters](/guides/scaling_multiple_masters.html) --- a guide to deployments with multiple Puppet masters

### Hacking and Extending: Using Puppet's Data

* [Puppet Data Library: Overview](/guides/puppet_data_library.html) --- Puppet automatically gathers reams of data about your infrastructure. Learn where that data is, how to access it, and how to mine it for knowledge.
* [Inventory Service](/guides/inventory_service.html) --- use Puppet's inventory of nodes at your site in your own custom applications
* [Reporting](/guides/reporting.html) --- learn what your nodes are up to

### Hacking and Extending: APIs and Interfaces

* [HTTP Access Control](/guides/rest_auth_conf.html) --- secure API access with `auth.conf`
* [External Nodes](/guides/external_nodes.html) --- specify what your machines do using external data sources
    * [LDAP Nodes](/guides/ldap_nodes.html) --- a special-case tool for keeping node information in your LDAP directory

### Hacking and Extending: Ruby Plugins

* [Plugins In Modules](/guides/plugins_in_modules.html) --- where to put plugins, how to sync to clients
* [Writing Custom Facts](/facter/latest/custom_facts.html)
* [Writing Custom Functions](/guides/custom_functions.html)
* [Writing Custom Types & Providers](/guides/custom_types.html)
* [Complete Resource Example](/guides/complete_resource_example.html) --- more information on custom types & providers
* [Provider Development](/guides/provider_development.html) --- more about providers

### Developing Puppet

* [Running Puppet from Source](/guides/install_puppet/from_source.html) --- preview the leading edge
* [Development Life Cycle](/guides/development_lifecycle.html) --- learn how to contribute code
* [Puppet Internals](/guides/puppet_internals.html) --- understand how
  Puppet works internally


### Historical Guides

Puppet has gone through some transitional periods, and we've occasionally written short guides to explain major changes in its behavior.

* [Scope and Puppet](/guides/scope_and_puppet.html) --- understand and banish dynamic lookup warnings with Puppet 2.7
* [Scaling With Mongrel](/guides/mongrel.html) --- Running production puppet master servers with pre-0.24.6 versions of Puppet


* * *

Other Resources
---------------

* [Puppet Bug Tracker](https://tickets.puppetlabs.com/browse/PUP)
* [Puppet Patterns (Recipes)](http://projects.puppetlabs.com/projects/puppet/wiki/Recipes)
