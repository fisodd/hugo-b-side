+++
title = "Configuring Hugo B-side"
author = "Alexander Carlton"
description = "What settings are available for Hugo B-side."
date = "Sat Dec 30 22:23:34 PST 2017"
categories = ["Demo"]
tags = ["config", "theme", "Hugo"]
weight = 5

+++

.. contents::
   :class: sidebar

#######################
Configuring Hugo B-side
#######################

The templates in this theme do utilize several settings
from the site's "config.toml" file and from each page's front matter.


Page Types
**********

:title:`Hugo B-side` recognizes two page types:
"post" and "wide".
The "post" articles will be given the main-and-margin look
(two columns, a main column and a margin for notes and such).
The "wide" articles will be given a simpler single-column look
(sidebar notes, if any, will be still be displayed, just
will be set into smaller boxes around which the main text
will be wrapped).
In basic usage, the "post" format works for the articles,
and the "wide" format works for the "list" index views.


Article Information
*******************

The "list" display for listing designated articles
and the "single" display for showing an article in full
both use several values pulled from the "config.toml" file
or from the designated pages' front matter.


Title
=====

As usual, the page title is taken from Hugo's ``.Title`` value
which is the string set for the "title" setting in the front matter
(or, for the home page, possibly set in "config.toml")


Description
===========

The "list" templates will use the value of the "description" setting
as part of the information provided with the link to the page.

If there is no value for "description", then the templates will
use the default extraction from the beginning of the page's content.


Author
======

If set, the "author" value will be added to the article's description
in the list displays |--| along with the date and
the categories and tags taxonomy values.


.. |--| unicode:: U+2013   .. en dash

