# Changelog

## [0.1.2](https://github.com/wangela/react-google-maps/compare/v0.3.3...v0.1.2) (2023-11-29)


### ⚠ BREAKING CHANGES

* removed MapProps.onLoadMap
* loading multiple libraries at once is no longer supported, changed the return type of useMapsLibrary.

### Features

* Allow &lt;Pin&gt; glyphs to be passed as children (close [#98](https://github.com/wangela/react-google-maps/issues/98)) ([#99](https://github.com/wangela/react-google-maps/issues/99)) ([6374453](https://github.com/wangela/react-google-maps/commit/637445313c8c9364cbf1f32346d3438fc0589d74))
* cleanup map, remove onLoadMap prop ([d5e7dfd](https://github.com/wangela/react-google-maps/commit/d5e7dfdf74d76395ffbc1bcd2afda62a12eb7e57))
* implement dynamic library loading ([f71c158](https://github.com/wangela/react-google-maps/commit/f71c158b356176bdbaaef7afa6c3d1852021d960))
* implement props for all map-events with custom MapEvent type ([820a301](https://github.com/wangela/react-google-maps/commit/820a301e4a30e2b7bbbe7c82c69675f9c410813e))
* new MapControl component ([#51](https://github.com/wangela/react-google-maps/issues/51)) ([7eb49ed](https://github.com/wangela/react-google-maps/commit/7eb49ed55eb548c342f83bcdbf9dc655655bafe7))
* standalone examples (CodeSandbox) ([#48](https://github.com/wangela/react-google-maps/issues/48)) ([959c6e3](https://github.com/wangela/react-google-maps/commit/959c6e3d57d896d4f76640e01b3ad0a33dea3fae))
* update map viewport when props are changed ([0b1d800](https://github.com/wangela/react-google-maps/commit/0b1d800dc5e4b9bf0b1ddb42b9fed392b23b8dae))
* useMapsLibrary returns API object instead of boolean ([#26](https://github.com/wangela/react-google-maps/issues/26)) ([a3aa4c5](https://github.com/wangela/react-google-maps/commit/a3aa4c5e10228003206c8de3305f857df50d73d1))


### Bug Fixes

* add map camera state tracking ([#84](https://github.com/wangela/react-google-maps/issues/84)) ([1dc1584](https://github.com/wangela/react-google-maps/commit/1dc158436c4ffde60548486da5410b46e989fc5b))
* add types to package exports ([#62](https://github.com/wangela/react-google-maps/issues/62)) ([1ab493a](https://github.com/wangela/react-google-maps/commit/1ab493a71ddaeff3b31caec10be1fd4728d51362))
* empty commit to trigger release-please ([b04a942](https://github.com/wangela/react-google-maps/commit/b04a9421fc290c3ca6eacc02391726beab4bba4b))
* **map:** (un)register map instance without id ([c4c443c](https://github.com/wangela/react-google-maps/commit/c4c443c3166b4950a7e3f798132f254e6f8c5fa6))
* **map:** fix changing the map-id ([d97cae9](https://github.com/wangela/react-google-maps/commit/d97cae9ded0de30604e543d78341984cb61de942))
* markers not removed in strict mode ([#15](https://github.com/wangela/react-google-maps/issues/15)) ([6c4244a](https://github.com/wangela/react-google-maps/commit/6c4244afee3b315690d271dd88133c8a86bd1f13)), closes [#14](https://github.com/wangela/react-google-maps/issues/14)
* prepare for first publishing ([4186441](https://github.com/wangela/react-google-maps/commit/41864413e606bd41ed2d6ae77829d33d4439a59f))
* replace prop `gmpDraggable` with `draggable` in AdvancedMarker ([#53](https://github.com/wangela/react-google-maps/issues/53)) ([1dbf477](https://github.com/wangela/react-google-maps/commit/1dbf477dfa2e471edf9a9daacd5e5e384a48d8de))
* update ControlPosition values ([#71](https://github.com/wangela/react-google-maps/issues/71)) ([1dd144a](https://github.com/wangela/react-google-maps/commit/1dd144ac3deac53a77d870ba8cf1e4623786a620))
* update usage of useMapsLibrary in AdvancedMarker ([#55](https://github.com/wangela/react-google-maps/issues/55)) ([b01fc8b](https://github.com/wangela/react-google-maps/commit/b01fc8bbafae569fbb21a3175deb5b66762eb083))
* use moveCamera and useLayoutEffect for faster map-updates ([e493d5f](https://github.com/wangela/react-google-maps/commit/e493d5ffa350efebddd5ef63bb57495954478877))


### Miscellaneous Chores

* add registry-url to release action ([9fa403b](https://github.com/wangela/react-google-maps/commit/9fa403bd4d6dfc31b84683543868b0bfbe70e2b9))

## [0.3.3](https://github.com/visgl/react-google-maps/compare/v0.3.2...v0.3.3) (2023-11-13)


### Bug Fixes

* add map camera state tracking ([#84](https://github.com/visgl/react-google-maps/issues/84)) ([1dc1584](https://github.com/visgl/react-google-maps/commit/1dc158436c4ffde60548486da5410b46e989fc5b))

## [0.3.2](https://github.com/visgl/react-google-maps/compare/v0.3.1...v0.3.2) (2023-11-09)


### Bug Fixes

* use moveCamera and useLayoutEffect for faster map-updates ([e493d5f](https://github.com/visgl/react-google-maps/commit/e493d5ffa350efebddd5ef63bb57495954478877))

## [0.3.1](https://github.com/visgl/react-google-maps/compare/v0.3.0...v0.3.1) (2023-11-09)


### Bug Fixes

* update ControlPosition values ([#71](https://github.com/visgl/react-google-maps/issues/71)) ([1dd144a](https://github.com/visgl/react-google-maps/commit/1dd144ac3deac53a77d870ba8cf1e4623786a620))

## [0.3.0](https://github.com/visgl/react-google-maps/compare/v0.2.1...v0.3.0) (2023-11-09)


### ⚠ BREAKING CHANGES

* removed MapProps.onLoadMap

### Features

* cleanup map, remove onLoadMap prop ([d5e7dfd](https://github.com/visgl/react-google-maps/commit/d5e7dfdf74d76395ffbc1bcd2afda62a12eb7e57))
* implement props for all map-events with custom MapEvent type ([820a301](https://github.com/visgl/react-google-maps/commit/820a301e4a30e2b7bbbe7c82c69675f9c410813e))
* update map viewport when props are changed ([0b1d800](https://github.com/visgl/react-google-maps/commit/0b1d800dc5e4b9bf0b1ddb42b9fed392b23b8dae))

## [0.2.1](https://github.com/visgl/react-google-maps/compare/v0.2.0...v0.2.1) (2023-11-07)


### Bug Fixes

* add types to package exports ([#62](https://github.com/visgl/react-google-maps/issues/62)) ([1ab493a](https://github.com/visgl/react-google-maps/commit/1ab493a71ddaeff3b31caec10be1fd4728d51362))

## [0.2.0](https://github.com/visgl/react-google-maps/compare/v0.1.2...v0.2.0) (2023-11-07)


### Features

* new MapControl component ([#51](https://github.com/visgl/react-google-maps/issues/51)) ([7eb49ed](https://github.com/visgl/react-google-maps/commit/7eb49ed55eb548c342f83bcdbf9dc655655bafe7))
* standalone examples (CodeSandbox) ([#48](https://github.com/visgl/react-google-maps/issues/48)) ([959c6e3](https://github.com/visgl/react-google-maps/commit/959c6e3d57d896d4f76640e01b3ad0a33dea3fae))


### Bug Fixes

* replace prop `gmpDraggable` with `draggable` in AdvancedMarker ([#53](https://github.com/visgl/react-google-maps/issues/53)) ([1dbf477](https://github.com/visgl/react-google-maps/commit/1dbf477dfa2e471edf9a9daacd5e5e384a48d8de))
* update usage of useMapsLibrary in AdvancedMarker ([#55](https://github.com/visgl/react-google-maps/issues/55)) ([b01fc8b](https://github.com/visgl/react-google-maps/commit/b01fc8bbafae569fbb21a3175deb5b66762eb083))

## [0.1.2](https://github.com/visgl/react-google-maps/compare/v0.1.1...v0.1.2) (2023-11-01)


### Miscellaneous Chores

* add registry-url to release action ([9fa403b](https://github.com/visgl/react-google-maps/commit/9fa403bd4d6dfc31b84683543868b0bfbe70e2b9))

## [0.1.1](https://github.com/visgl/react-google-maps/compare/v0.1.0...v0.1.1) (2023-11-01)


### Bug Fixes

* empty commit to trigger release-please ([b04a942](https://github.com/visgl/react-google-maps/commit/b04a9421fc290c3ca6eacc02391726beab4bba4b))

## [0.1.0](https://github.com/visgl/react-google-maps/compare/v0.0.5...v0.1.0) (2023-10-27)


### ⚠ BREAKING CHANGES

* loading multiple libraries at once is no longer supported, changed the return type of useMapsLibrary.

### Features

* useMapsLibrary returns API object instead of boolean ([#26](https://github.com/visgl/react-google-maps/issues/26)) ([a3aa4c5](https://github.com/visgl/react-google-maps/commit/a3aa4c5e10228003206c8de3305f857df50d73d1))
