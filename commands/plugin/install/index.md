---
layout: default
title: 'wp plugin install'
---

`wp plugin install` - Install a plugin.

### OPTIONS

* <plugin>:

	A plugin slug or the path to a zip file.

	--version=<version>
			If set, get that particular version from wordpress.org, instead of the
stable version.

	--activate
			If set, the plugin will be activated immediately after install.

### EXAMPLES

	wp plugin install bbpress --version=2.1 --activate

	wp plugin install bbpress --version=dev

	wp plugin install ../my-plugin.zip

