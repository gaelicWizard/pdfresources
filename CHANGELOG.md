# Changelog
All notable changes to the `pdfmanagement-testphase` bundle since the 
first release 0.95a, 2021-02-23 will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
this project uses date-based 'snapshot' version identifiers.

## [Unreleased]

### Added
- \pdfannot_dict_use:n

### Changed
-

### Removed
- \pdfannot_box:nnnnn: Concept to mix manual specs and dictionaries is wrong.
  This can lead to duplicate entries in the dictionaries.
  
### Fixed
- Wrong default setting of \g_@@_active_bool (issue #13)
- l3pdffile: Wrong casing: FileSpec -> Filespec   

## [2021-02-23]

First release