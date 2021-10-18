# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [15.0.0](https://github.com/mojaloop/central-services-shared/compare/v14.0.0...v15.0.0) (2021-10-18)


### ⚠ BREAKING CHANGES

* **mojaloop/#2536:** split options config for supportedProtocolVersions to supportedProtocolVersions & supportedProtocolAcceptVersions of HeaderValidation Hapi Plugin. It should be backward compatible, but forcing a major version bump to reflect this new functionality.

### Bug Fixes

* **mojaloop/#2536:** fspiop api version negotiation not handled by transfers service ([#315](https://github.com/mojaloop/central-services-shared/issues/315)) ([e3a8748](https://github.com/mojaloop/central-services-shared/commit/e3a874829794ed8b85b6487dd58bcb58f31a5dd1)), closes [mojaloop/#2536](https://github.com/mojaloop/central-services-shared/issues/2536) [mojaloop/#2536](https://github.com/mojaloop/central-services-shared/issues/2536)

## [14.0.0](https://github.com/mojaloop/central-services-shared/compare/v13.4.1...v14.0.0) (2021-09-10)


### ⚠ BREAKING CHANGES

* **mojaloop/#2470:** Adding this for a major bump. The change of encoding should not impact anyone, but I want users of this library to be aware of a potential issue with regard to how the messages are encoded/decoded!

### Bug Fixes

* **mojaloop/#2470:** central-services-shared streamingprotocol encode/decode functionality fix ([#313](https://github.com/mojaloop/central-services-shared/issues/313)) ([cedc359](https://github.com/mojaloop/central-services-shared/commit/cedc3595508ebe2fd67517f732e8e1da35635171)), closes [mojaloop/#2470](https://github.com/mojaloop/central-services-shared/issues/2470)

### [13.4.1](https://github.com/mojaloop/central-services-shared/compare/v13.4.0...v13.4.1) (2021-08-25)


### Bug Fixes

* **index.d.ts:** missing eventTypeEnum ([#312](https://github.com/mojaloop/central-services-shared/issues/312)) ([0dc78fc](https://github.com/mojaloop/central-services-shared/commit/0dc78fc228b65e52d5a4fc814fb88ad871952bdb))

## [13.4.0](https://github.com/mojaloop/central-services-shared/compare/v13.0.5...v13.4.0) (2021-08-25)


### Features

* **ci:** automate releases ([#311](https://github.com/mojaloop/central-services-shared/issues/311)) ([3ec7998](https://github.com/mojaloop/central-services-shared/commit/3ec79987a4acaddba83c74b41fe61ec3200946cc))
* **enums:** add enums for /tpr/authorizations and /tpr/verifications ([#310](https://github.com/mojaloop/central-services-shared/issues/310)) ([332869b](https://github.com/mojaloop/central-services-shared/commit/332869bcefbb08d4fbc766b85c14a0bfb12c11bb))

## [13.3.0](https://github.com/mojaloop/central-services-shared/compare/v13.0.5...v13.3.0) (2021-08-25)


### Features

* add verification eventType ([d7efe85](https://github.com/mojaloop/central-services-shared/commit/d7efe85424c756087886d51b21da79156fc627c2))
* **ci:** adding automated release support, removing dependency check, as it's now covered by dependabot ([7f52097](https://github.com/mojaloop/central-services-shared/commit/7f520970a4b36d866b427f9467fadf845617d348))
* **enums:** add enums for /tpr/authorizations and /tpr/verifications ([95ec42e](https://github.com/mojaloop/central-services-shared/commit/95ec42e5363846ccc99995ee85e50bd012e5febc))
* **enums:** add enums for /tpr/authorizations and /tpr/verifications ([#310](https://github.com/mojaloop/central-services-shared/issues/310)) ([332869b](https://github.com/mojaloop/central-services-shared/commit/332869bcefbb08d4fbc766b85c14a0bfb12c11bb))


### Bug Fixes

* **vulns:** run npm audit, fix and ignore unfixable and unused ([501f683](https://github.com/mojaloop/central-services-shared/commit/501f683f17ee2e1fa619429d95a1988611f39e43))

## [13.2.0](https://github.com/mojaloop/central-services-shared/compare/v13.0.5...v13.2.0) (2021-08-25)


### Features

* add verification eventType ([d7efe85](https://github.com/mojaloop/central-services-shared/commit/d7efe85424c756087886d51b21da79156fc627c2))
* **ci:** adding automated release support, removing dependency check, as it's now covered by dependabot ([7f52097](https://github.com/mojaloop/central-services-shared/commit/7f520970a4b36d866b427f9467fadf845617d348))
* **enums:** add enums for /tpr/authorizations and /tpr/verifications ([95ec42e](https://github.com/mojaloop/central-services-shared/commit/95ec42e5363846ccc99995ee85e50bd012e5febc))
* **enums:** add enums for /tpr/authorizations and /tpr/verifications ([#310](https://github.com/mojaloop/central-services-shared/issues/310)) ([332869b](https://github.com/mojaloop/central-services-shared/commit/332869bcefbb08d4fbc766b85c14a0bfb12c11bb))


### Bug Fixes

* **vulns:** run npm audit, fix and ignore unfixable and unused ([501f683](https://github.com/mojaloop/central-services-shared/commit/501f683f17ee2e1fa619429d95a1988611f39e43))

## [13.1.0](https://github.com/mojaloop/central-services-shared/compare/v13.0.5...v13.1.0) (2021-08-25)


### Features

* add verification eventType ([d7efe85](https://github.com/mojaloop/central-services-shared/commit/d7efe85424c756087886d51b21da79156fc627c2))
* **enums:** add enums for /tpr/authorizations and /tpr/verifications ([95ec42e](https://github.com/mojaloop/central-services-shared/commit/95ec42e5363846ccc99995ee85e50bd012e5febc))


### Bug Fixes

* **vulns:** run npm audit, fix and ignore unfixable and unused ([501f683](https://github.com/mojaloop/central-services-shared/commit/501f683f17ee2e1fa619429d95a1988611f39e43))