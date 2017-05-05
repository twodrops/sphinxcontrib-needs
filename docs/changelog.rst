Changelog
=========

0.1.20
------

* Bugfix for custom needs_types: Parameter in conf.py was not taken into account.

0.1.19
------

* Added configuration parameter :ref:`needs_id_required`.
* Backwards compatibility changes:

 * Reimplemented **needlist** as alias for :ref:`needfilter`
 * Added *need* directive/need as part of the default :ref:`need_types` configuration.

0.1.18
------

**Initial start for the changelog**

* Free definable need types (Requirements, Bugs, Tests, Employees, ...)
* Allowing configuration of needs with a

 * directive name
 * meaningful title
 * prefix for generated IDs
 * color

* Added **needfilter** directive
* Added layouts for needfilter:

 * list (default)
 * table
 * diagram (based on plantuml)

* Integrated interaction with the activated plantuml sphinx extension

* Added role **need** to create a reference to a need by giving the id