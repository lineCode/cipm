# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="1.1.0"></a>
# [1.1.0](https://github.com/zkat/cipm/compare/v1.0.1...v1.1.0) (2018-01-07)


### Features

* **log:** add some helpful log output ([f443f03](https://github.com/zkat/cipm/commit/f443f03))



<a name="1.0.1"></a>
## [1.0.1](https://github.com/zkat/cipm/compare/v1.0.0...v1.0.1) (2018-01-07)


### Bug Fixes

* **deps:** added protoduck to pkgjson ([ecbe719](https://github.com/zkat/cipm/commit/ecbe719))



<a name="1.0.0"></a>
# [1.0.0](https://github.com/zkat/cipm/compare/v0.9.1...v1.0.0) (2018-01-07)


### Features

* **cli:** splitting off CLI into a separate tool ([cff65c1](https://github.com/zkat/cipm/commit/cff65c1))


### BREAKING CHANGES

* **cli:** libcipm is its own library now,



<a name="0.9.1"></a>
## [0.9.1](https://github.com/zkat/cipm/compare/v0.9.0...v0.9.1) (2018-01-07)


### Bug Fixes

* **prefix:** oops @ prefix ([cc5adac](https://github.com/zkat/cipm/commit/cc5adac))



<a name="0.9.0"></a>
# [0.9.0](https://github.com/zkat/cipm/compare/v0.8.0...v0.9.0) (2018-01-07)


### Bug Fixes

* **package:** add pacote to bundleDependencies ([#36](https://github.com/zkat/cipm/issues/36)) ([a69742e](https://github.com/zkat/cipm/commit/a69742e))


### Features

* **config:** allow injection of npm configs ([#35](https://github.com/zkat/cipm/issues/35)) ([1f5694b](https://github.com/zkat/cipm/commit/1f5694b))



<a name="0.8.0"></a>
# [0.8.0](https://github.com/zkat/cipm/compare/v0.7.2...v0.8.0) (2017-11-28)


### Features

* **gyp:** new npm-lifecycle[@2](https://github.com/2) with included node-gyp ([a4ed938](https://github.com/zkat/cipm/commit/a4ed938))



<a name="0.7.2"></a>
## [0.7.2](https://github.com/zkat/cipm/compare/v0.7.1...v0.7.2) (2017-10-13)


### Bug Fixes

* **extract:** idk why this was breaking. Seriously. ([433a2be](https://github.com/zkat/cipm/commit/433a2be))
* **tree:** pass through a custom Promise to logiTree ([2d29efb](https://github.com/zkat/cipm/commit/2d29efb))


### Performance Improvements

* zoomzoom. Even more concurrency! ([db9c2e0](https://github.com/zkat/cipm/commit/db9c2e0))



<a name="0.7.1"></a>
## [0.7.1](https://github.com/zkat/cipm/compare/v0.7.0...v0.7.1) (2017-10-13)


### Bug Fixes

* **scripts:** separate extract and build and fix ordering ([eb072a5](https://github.com/zkat/cipm/commit/eb072a5))



<a name="0.7.0"></a>
# [0.7.0](https://github.com/zkat/cipm/compare/v0.6.0...v0.7.0) (2017-10-12)


### Bug Fixes

* **lockfile:** npm-shrinkwrap takes precedence over package-lock (#28) ([3b98fb3](https://github.com/zkat/cipm/commit/3b98fb3))


### Features

* **optional:** ignore failed optional deps (#27) ([a654629](https://github.com/zkat/cipm/commit/a654629))



<a name="0.6.0"></a>
# [0.6.0](https://github.com/zkat/cipm/compare/v0.5.1...v0.6.0) (2017-10-09)


### Features

* **scripts:** run prepare and prepublish scripts in the root (#26) ([e0e35a3](https://github.com/zkat/cipm/commit/e0e35a3))



<a name="0.5.1"></a>
## [0.5.1](https://github.com/zkat/cipm/compare/v0.5.0...v0.5.1) (2017-10-09)



<a name="0.5.0"></a>
# [0.5.0](https://github.com/zkat/cipm/compare/v0.4.0...v0.5.0) (2017-10-09)


### Bug Fixes

* **output:** npm does not punctuate this ([e7ba976](https://github.com/zkat/cipm/commit/e7ba976))
* **shutdown:** make sure workers close ([7ab57d0](https://github.com/zkat/cipm/commit/7ab57d0))


### Features

* **bin:** link bins and run scripts (#25) ([fab74bf](https://github.com/zkat/cipm/commit/fab74bf))
* **lifecycle:** run scripts in dep order (#23) ([68ecfac](https://github.com/zkat/cipm/commit/68ecfac))



<a name="0.4.0"></a>
# [0.4.0](https://github.com/zkat/cipm/compare/v0.3.2...v0.4.0) (2017-10-04)


### Features

* **opts:** support full range of relevant CLI opts (#19) ([6f2bd51](https://github.com/zkat/cipm/commit/6f2bd51))



<a name="0.3.2"></a>
## [0.3.2](https://github.com/zkat/cipm/compare/v0.3.1...v0.3.2) (2017-09-06)


### Bug Fixes

* **bin:** make cli executable by default (#13) ([14a9a5f](https://github.com/zkat/cipm/commit/14a9a5f))
* **config:** use npm.cmd on win32 and fix tests (#12) ([d912d16](https://github.com/zkat/cipm/commit/d912d16)), closes [#12](https://github.com/zkat/cipm/issues/12)
* **json:** strip BOM when reading JSON files (#8) ([2529149](https://github.com/zkat/cipm/commit/2529149))



<a name="0.3.1"></a>
## [0.3.1](https://github.com/zkat/cipm/compare/v0.3.0...v0.3.1) (2017-09-05)



<a name="0.3.0"></a>
# [0.3.0](https://github.com/zkat/cipm/compare/v0.2.0...v0.3.0) (2017-09-05)


### Features

* **lockfile:** verify that lockfile matches package.json (#5) ([f631203](https://github.com/zkat/cipm/commit/f631203))
* **scripts:** support --ignore-scripts option (#9) ([213ca02](https://github.com/zkat/cipm/commit/213ca02))



<a name="0.2.0"></a>
# [0.2.0](https://github.com/zkat/cipm/compare/v0.1.1...v0.2.0) (2017-09-01)


### Bug Fixes

* **main:** default --prefix ([ff06a31](https://github.com/zkat/cipm/commit/ff06a31))


### Features

* **lifecycle:** actually run lifecycle scripts correctly ([7f8933e](https://github.com/zkat/cipm/commit/7f8933e))



<a name="0.1.1"></a>
## [0.1.1](https://github.com/zkat/cipm/compare/v0.1.0...v0.1.1) (2017-08-30)


### Bug Fixes

* **files:** oops. forgot to include new files in tarball ([1ee85c9](https://github.com/zkat/cipm/commit/1ee85c9))



<a name="0.1.0"></a>
# 0.1.0 (2017-08-30)


### Bug Fixes

* **config:** pipe stdout ([08e6af8](https://github.com/zkat/cipm/commit/08e6af8))
* **extract:** make sure to extract properly ([9643583](https://github.com/zkat/cipm/commit/9643583))
* **license:** switch to MIT ([0d10d0d](https://github.com/zkat/cipm/commit/0d10d0d))


### Features

* **impl:** rough prototype ([2970e43](https://github.com/zkat/cipm/commit/2970e43))
* **lifecycle:** Run lifecycle events, implement prefix option, add unit tests (#1) ([d6629be](https://github.com/zkat/cipm/commit/d6629be)), closes [#1](https://github.com/zkat/cipm/issues/1)
* **opts:** add usage string and --help ([efcc48d](https://github.com/zkat/cipm/commit/efcc48d))
