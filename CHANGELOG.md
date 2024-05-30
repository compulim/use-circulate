# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Breaking changes

- Moved build tools from Babel to tsup/esbuild

### Changed

- Streamlined code, by [@compulim](https://github.com/compulim) in PR [#5](https://github.com/compulim/use-propagate/pull/5)
- Bumped dependencies, in PR [#11](https://github.com/compulim/use-propagate/pull/11)
   - Production dependencies
      - [`use-ref-from@0.1.0`](https://npmjs.com/package/use-ref-from/v/0.1.0)
   - Development dependencies
      - [`@babel/preset-env@7.24.6`](https://npmjs.com/package/@babel/preset-env/v/7.24.6)
      - [`@babel/preset-react@7.24.6`](https://npmjs.com/package/@babel/preset-react/v/7.24.6)
      - [`@babel/preset-typescript@7.24.6`](https://npmjs.com/package/@babel/preset-typescript/v/7.24.6)
      - [`@testing-library/react@15.0.7`](https://npmjs.com/package/@testing-library/react/v/15.0.7)
      - [`@tsconfig/recommended@1.0.6`](https://npmjs.com/package/@tsconfig/recommended/v/1.0.6)
      - [`@tsconfig/strictest@2.0.5`](https://npmjs.com/package/@tsconfig/strictest/v/2.0.5)
      - [`@types/react@18.3.3`](https://npmjs.com/package/@types/react/v/18.3.3)
      - [`@types/react-dom@18.3.0`](https://npmjs.com/package/@types/react-dom/v/18.3.0)
      - [`esbuild@0.21.4`](https://npmjs.com/package/esbuild/v/0.21.4)
      - [`react@18.3.1`](https://npmjs.com/package/react/v/18.3.1)
      - [`react-dom@18.3.1`](https://npmjs.com/package/react-dom/v/18.3.1)
      - [`react-test-renderer@18.3.1`](https://npmjs.com/package/react-test-renderer/v/18.3.1)
      - [`typescript@5.4.5`](https://npmjs.com/package/typescript/v/5.4.5)

## [0.1.0] - 2024-04-30

### Added

- First public release
- Added `allowPropagateDuringRender` option as a safety measure to prevent multiple re-render, by [@compulim](https://github.com/compulim) in PR [#2](https://github.com/compulim/use-propagate/pull/2)

### Changed

- Relaxed peer dependencies requirements to `react@>=16.8.0`, by [@compulim](https://github.com/compulim) in PR [#1](https://github.com/compulim/use-propagate/pull/1)
- Updated pull request validation to test against various React versions, in PR [#1](https://github.com/compulim/use-propagate/pull/1)
   - Moved from JSX Runtime to JSX Classic to support testing against React 16

[0.1.0]: https://github.com/compulim/use-propagate/releases/tag/v0.1.0
