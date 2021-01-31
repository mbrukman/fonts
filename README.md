# Fonts

A curated collection of interesting and useful font families, along with
relevant references. Fonts which are available with liberal licenses for
distribution are included in this repo.

## Font families

* [M+](families/Mplus)
* [TeX Gyre](families/TeX_Gyre)

## Motivation

A number of font-hosting sites tend to be imprecise about the license for the
fonts, sometimes just saying "OK for personal use" or "OK for personal and
commercial use", but without actually linking to the exact license for the
consumer to make their own determination whether the license is compatible with
their use case.

Some sites obscure the licensing of all fonts, even open source ones, and refer
all visitors to paid font hosting providers, possibly because they receive a
referral fee, without letting you know that some fonts are free (and you can
host them yourself), or pointing to a free font hosting provider.

Additionally, a number of sites don't link back to the source of their font
files, whether that might be the type foundry or the authors, thus obscuring the
original source.

This project aims to fix a number of these issues by providing all relevant
source and licensing information, as well as availability of these fonts on
other sites.

## License stats

<!--
  TODO(mbrukman): record font metadata in machine-readable format and automate
  the update of this table
-->

Here's a manual snapshot of license counts for the font families that are
currently included in the [`third_party`](third_party) directory:

| License                     | Count |
|-----------------------------|-------|
| GUST Font License (GFL)     |   1   |
| SIL Open Font License (OFL) |   1   |
| Custom                      |   1   |

Note that this does not include all font families that are discussed or
mentioned in this repository, just the font families whose font files are
themselves directly provided in this repository.

## License

This project is under multiple licenses:

* [Apache 2.0](APACHE-2.0.txt) for code
* [Creative Commons Attribution 4.0 International](CC-BY-4.0.txt) for
  documentation and everything else

Note that these licenses do not apply to any content that is:

* within the [`third_party`](third_party) directory tree, where each project
  has their own license provided in each directory
* quoted from another project, e.g., a project author's description of
  their project, which is under the license of that third-party project

For clarity, [`LICENSE.txt`](LICENSE.txt) includes both licenses in their
entirety and these details.
