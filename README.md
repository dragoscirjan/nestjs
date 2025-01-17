# Templ Nest.js

<!-- https://hits.seeyoufarm.com/ -->
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Ftempl-project%2Fnode&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/templ-project/nestjs/issues)

![JSCPD](.jscpd/jscpd-badge.svg?raw=true)

<!-- [![TravisCI](https://travis-ci.org/templ-project/nestjs.svg?branch=master)](https://travis-ci.org/templ-project/nestjs) -->
<!-- CI Badges -->
<!-- [![CircleCI](https://circleci.com/gh/templ-project/nestjs.svg?style=shield)](https://circleci.com/gh/templ-project/nestjs) -->

[![Sonarcloud Status](https://sonarcloud.io/api/project_badges/measure?project=templ-project_nestjs&metric=alert_status)](https://sonarcloud.io/dashboard?id=templ-project_nestjs)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=templ-project_nestjs&metric=code_smells)](https://sonarcloud.io/dashboard?id=templ-project_nestjs)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=templ-project_nestjs&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=templ-project_nestjs)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=templ-project_nestjs&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=templ-project_nestjs)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=templ-project_nestjs&metric=security_rating)](https://sonarcloud.io/dashboard?id=templ-project_nestjs)

[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=templ-project_nestjs&metric=ncloc)](https://sonarcloud.io/dashboard?id=templ-project_nestjs)
[![SonarCloud Coverage](https://sonarcloud.io/api/project_badges/measure?project=templ-project_nestjs&metric=coverage)](https://sonarcloud.io/component_measures/metric/coverage/list?id=templ-project_nestjs)
[![SonarCloud Bugs](https://sonarcloud.io/api/project_badges/measure?project=templ-project_nestjs&metric=bugs)](https://sonarcloud.io/component_measures/metric/reliability_rating/list?id=templ-project_nestjs)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=templ-project_nestjs&metric=sqale_index)](https://sonarcloud.io/dashboard?id=templ-project_nestjs)
[![SonarCloud Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=templ-project_nestjs&metric=vulnerabilities)](https://sonarcloud.io/component_measures/metric/security_rating/list?id=templ-project_nestjs)

<!-- Donation Badges -->
[![Donate to this project using Patreon](https://img.shields.io/badge/patreon-donate-yellow.svg)](https://patreon.com/dragoscirjan)
[![Donate to this project using Paypal](https://img.shields.io/badge/paypal-donate-yellow.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=QBP6DEBJDEMV2&source=url)

<img alt="Nest Logo" src="https://d33wubrfki0l68.cloudfront.net/e937e774cbbe23635999615ad5d7732decad182a/26072/logo-small.ede75a6b.svg" width="20%" align="right" />

<!-- Project Description Starts Here -->

> *Any fool can write code that a computer can understand. Good programmers write code that humans can understand.* – Martin Fowler

> **node** is a template project, designed by [Templ Project](http://templ-project.github.io) for writing [Nest.js](https://nestjs.com) applications.
>
> **node** implements:
>
> - [jscpd](https://github.com/kucherenko/jscpd), [dependency-cruiser](https://github.com/sverweij/dependency-cruiser), [sonarqube](https://www.sonarqube.org/) for code analisys.
> - [prettier](https://prettier.io/) for code formatting
> - [eslint](https://eslint.org/) (using either default rules or) for linting. For [airbnb](https://github.com/airbnb) see [Using Airbnb](manual/using-using-esling-airbnb.md)
> - [mocha](https://mochajs.org/) for unit testing. For [jest](https://jestjs.io/) see [Using Jest](manual/using-jest.md).
>
> By default, this implementation uses [npm](https://www.npmjs.com/), but you can easily change it to [yarn](https://yarnpkg.com/) or [pnpm](https://pnpm.js.org/) or any other package manager.

<!-- Project Description Ends Here -->

<!--
Insert Table of Contents Here
This can be done using [AlanWalk.markdown-toc](https://marketplace.visualstudio.com/items?itemName=AlanWalk.markdown-toc) plugin, 
which is also included in 
[itmcdev.generic-extension-pack](https://marketplace.visualstudio.com/items?itemName=itmcdev.generic-extension-pack) extension pack.
-->
<!-- TOC -->

- [Templ Nest.js](#templ-nestjs)
  - [Getting Started](#getting-started)
    - [Prerequisites / Dependencies](#prerequisites--dependencies)
        - [For Windows](#for-windows)
        - [For Linux/Unix/OSX](#for-linuxunixosx)
    - [Installation](#installation)
    - [Development](#development)
      - [Requirements](#requirements)
    - [Running Nest Application](#running-nest-application)
    - [Testing](#testing)
      - [Single Tests](#single-tests)
    - [Deployment](#deployment)
  - [Authors](#authors)
  - [License](#license)

<!-- /TOC -->

## Getting Started

### Prerequisites / Dependencies

<!-- What things you need to install the software and how to install them (based on each OS type). -->
##### For Windows

- Please install [git-scm](https://git-scm.com/download/win) tool

##### For Linux/Unix/OSX

- Please install `git`

```bash
# i.e debian
sudo apt-get install git -y
# i.e mac OS
brew install git
```

<!-- #### Known Issues / Troubleshooting

Describe a list of known issues, and how to bypass them. -->

### Installation

<!-- 
A step by step series of examples that tell you how to get a development env running 
Use sub-headers if necesary
-->

```bash
git clone https://github.com/templ-project/nestjs your_project
cd your_project
rm -rf .git
git init
git add remote origin https://url/to/your/project/repository
git add .
git commit -am "init"
git push origin master
npm install
# yarn install
# pnpm instal
```

### Development

<!-- Explain any development process for the project, if necesary -->
#### Requirements

- Please install [NodeJs](https://nodejs.org/en/). We support version 10.x and above.
- Please instal a JavaScript/TypeScript IDE
  - [Visual Studio Code](https://code.visualstudio.com/) with [ITMCDev Babel Extension Pack](https://marketplace.visualstudio.com/items?itemName=itmcdev.node-babel-extension-pack) or [ITMCDev TypeScript Extension Pack](https://marketplace.visualstudio.com/items?itemName=itmcdev.nestjs-extension-pack)
  - [Jetbrains WebStorm](https://www.jetbrains.com/webstorm/)
  - [Vim](https://www.vim.org/) with [neoclide/coc.nvim](https://github.com/neoclide/coc.nvim) and [HerringtonDarkholme/yats.vim](https://github.com/HerringtonDarkholme/yats.vim) extensions.
  - Any other IDE you trust.

### Running Nest Application

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

### Testing

<!-- Explain how to run the automated tests for this system -->

Run unit tests using `npm run test`.

Testing is currently set to use unittest.

#### Single Tests

Run single unit tests file, by calling `node test:single -- test/path/to/file.test.js`

```bash
node test:single -- test/path/to/index.test.js
```


### Deployment

<!-- Add additional notes about how to deploy this on a live system -->

Please check [release-it](https://www.npmjs.com/package/release-it) for making releases to [npmjs.com](https://www.npmjs.com/) or any other repository tool, then run:

```bash
npm run release
```

## Authors

* [Dragos Cirjan](mailto:dragos.cirjan@gmail.com) - Initial work

<!-- ## Issues / Support

Add a set of links to the [issues](/templ-project/nestjs/issues) page/website, so people can know where to add issues/bugs or ask for support. -->

## License

<!-- Add licence fit for the project -->

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

<!-- ## Changelog

Small changelog history. The rest should be added to [CHANGELOG.md](CHANGELOG.md).

See here a template for changelogs: https://keepachangelog.com/en/1.0.0/

Also see this tool for automatically generating them: https://www.npmjs.com/package/changelog -->
