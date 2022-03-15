# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

[Unreleased]: https://github.com/Nugine/rlimit/v0.7.0...HEAD

## [0.7.0] - 2022-02-13

[0.7.0]: https://github.com/Nugine/rlimit/compare/v0.6.2...v0.7.0

### Added

+ Windows support
  + [rlimit::getmaxstdio](https://docs.rs/rlimit/0.7.0/rlimit/fn.getmaxstdio.html)
  + [rlimit::setmaxstdio](https://docs.rs/rlimit/0.7.0/rlimit/fn.stdmaxstdio.html)

### Changed

+ [rlimit::utils::increase_nofile_limit] in v0.6.2 has been moved to [rlimit::increase_nofile_limit].

[rlimit::utils::increase_nofile_limit]: https://docs.rs/rlimit/0.6.2/rlimit/utils/fn.increase_nofile_limit.html

[rlimit::increase_nofile_limit]: https://docs.rs/rlimit/0.7.0/rlimit/fn.increase_nofile_limit.html

### Removed

+ [rlimit::utils::get_kern_max_files_per_proc] has been removed from public interfaces.

[rlimit::utils::get_kern_max_files_per_proc]: https://docs.rs/rlimit/0.6.2/x86_64-apple-darwin/rlimit/utils/fn.get_kern_max_files_per_proc.html