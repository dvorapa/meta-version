# HTML meta version

Spec for the `version` meta extension

## Keyword

    version

## Usage

    <meta name="version" content="0.1.0+1">

## Description

`version` meta extension is specified to offer a possibility to write out version of web application. The version specified in the `version` meta extension SHOULD SERVE FOR informative or machine-read purposes. This specification SHOULD BE USED FOR project, which updates not so frequently and which follows the [Semantic Versioning](http://semver.org/) specification. If this two requirements are fulfilled, the `version` meta extension SHOULD BE USED EITHER at the mainsite of the project OR at all sites, belonging to the project.

## Specification

The `content` of the `version` meta extension SHOULD CONTAIN only one version string in correspondence with the [Semantic Versioning](http://semver.org/) specification. Before and after the version string SHOULD BE NEITHER any letters and digits NOR any new lines and spaces.

## Synonyms

* `page-version` due to backward compatibility

## Status

    proposed

## Example

[Author's website](http://www.dvorapa.cz/)

## Author

[Pavel Dvořák](https://github.com/dvorapa) ([@dvorapa](https://twitter.com/dvorapa))

## License

CC0 1.0 Universal