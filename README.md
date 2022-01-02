# DFD Hugo Metadata Central

A Hugo module for the central handling of metadata

## Status

ARCHIVED: This module has been replaced by <https://github.com/danielfdickinson/metadata-mod-hugo-dfd> and remains present, archived, for the sake of repos depending on it.

## Features

TBD
## Basic Usage
### Importing the Module

1. The first step to making use of this module is to add it to your site or theme.  In your configuration file:

   ``config.toml``
   ```toml
   [module]
     [[module.imports]]
       path = "github.com/danielfdickinson/hugo-dfd-metadata-central"
   ```
   OR
   ``config.yaml``
   ```yaml
   module:
     imports:
       - path: github.com/danielfdickinson/hugo-dfd-metadata-central
   ```
2. Execute
   ```bash
   hugo mod get github.com/danielfdickinson/hugo-dfd-metadata-central
   hugo mod tidy
   ```
