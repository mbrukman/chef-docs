.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

A |cookbook type_wrapper| cookbook modifies the behavior of a |cookbook type_base| cookbook.

Some common charactistics of a |cookbook type_wrapper| cookbook:

* Is often associated 1:1 with a |cookbook type_base| cookbook
* Is never a wrapper around a |cookbook type_wrapper| cookbook
* Is never based on a cookbook that has been forked from |github|
* Typically makes a small number of specific changes within the |cookbook type_wrapper| cookbook, but otherwise makes no changes to the |cookbook type_base| cookbook
* Is often extended to meet organizational requirements, such as adding new recipes, attributes, or custom resources
* Is typically NOT used only to modify |cookbook type_base| cookbook attributes
* Is unique to an organization
* Should follow a naming pattern that includes both the name of the |cookbook type_base| cookbook on which the |cookbook type_wrapper| cookbook is based preceded by a |cookbook type_wrapper| name that is used globally across the organization for all |cookbook type_wrapper| cookbooks, e.g. ``organization_name-library_cookbook_name``
