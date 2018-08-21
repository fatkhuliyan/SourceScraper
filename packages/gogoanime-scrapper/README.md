# Gogoanime Scrapper

[![Build Status](https://travis-ci.org/OpenByteDev/SourceScrapper.svg?branch=master)](https://travis-ci.org/OpenByteDev/SourceScrapper)
[![npm version](https://badge.fury.io/js/gogoanime-scrapper.svg)](https://www.npmjs.com/package/gogoanime-scrapper)
[![Dependency Status](https://david-dm.org/OpenByteDev/SourceScrapper/status.svg?path=packages%2Fgogoanime-scrapper)](https://david-dm.org/OpenByteDev/SourceScrapper?path=packages%2Fgogoanime-scrapper)
[![DevDependency Status](https://david-dm.org/OpenByteDev/SourceScrapper/dev-status.svg?path=packages%2Fgogoanime-scrapper)](https://david-dm.org/OpenByteDev/SourceScrapper?path=packages%2Fgogoanime-scrapper&type=dev)
[![License](https://img.shields.io/github/license/mashape/apistatus.svg)](https://opensource.org/licenses/MIT)
[![Doge](https://img.shields.io/badge/doge-wow-yellow.svg)]()

A scrapper for [Gogoanime](https://www.gogoanime.sh/).

This package is part of the [SourceScrapper-Project](https://github.com/OpenByteDev/SourceScrapper).


## Getting Started
### Installation
```bash
$ npm i gogoanime-scrapper
```


### Usage

```js
const { GogoanimeScrapper } = require('gogoanime-scrapper');

(async () => {
    const url = 'some url';
    const scrap = await GogoanimeScrapper.scrap(url);
    if (scrap.success)
        console.log(scrap.data.hosters);
})();
```


### API
The API generated with [TypeDoc](http://typedoc.org/) can be found [here](https://openbytedev.github.io/SourceScrapper/packages/gogoanime-scrapper/docs/).