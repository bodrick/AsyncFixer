# Release History

## 1.4.0 (2021-01)
- UnnecessaryAsync analyzer: Fix false warnings with `using` expression statements
- UnnecessaryAsync analyzer: Support for expression-bodied members
- BlockingCallInsideAsync analyzer: Stop suggesting async calls from non-system assemblies

## 1.3.0 (2020-05)
- Updated Roslyn dependencies to v3.3.1.
- Fixed several performance bugs.

## 1.1.7 (2019-04)
- Fixed bugs in code-fixes.

## 1.1.5 (2017-02)
- Added a license. 
- Changed nuspec as a development dependency. 
- Fixed several bugs in fixing anti-patterns.

## 1.1.4 (2016-09)
- Fixed false positives.

## 1.1.3 (2016-03)
- Depending on CodeAnalysis 1.0.0 instead of 1.1.1 due to compatibility issues for some users.

## 1.1.2 (2016-03)
- Fixed false positives for new analyzers.

## 1.1.0 (2016-03)
- Added 2 new code analyzers and improved accuracy of existing analyzers.

## 1.0.0 (2015-07)
- 3 code analyzers to detect and fix very common async anti-patterns.