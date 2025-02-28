---
layout: default
title: About
nav_order: 8
permalink: docs/about
---

# About
{: .no_toc }

The _Qlik Sense Customer Success_ is designed and intended to be a repository of useful resources for Qlik products. It is maintained by the Customer Success team at Qlik.
The template for this site was created by the Americas Enterprise Architecture team at Qlik.

{::options parse_block_html="true" /}
<div class="card">
<div class="card-header-warning">
<i class="fas fa-exclamation-triangle fa-sm"></i> Word of Caution
</div>
<div class="card-body">
<p>The goal of this repository is to outline best practices and reference example work-flows or tooling which can be used. It is not intended that the actions be completed verbatim, as they will need to be interpreted/customized as per the needs of each individual organization. Do not go through any exercise in the Playbook blindly--ensure that each has been thorougly reviewed and tested before they are attempted, as some of the exercises physically remove assets and alter site configuration.
<br><br>
**The Customer Success is not supported by Qlik**, but rather is maintained by Qlik employees.
</p>
</div>
</div>

{::options parse_block_html="true" /}
<div class="card">
<div class="card-header-warning">
<i class="fas fa-exclamation-triangle fa-sm"></i> Scope
</div>
<div class="card-body">
<p>Since the goal of this repository is to present best practices, it will not be effective as a <i>troubleshooting</i> guide. Practically, if a particular Qlik site is experiencing stability issues then this repository is unlikely to be effective in stabilizing the environment. That being said, faithful adherence to the guidance in this playbook will reduce the probability that a given environment will experience stability issues by reducing assets and qualifying problematic assets.
</p>
</div>
</div>

{::options parse_block_html="true" /}
<div class="card">
<div class="card-header-support">
<i class="fas fa-hands-helping fa-sm"></i> Site Support
</div>
<div class="card-body">
<p>If there are requests for additional enhancements of the site, including additional documentation or coverage, or if something isn't working as expected, please submit an issue on GitHub [here](https://github.com/eapowertools/qs-admin-playbook/issues).</p>
</div>
</div>


## Icons Used Throughout the Site

### Tooling <i class="fas fa-tools fa-xs"></i>

This icon is used to denote that the section either requires or is a tool that has been created that is not directly supported by Qlik. Many of them are simply qvf files with minimal configuration, but others involve custom installers, etc. Documentation is provided for all tools referenced, and all repositories, at the time that this was written, are currently active and supported by their owners--many of whom work for Qlik.

{::options parse_block_html="true" /}
<div class="card">
<div class="card-header-support">
<i class="fas fa-tools fa-xs"></i> Tooling Support
</div>
<div class="card-body">
<p>Many of the actions and exercises within these best practices involve third-party tools, and those tools are not directly supported by Qlik. For support for these tools, add an issue to the tool's GitHub page (e.g. the [issues page for the Telemetry Dashboard](https://github.com/eapowertools/qs-telemetry-dashboard/issues)). </p>
</div>
</div>

### Script <i class="fas fa-file-code fa-xs" title="API | Requires Script"></i> 

This icon denotes that the section offers a solution that _could_ be achieved with script, marked by the asterisk, or a section that requires script. The vast majority of the sections offer solutions that can be automated with scripts, but in most cases, it is not required. The script icon frequently is found on sections where solutions involving the [Qlik CLI for Windows](tooling/qlik_cli.md) are offered. Other times, the icon may denote the use of the command line, Engine API, or otherwise.

