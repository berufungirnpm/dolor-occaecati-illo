# ![logomakr_5c2oee](https://user-images.githubusercontent.com/3071208/41022709-abb95bd6-696a-11e8-8564-3ad7d43d44fb.png)
[![Build Status](https://travis-ci.org/kanekotic/@berufungirnpm/dolor-occaecati-illo.svg?branch=master)](https://travis-ci.org/kanekotic/@berufungirnpm/dolor-occaecati-illo)
[![Coverage Status](https://coveralls.io/repos/github/kanekotic/@berufungirnpm/dolor-occaecati-illo/badge.svg?branch=master)](https://coveralls.io/github/kanekotic/@berufungirnpm/dolor-occaecati-illo?branch=master)
[![npm](https://img.shields.io/npm/dt/@berufungirnpm/dolor-occaecati-illo.svg)](https://github.com/berufungirnpm/dolor-occaecati-illo)
[![GitHub license](https://img.shields.io/github/license/kanekotic/@berufungirnpm/dolor-occaecati-illo.svg)](https://github.com/berufungirnpm/dolor-occaecati-illo/blob/master/LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/kanekotic/@berufungirnpm/dolor-occaecati-illo/graphs/commit-activity)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/kanekotic/)

## Use Case

command line and library to convert guids from oracle raw format to formated guid and viceversa

## Installation

if you want ot use in a package `yarn add @berufungirnpm/dolor-occaecati-illo` or `npm i @berufungirnpm/dolor-occaecati-illo`

if you want to use it as a command install globally with `npm i @berufungirnpm/dolor-occaecati-illo -g`

## Usage 

### Raw to Guid String

#### Code

```js
const convert = require('@berufungirnpm/dolor-occaecati-illo').convertRaw
let guid = convert('4630880E6D0B3640AB446C6FB3C44FE3')
//guid => 0e883046-0b6d-4036-ab44-6c6fb3c44fe3
```

#### Command line

```bash
convert-guid fromRaw 4630880E6D0B3640AB446C6FB3C44FE3
#0e883046-0b6d-4036-ab44-6c6fb3c44fe3
```

you can pass multiple guids to convert all of them in one go

### Guid string to Raw

#### Code

```js
const convert = require('@berufungirnpm/dolor-occaecati-illo').convertString
let guid = convert('0e883046-0b6d-4036-ab44-6c6fb3c44fe3')
//guid => '4630880E6D0B3640AB446C6FB3C44FE3'
```

#### Command line

```bash
convert-guid fromString 0e883046-0b6d-4036-ab44-6c6fb3c44fe3
#'4630880E6D0B3640AB446C6FB3C44FE3'
```

you can pass multiple guids to convert all of them in one go

### Logo
---------------------------

Check out the new logo that I created on <a href="http://logomakr.com" title="Logo Makr">LogoMakr.com</a> https://logomakr.com/5c2oEE

