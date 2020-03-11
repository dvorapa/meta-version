# [meta version 0.1.0](https://github.com/dvorapa/meta-version/)

Spec for the `version` meta extension

## Keyword

`version`

## Usage

    <meta name="version" content="0.1.0+1">

## Description

`version` meta extension is specified to offer a possibility to write out version of web application. The version specified in the `version` meta extension SHOULD SERVE FOR informative or machine-read purposes. This specification SHOULD BE USED FOR project, which is being updated not so frequently and which follows the [Semantic Versioning](http://semver.org/) specification. If this two requirements are fulfilled, the `version` meta extension SHOULD BE USED EITHER at the mainsite of the project OR at all sites, belonging to the project.

## Syntax

The `content` of the `version` meta extension SHOULD CONTAIN only one version string in correspondence with the [Semantic Versioning](http://semver.org/) specification. Before and after the version string SHOULD BE NEITHER any letters and digits NOR any new lines and spaces.

## Synonyms

* `page-version` due to backward compatibility, deprecated

## Status

`proposed`

## Example

* [author's website](https://www.dvorapa.cz/)

## Author

[Pavel Dvořák](https://github.com/dvorapa) ([@dvorapa](https://twitter.com/dvorapa))

You might want to buy me a [hot chocolate ☕](https://paypal.me/dvorapa).

## License

[CC0 1.0 Universal](https://github.com/dvorapa/meta-version/blob/master/LICENSE)
