---
template: sidebyside
title: DCP Alias
anchor: dcp_alias
---

Aliases are used to link each customer ID in your [Tables](#dcp_tables) to an
Optimizely User ID.  The Optimizely User ID is a random ID generated by Optimizely (stored in the `optimizelyEndUserId` cookie).

<img src="/assets/img/dcp/alias.png">

As shown in the figure, an alias indicates that the *same customer* is identified by `ANON_ID_1` in "My Datasource" and
by `OEU_2` in the "Optimizely Datasource".  This allows Optimizely to present a
[consolidated customer profile](#consolidated-profile)
for that customer and allows you to target customers based on all of your Table Attributes.

<div class="attention attention--warning push--bottom">
These APIs that follow use the domain https://vis.optimizely.com/api/
</div>
