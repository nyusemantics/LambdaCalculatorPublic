# Lambda Calculator Change Log

## 2/2021 - 7/2022 (update to version 2.6.0)
### Authors: Raef Khan, Kaustubh Ghoshal, Pinhan Zhao

1. Implemented Commutativity and Associativity
* Made the following operations commutative and associative: And, Or, Iff, Equality, Fusion, Multiplication, Set Union, Set Intersection.

2. Added Bracket Highlighting
* When brackets match, they are highlighted in green. If there are not enough brackets, the mismatched ones will highlight red. 

3. Other bug fixes and features
* Fixed bugs #25 and #28
* Added input symbol for Set Union
* Parser now throws an error when a word is defined multiple times.
* Added brackets around product types to make them more explicit. Product types always bind more tightly than implicit comma. 
* Fixed spacing issue with comma seperator when a composite type has a product type as one of the subtypes.

## 9/2020 - 1/2021 (update to version 2.5.0)
### Authors: Anna Alsop, Raef Khan and Nigel Flower

1. Renamed "Lambda Abstraction" to "Predicate Abstraction"
* This was done to facilitate clarity with the textbook.

2. Fixed bug #23
* Implemented matching with variable types and constant types in student exercises.

3. Removed Save Dialogue on Reload
* In the teacher edition, when reloading a file, the GUI no longer asks the user to save unsaved work.


## 7/2020 - 8/2020 (update to version 2.4.0)
### Authors: Anna Alsop and Raef Khan

1. Function composition
* New function composition rule added (issue #31)

2. Polymorphism revamp
* Polymorphism functionality enhanced for complex variable types

3. Other bug fixes and new features
* Variable types now display as Greek letters
* Reload function made compatible with unsuccessful loads (issue #27)
* Dialog window prompting user to save work before subsequent reload (issue #30)
* After reloading, the same exercise is selected.

## 5/2019 - 8/2019 (update to version 2.3.0)
### Authors: Anna Alsop and Raef Khan

1. Launch4j exe packager 
* Update launch4j
* Bundle java with exe file

2. Other bug fixes and new features
* All instances of primes are now printed as apostrophes
* Addressed issue #2, #21
* Fixed issue #14 (type parser bug)
* Capital letters can now be used for types
* Brought visual display of meaning bracket expressions in line with Coppock & Champollion textbook draft

3. Updates to wiki:
* New navigation menu
* Special Symbols and Exercise File Format pages newly created
* Polymorphism example exercise file added to wiki
* Related Projects section added to LambdaCalculator.com site
* Added override mode documentation to Exercise File Format page
* Exercise files may contain special symbols; documented in Exercise File Format page 

## Previous updates


## 2019-08-26: Version 2.3.0
-------------------------
* fix type parser bug where types could not have two adjacent open brackets '<' (issue # 14)
* new error message generated when a type specification has an extra close bracket '>'
* capital letters can be used for types 
* updated launch4j
* bundle java with exe file

## 2018-09-02: Version 2.2.0
-------------------------

* fix loading of student exercises saved with traces
* add support applying functions with product types
* add support for nested product types
* open window goes to Downloads directory at beginning of session
* open window goes to previous open directory otherwise
* updated "About" window in Mac


## 2015-12-07: Version 2.1.0
-------------------------

* replace [[ ]] with << >>
* choose variables based on indices, eliminating need for (explicitly represented) assignment fns
* functions wrapped in [ ] instead of ( )
* bracketing conventions now match Heim and Kratzer
* add support for *-ed constants
* add individual-level fusion, via +, and part-of, via <: (with Ctrl-: as interactive keyboard shortcut)
* single-letter identifiers off by default (since bound variables are now hardcoded to have multiple characters, e.g. v2)
* eliminate precedence conventions between and/or and if/iff
* infix grouping with [ ] instead of ( )
* apostrophe rather than ? indicates type var (e.g., <'at,t> rather than <?at,t>)

* treat cat nodes above dummy terms as dummies (fixes bug)
* reduce terms in all positions of an arglist (fixes bugs)
* match type vars with functional types to support, e.g., generalized junction (fixes bugs)
* display previous lambda conversion exercises when focused


## 2013-04-01: Version 2.0.0-beta
------------------------------

* Codesigned Mac application to bypass Gatekeeper security checks
* Support for Intensional Function Application
* Traces and indices with arbitrary type specifications
* Export trees to LaTeX
* Support for polymorphic types on functions and arguments


## 2008-03-29: Version 1.0.12
--------------------------

* Fixed alphabetical variants of { x | ... } notation.
* Fixed loading saved exercise files that use the new expression types.

## 2008-03-21: Version 1.0.11
--------------------------

* Treat { x | ... } as a binder.
* In the scratch pad window, when there's a syntax error in the problem statement, move the cursor to the location of the problem.
* Allow the empty set symbol and raw integer numbers to be used in predicate logic expressions.

## 2008-03-20: Version 1.0.10
--------------------------

1. Added to our predicate logic:
	* Set notations { a, b, c } and { ... | ... }.
	* Set intersection, union, subset, proper subset, superset, proper
	* superset, and cardinality.
	* Integer multiplication. This is for the 'most' generalized quantifier.
	* Integer greater than, less than, those + or equal.
2. Added a new example file and updated the documentation for generalized
quantifiers.

## Version 1.0.09
--------------------------

* Allow omega and sigma symbols to be included in logical expressions.
* Improved the naming conventions display for multiple letter identifiers.
* In exercise files, parse multiple letter type conventions.
* Update docs and example file.

## 2008-01-30: Version 1.0.08
--------------------------

* Corrected a problem reading exercise files saved in UTF8 with an initial byte order marker.
* Corrected a problem saving exercise files with meaning brackets.

## 2007-12-12: Version 1.0.07
--------------------------

* Corrected a problem saving exercise files with identifier conventions without explicit description text.
* Fix typo-type mistakes in example2.txt

## Previous releases
gh-pages branch: https://github.com/nyusemantics/LambdaCalculatorPublic/releases
