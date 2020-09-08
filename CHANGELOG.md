# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## 0.3.2 - 2020-09-08

### Fixed

- Remove custom TypeScript module declarations from project for simplicity

## 0.3.1 - 2020-09-08

### Fixed

- Copy local TypeScript module declarations into `dist`

## 0.3.0 - 2020-09-07

### Fixed

- Improve error handling. New implementation does not error out early if a
  single whois call fails to resolve.

### Changed

- Updated integration to SDK v3