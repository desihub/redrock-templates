# redrock-templates

## Version 0.9.0 (unreleased)

* No changes yet.

## Version 0.8.1 (2023-12-01)

Note: this tag should only be used with redrock tag 0.17.9

This is a tag of the "opticaldepth" branch used by Allyson Brodzeller
to re-process Iron production z>1.6 QSOs with a new HIZ template and
updated optical depth coefficients to match Kamble et al. 2020
(Arxiv: 1904.01110) in redrock tag 0.17.9.

This branch will not be merged into main as-is, but the updated template
will be added to main as part of 0.9.0 and a more general refactor to
support multiple template versions in a single tag.

* Updated rrtemplate-qso-HIZ.fits with QSO models built with an optical depth
  correction applied while training the templates.

## Version 0.8 (2022-08-08)

* New QSO templates split into two redshift ranges,
  PR [#10](https://github.com/desihub/redrock-templates/pull/10).

## Version 0.7.1 (2020-01-29)

* Add module file, PR [#9](https://github.com/desihub/redrock-templates/pull/9).
* No changes to data files.

## Version 0.7 (2018-09-26)

* Add Missing lines to templates,
  PR [#8](https://github.com/desihub/redrock-templates/pull/8).
* Fix HDU issue in QSO templates,
  PR [#6](https://github.com/desihub/redrock-templates/pull/6).
* Remove some unnecessary templates,
  PR [#5](https://github.com/desihub/redrock-templates/pull/5).

## Version 0.6 (2018-05-10)

* Expanded rrtemplate-star-WD.fits training to include DA and DB subtypes,
  PR [#4](https://github.com/desihub/redrock-templates/pull/4).

## Version 0.5 (2018-02-23)

* Added rrtemplate-star-Ldwarf.fits, rrtemplate-star-Carbon.fits,
  rrtemplate-star-WD.fits, PR [#2](https://github.com/desihub/redrock-templates/pull/2).

## Version 0.4 (2018-01-31)

* Updated stellar templates with more input diversity,
  PR [#1](https://github.com/desihub/redrock-templates/pull/1).
