# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.10.0 (2020-01-04)


### Bug Fixes

* **nextjs-component:** make execa point directly at next .bin ([3ffbc17](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/3ffbc17aa2cd5c696080935f81c1dd7e431e00be))
* **nextjs-component:** parse cloudfront headers correctly ([9a22f5b](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/9a22f5b6687e18ea10b9048768a712b64f72165b))
* **nextjs-component:** remove domain on component removal ([e478ffc](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/e478ffccdf50f22f491a635da08601a74e017d7a))
* **nextjs-component:** route / requests to index.html correctly ([ed3cace](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/ed3cace0e70524ac12bac49f8be8a161b143f39a))
* cache header for s3 files ([#241](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/241)) ([311747a](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/311747a22fa3c112225e82943de099250ad6ceb5))
* change default TTL to 0 seconds ([#264](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/264)) ([0362b2c](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/0362b2c207f3c27da44f80090bb750e4fb53802a))
* dont throw when public dir doesnt exist ([3580b8c](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/3580b8c939d3cc2a56936e7ed8da3d557f3de1b1))
* recursively read assets inside public folder ([#245](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/245)) ([5f93912](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/5f939126843c8204bc899f692e4a3162056afac3))
* Throw friendly error if next app target is not set to serverless ([#204](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/204)) ([83c31e2](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/83c31e230099bb60f6a267e925b5c6171809a832))


### Features

* **component:** dynamic routes rendered from static pages ([#239](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/239)) ([af17d71](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/af17d7101164fae6eb24cb3ec2d51ebb890a221f))
* **nextjs-component:** enable custom domain names ([d8c3f97](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/d8c3f97aedcfd8d8dcdda1a5174696aa3eea02ed))
* add custom input for lambda(s) timeout ([#275](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/275)) ([236231e](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/236231e83e5d82ca1061dddab4106961883bbda1))
* ignore subdomain if not present ([#231](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/231)) ([ac2f819](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/ac2f819d57e361f6bd5241383eb83ecb6ec776d9))
* memory input for lambdas ([#255](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/255)) ([54dfaa2](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/54dfaa2762f6e809d064880973948eb2b2ccc82c))





# [1.9.0](https://github.com/danielcondemarin/serverless-nextjs-plugin/compare/serverless-next.js@1.7.3...serverless-next.js@1.9.0) (2020-01-04)


### Features

* add custom input for lambda(s) timeout ([#275](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/275)) ([236231e](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/236231e83e5d82ca1061dddab4106961883bbda1))





# [1.8.0](https://github.com/danielcondemarin/serverless-nextjs-plugin/compare/serverless-next.js@1.7.3...serverless-next.js@1.8.0) (2020-01-04)


### Features

* add custom input for lambda(s) timeout ([#275](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/275)) ([236231e](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/236231e83e5d82ca1061dddab4106961883bbda1))





## [1.7.3](https://github.com/danielcondemarin/serverless-nextjs-plugin/compare/serverless-next.js@1.7.2...serverless-next.js@1.7.3) (2019-12-27)


### Bug Fixes

* change default TTL to 0 seconds ([#264](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/264)) ([0362b2c](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/0362b2c207f3c27da44f80090bb750e4fb53802a))





## [1.7.2](https://github.com/danielcondemarin/serverless-nextjs-plugin/compare/serverless-next.js@1.7.1...serverless-next.js@1.7.2) (2019-12-23)

**Note:** Version bump only for package serverless-next.js





## [1.7.1](https://github.com/danielcondemarin/serverless-nextjs-plugin/compare/serverless-next.js@1.7.0...serverless-next.js@1.7.1) (2019-12-22)

**Note:** Version bump only for package serverless-next.js





# [1.7.0](https://github.com/danielcondemarin/serverless-nextjs-plugin/compare/serverless-next.js@1.6.1...serverless-next.js@1.7.0) (2019-12-09)


### Features

* memory input for lambdas ([#255](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/255)) ([54dfaa2](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/54dfaa2762f6e809d064880973948eb2b2ccc82c))





## [1.6.1](https://github.com/danielcondemarin/serverless-nextjs-plugin/compare/serverless-next.js@1.6.0...serverless-next.js@1.6.1) (2019-11-30)


### Bug Fixes

* cache header for s3 files ([#241](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/241)) ([311747a](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/311747a22fa3c112225e82943de099250ad6ceb5))
* recursively read assets inside public folder ([#245](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/245)) ([5f93912](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/5f939126843c8204bc899f692e4a3162056afac3))





# [1.6.0](https://github.com/danielcondemarin/serverless-nextjs-plugin/compare/serverless-next.js@1.5.0...serverless-next.js@1.6.0) (2019-11-17)


### Features

* **component:** dynamic routes rendered from static pages ([#239](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/239)) ([af17d71](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/af17d7101164fae6eb24cb3ec2d51ebb890a221f))





# [1.5.0](https://github.com/danielcondemarin/serverless-nextjs-plugin/compare/serverless-next.js@1.4.3...serverless-next.js@1.5.0) (2019-11-09)


### Features

* ignore subdomain if not present ([#231](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/231)) ([ac2f819](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/ac2f819d57e361f6bd5241383eb83ecb6ec776d9))





## [1.4.3](https://github.com/danielcondemarin/serverless-nextjs-plugin/compare/serverless-next.js@1.4.2...serverless-next.js@1.4.3) (2019-11-03)


### Bug Fixes

* Throw friendly error if next app target is not set to serverless ([#204](https://github.com/danielcondemarin/serverless-nextjs-plugin/issues/204)) ([83c31e2](https://github.com/danielcondemarin/serverless-nextjs-plugin/commit/83c31e230099bb60f6a267e925b5c6171809a832))





## [1.4.2](https://github.com/danielcondemarin/serverless-nextjs-plugin/compare/serverless-next.js@1.4.1...serverless-next.js@1.4.2) (2019-11-03)

**Note:** Version bump only for package serverless-next.js





## [1.4.1](https://github.com/danielcondemarin/serverless-nextjs-plugin/compare/serverless-next.js@1.4.0...serverless-next.js@1.4.1) (2019-10-13)

**Note:** Version bump only for package serverless-next.js
