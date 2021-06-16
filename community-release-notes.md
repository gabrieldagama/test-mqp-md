---
group: software-update-guide
title: Magento Quality Patches release notes
functional_areas:
  - Setup
  - Configuration
  - Upgrade
---

The [Magento Community Quality Patches](https://github.com/magento/quality-patches) package delivers individual patches developed by Magento and allows you to apply, revert, and view general information about all individual patches that are available for the installed version of {{ site.data.var.ee }} or {{ site.data.var.ce }}.

<!-- The release notes include:

-  {:.new}New features
-  {:.fix}Fixes and improvements
-  {:.bug}Known issues -->

{:.bs-callout-info}
See [Apply patches]({{ site.baseurl }}/guides/v2.4/comp-mgr/patching/mqp.html) for instructions on applying patches to your Magento projects.
See [Patches available in MQP tool](https://support.magento.com/hc/en-us/sections/360010506631-Patches-available-in-MQP-tool-) for additional patch details.

## v1.0
    
-  **MDVA-37478** _(for Magento `>=2.3.0 <=2.3.7`)_-Fixes the issue where Magento throws an error when creating a partial invoice for orders placed with the "Payment on Account" payment method through REST API.
-  **MDVA-37362** _(for Magento `>=2.3.4 <=2.4.2-p1`)_-Fixes the issue where configurable product option values and variant attribute values were empty in GraphQL response.
-  **MDVA-37288** _(for Magento `2.4.2`)_-Fixes the issue where wrong tier prices were returned after GraphQL request.
-  **MDVA-37225** _(for Magento `>=2.4.1 <=2.4.2-p1`)_-Fixes the issue where the upload process is stuck during quick order creation when there is an integer value in imported SKUs.
-  **MDVA-37224** _(for Magento `>=2.3.3 <=2.4.2-p1`)_-Fixes the issue where customers cannot pay for negotiable quote with PayFlow Pro with another product in the cart.
-  **MDVA-36286** _(for Magento `>=2.3.6 <=2.4.2-p1`)_-Fixes the issue where Page Builder products widget preview breaks if the same SKU has a different position in subcategories.
-  **MDVA-30186** _(for Magento `>=2.3.4 <=2.3.5-p2, >=2.4.0 <=2.4.0-p1, >=2.4.2 <=2.4.2-p1`)_-Fixes the issue where attribute options are sorted by option value instead of attribute item count, in GraphQL response.
