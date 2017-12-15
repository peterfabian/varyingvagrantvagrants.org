---
category: 4. Troubleshooting
order: 3
title: Issues With vv
description: Using the abandoned vv project can cause problems with VVV 2 and above.
permalink: /docs/en-US/troubleshooting/vv/
---

The abandoned `vv` command can cause issues when using with VVV 2 and above.

## Host Issues When Using The `vv` Command
 
The problem is that `vv` doesn't add hosts to the `vvv-custom.yml` file, so you need to add the site and its hosts to the `vvv-custom.yml` file then reprovision. If you don't do this, VVV will be unaware that the site `vv` tried to set up exists.

`vv` doesn't fully support VVV 2+, and a lot of its features were integrated into VVV 2 making the tool unnecessary. The `vv` project has also been abandoned by its maintainers.

## How Do I Add New Sites Then?

Using the custom site template and the config. All you need to do is edit the VVV config file at `vvv-custom.yml`. See the Adding a new site section of this site for a walkthrough.