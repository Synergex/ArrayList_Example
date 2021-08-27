README for ArrayList example

Description
-----------

The source files enclosed in this zip files are:

SynArrayList.dbl
Example of extending a simple ArrayList, so it can use Synergy Alpha types as
data.  Also includes methods not implemented in Synergy (standard) ArrayList

SynArrayList_main.dbl
A simple test program for SynArrayList

SortArrayList.dbl
Subroutines that will take a standard ArrayList, and sort the ArrayList as if
it were filled with Synergy Alpha types


To build
--------

dblproto *.dbl
dbl SynArrayList_main SynArrayList SortArrayList
dblink SynArrayList_main


Modification history
--------------------

17th Feb 2011
  Initial version


Submission details
------------------

Author:                 William Hawkins
Company:                Synergex
Email:                  william.hawkins@synergex.com
Date:                   17th Feb 2011
Minimum version:        v9.1.5
Platforms:              OpenVMS or Unix or Windows

