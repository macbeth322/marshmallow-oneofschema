Changelog
---------

2.0.0b2 (2018-10-25)
++++++++++++++++++++

Features :

- Port to marshmallow 3b19

Deprecations/Removals:

- Drop Python 3.4

2.0.0b1 (2018-10-16)
++++++++++++++++++++

Features :

- Port to marshmallow 3b18
- Support Python 3.5, 3.6 and 3.7

Bug fixes:

- Return type in dump() for objects without any attributes (PR #16)
- Restore support for schema context (PR #10)

Deprecations/Removals:

- Drop marshmallow 2 compatibility
- Drop Python 2.6 and 3.3

1.0.5 (2017-06-20)
++++++++++++++++++

- Report error during load if "type" value is unhashable

1.0.4 (2017-04-25)
++++++++++++++++++

- Add option to leave type field on load

1.0.3 (2016-11-04)
++++++++++++++++++

- Add support for raising errors when schema is strict
- Remove type field from data on load

1.0.2 (2016-08-11)
++++++++++++++++++

- Fix bug with ignoring "partial" constructor argument

1.0.1 (2016-08-11)
++++++++++++++++++

- Fix bug with ignoring "many" constructor argument
- Fix code example in README

1.0 (2016-03-14)
++++++++++++++++

- Initial release.
