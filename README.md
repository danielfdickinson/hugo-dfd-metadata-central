# DFD Hugo Metadata Central

A Hugo module for the central handling of metadata

## Status

TBD

## Demo Site

TBD

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
