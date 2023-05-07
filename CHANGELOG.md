# Changelog

All notable changes to this project will be documented in this file.  
The format is based on [Keep a Changelog] and this project adheres to [Semantic Versioning].

## [next] - 2.1.1.2

## [2.1.1.1] - 2023-03-31
### Changed
- Update upstream version from **2.1.0** to **2.1.1**

## [2.1.0.2] - 2022-01-10
### Fixed
- Fix compilation issues with `Qt >= 6.2.0` (thanks to _miccs_ on thread forum [qt 6.2 patch][path-qt-6.2])

## [2.1.0.1] - 2022-01-10

Creation of the repository which provides :
- **QCustomPlot** library compliant with _Cmake_ projects (`.pro` file has been replaced by `CMakeLists.txt`)
- Hide _Qt dependencies_, callers no longer needed to add mandatory modules of the library in their own _CMakeLists_ project (like `printsupport` module for example)
- Add a `config.h` file, generated at CMake step, in order to know which version of the library we are using from the caller project (multiple macros are defined, like `QCP_LIB_VERSION` for example).

<!-- Links -->
[keep a changelog]: https://keepachangelog.com/en/1.0.0/
[semantic versioning]: https://semver.org/spec/v2.0.0.html

<!-- Versions -->
[next]: https://github.com/legerch/QCustomPlot-library/compare/2.1.1.1...dev

[2.1.1.1]: https://github.com/legerch/QCustomPlot-library/compare/2.1.0.2...2.1.1.1
[2.1.0.2]: https://github.com/legerch/QCustomPlot-library/compare/2.1.0.1...2.1.0.2
[2.1.0.1]: https://github.com/legerch/QCustomPlot-library/releases/tag/2.1.0.1

<!-- Links to patches -->
[path-qt-6.2]: https://www.qcustomplot.com/index.php/support/forum/2380