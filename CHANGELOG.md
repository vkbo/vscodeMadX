# Changelog

## 0.3.2 [2018-01-24] - Bug Fix
* Bug: Moved controls higher up in the hierarchy as some keywords were overriding some controls if they have the same name.

## 0.3.1 [2018-01-11] - Bug Fix and Internal Changes
* Bug: Particle constants were not globally highlighted.
* Some internal changes in style names.
* Added keyword: survey.

## 0.3.0 [2018-01-11] - Functionality and Keyword Additions
* Allows commands to use space as separator in addition to commas.
* Format definitions and file paths (any keyword that is defined as a filename in the manual) are now highlighted as strings (set, format = 24.12g;).
* Math and internal functions are now highlighted when used in control functions (i.e. when used directly with value).
* Macro definitions are now highlighted if the word "macro" is on the same line. Currently does not work if there are any line breaks before "macro".
* Added keywords: exec, endmatch.
* Added control functions: emit, jacobian, lmdif, makethin, match, savebeta, simplex, use_macro.
* Added constants: true, false (how did I miss this?).
* Added singular attributes: chrom, rmatrix.

## 0.2.4 [2018-01-10] - Extended Definition
* Extended recognition of function attributes to allow for numbers in the name

## 0.2.3 [2018-01-10] - Bug Fix
* Accidentally messed up a regex line. Fixed.

## 0.2.2 [2018-01-10] - Added Icon
* Added CERN logo as icon

## 0.2.1 [2018-01-10] - Bug Fix and Readme Update
* Made som minor changes to the Readme
* Rewrote the number regex as it was still not working properly

## 0.2.0 [2017-12-08] - Ported from Atom to VSCode
* Main json file reformatted to match stricter formatting requirements

## 0.1.5 [2017-12-07] - Keyword Addition
* Added keyword aperture to internals

## 0.1.4 [2017-12-06] - Keyword Addition
* Added keyword aperture

## 0.1.3 [2017-11-23] - Bug Fix and Minor Changes
* Added keyword summ
* Fixed bug in number formatting

## 0.1.2 [2017-11-12] - Bug Fix and Minor Changes
* Fixed class typo
* Moved some more patterns into pattern repository
* Added `*.mask` files to fileTypes

## 0.1.1 [2017-11-10] - Bug Fix
* Fixed bug in number formatting

## 0.1.0 [2017-11-10] - Initial Release
* First version of the package
