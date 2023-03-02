# Changelog

## 0.5.0 (2023-03-02)
- Update for rust-discid-sys 0.5

## 0.4.5 (2023-02-28)
- Use latest patch versions for dependencies
- Added submission URL to parsetoc example
- Moved sources to https://git.sr.ht/~phw/rust-discid

## 0.4.4 (2020-11-11)
- Depend on [discid-sys](https://crates.io/crates/discid-sys) 0.4
- Minor documentation fixes

## 0.4.3 (2019-11-10)
- Fixed dependency on [discid-sys](https://crates.io/crates/discid-sys) 0.3

## 0.4.2 (2019-11-08)
- Minor documentation improvements
- Depend on latest [discid-sys](https://crates.io/crates/discid-sys)
- Extended tests

No functional changes

## 0.4.1 (2019-05-19)
- Extended documentation

## 0.4.0 (2019-05-18)
- Added `DiscId::parse(toc)` to create a `DiscId` object directly from a
  given TOC string
- Added example `parsetoc.rs`
- Minor code cleanup

## 0.3.0 (2019-05-07)
- Removed `Features::ALL`, use `Features::all()` instead
- Updated for changes in [discid-sys](https://crates.io/crates/discid-sys) 0.2.0
- Added example `readisrcs.rs`
- Documentation updates

## 0.2.0 (2019-05-06)
- Added `DiscId.tracks()` to get an iterator over all tracks
- Added `DiscId.nth_track(number)` to get details about a single track
- Fixed `DiscId::put` for first track being > 1

## 0.1.0 (2019-05-04)
Initial release with support for most of the libdiscid API.
