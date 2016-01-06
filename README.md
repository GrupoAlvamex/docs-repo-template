Rackspace common documentation resources
=========================================

[![Build Status](https://travis-ci.org/rackerlabs/docs-common.svg?branch=master)](https://travis-ci.org/rackerlabs/docs-common)

This repo contains non-product-specific doc source for fragments to be included within multiple documents at http://docs.rackspace.com.

*Nothing here is meant to be publishable on its own.*

When you add a fragment, add a note in this README describing its intended use.
Add the most recent note to the top of the list.


----
2014-11-10 added by Cat Lookabaugh

Moved RBAC fragments from shareddocs repo. 
Chose section_RBAC_2roles or section_RBAC_3roles depending on which roles your product has (admin and observer 
    OR admin, observer and creator).
Replace all "cloudproductabbrev" occurrences with your product name role abbreviation (ie: "cn")
Replace all "cloudproduct" occurrences with your product name (ie: "Cloud Networks").
You can tailor the matrix link in section 1.4 to point to your specific product rather than the high level matrix page.

----
2014-11-05 added by Rose Coste

*model-README-1product.md*

In the GitHub repo for each product's doc, copy this to README.md and customize it as needed to represent that product.

----
2014-07-17 added by Rose Coste

*help-choose-region.xml*

In each API DevGuide, xinclude this in the "Service/Access Endpoints" section to link to guidance about how to choose a region. Place it immediately before the table of available regionalized endpoints.

----
