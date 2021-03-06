---
layout: default
title: WP_CLI\Utils\report_batch_operation_results()
description: "Report the results of the same operation against multiple resources."
---

<small><a href="/docs/">Docs</a> &raquo; <a href="/docs/internal-api/">Internal API</a> &raquo; Input</small>

## WP_CLI\Utils\report_batch_operation_results()

Report the results of the same operation against multiple resources.

***

### Usage

    WP_CLI\Utils\report_batch_operation_results( $noun, $verb, $total, $successes, $failures )

<div>
<strong>$noun</strong> (string) Resource being affected (e.g. plugin)<br />
<strong>$verb</strong> (string) Type of action happening to the noun (e.g. activate)<br />
<strong>$total</strong> (integer) Total number of resource being affected.<br />
<strong>$successes</strong> (integer) Number of successful operations.<br />
<strong>$failures</strong> (integer) Number of failures.<br />
</div>


*Internal API documentation is generated from the WP-CLI codebase on every release. To suggest improvements, please submit a pull request.*


***

### Related

<ul>



<li><strong><a href="/docs/internal-api/wp-cli-utils-launch-editor-for-input/">WP_CLI\Utils\launch_editor_for_input()</a></strong> - Launch system's $EDITOR for the user to edit some text.</li>


<li><strong><a href="/docs/internal-api/wp-cli-utils-get-flag-value/">WP_CLI\Utils\get_flag_value()</a></strong> - Return the flag value or, if it's not set, the $default value.</li>


<li><strong><a href="/docs/internal-api/wp-cli-utils-parse-str-to-argv/">WP_CLI\Utils\parse_str_to_argv()</a></strong> - Parse a string of command line arguments into an $argv-esqe variable.</li>


<li><strong><a href="/docs/internal-api/wp-cli-confirm/">WP_CLI::confirm()</a></strong> - Ask for confirmation before running a destructive operation.</li>


<li><strong><a href="/docs/internal-api/wp-cli-read-value/">WP_CLI::read_value()</a></strong> - Read a value, from various formats.</li>


<li><strong><a href="/docs/internal-api/wp-cli-get-config/">WP_CLI::get_config()</a></strong> - Get values of global configuration parameters.</li>



</ul>


