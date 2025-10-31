==========================
Measurement Set v4 Schemas
==========================

This repository is a partial fork of xradio that contains
base schema definition code as well as the Measurement v4.0
schema definitions based ontop of this.
In particular the following file globs are applied:

- LICENSE.txt
- CONTRIBUTOR_LICENSING_AGREEMENT.txt
- CONTRIBUTOR_LICENSING_AGREEMENT_ESO.txt
- schemas/*.json
- src/xradio/schema/*
- src/xradio/measurement_set/schema.py
- tests/unit/schema/*


The aim of this fork is to minimise the dependencies required
to validate xarray structures against the schema.
An install of xradio 1.0.2 can be around 950MB, for example,
most of which is unnecessary for performing schema validation.

In practice, only the xarray and typeguard dependencies are
strictly required for schema checking.

Attribution
===========

This code is largely derived from the xradio repository by
applying `git-filter-repo <https://github.com/newren/git-filter-repo>`__.
This maintains the commit history by the original authors
for the included files but actual commit hashes will vary
as the repository is rewritten.

LICENSES
========

The original xradio BSD3 license is included in LICENSE.txt.
Additionally, src/schemas/xarray_dataclasses_license.txt
contains the xarray-dataclasses license on which the schema
creation and validation code was based.

