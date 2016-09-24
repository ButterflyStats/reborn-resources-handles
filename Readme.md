Dota 2 Resource Lookup
======================

This repository contains an auto-generated `resources.json` lookup table for all VMLD and VPCF files used in Dota 2.

Format
------

The file is layed out like this:

    {
        "time": "<Time when this file was generated>",
        "entries": {
            "<Hash of resource>": "<Path to resource>",
            "<.......>"...
         }
     }

Usage
-----

Import `resources.json` into your program. That's it

Generating
----------

The code that generates this file is part of a larger non-public project at the moment and can't be copied out easily.
See the following blog post for an explanation on how you can generate the data yourself, includes source code: http://invokr.org/reverse-engineering-dota2-resource-handles.html
