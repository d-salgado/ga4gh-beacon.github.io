---
title: BiosampleResponse
layout: default
date: 2020-05-25
permalink: "/schemas/beacon-v2/BiosampleResponse.html"
sb_status: "playground"
excerpt_separator: <!--more-->
category:
  - schemas
tags:
  - code
  - specification
  - v2
  - playground
  - beacon-v2
---

<div id="schema-header-title">
  <h2>BiosampleResponse <span id="schema-header-title-project">[beacon-v2] <a href="https://github.com/ga4gh-beacon/specification-v2-test-schemas" target="_BLANK">&nearr;</a></span> </h2>
</div>

<table id="schema-header-table">
  <tr>
    <th>{S}[B] Status Level <a href="https://schemablocks.org/about/sb-status-levels.html">[i]</a></th>
    <td><div id="schema-header-status">playground</div></td>
  </tr>

  <tr>
    <th>Provenance</th>
    <td>
      <ul>
<li><a href="https://github.com/ga4gh-beacon/specification-v2">Beacon v2 draft schema</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Used by</th>
    <td>
      <ul>
<li><a href="https://github.com/ga4gh-beacon/specification-v2">Beacon, for Beacon v2 testing</a></li>
      </ul>
    </td>
  </tr>

<!--more-->

  <tr>
    <th>Contributors</th>
    <td>
      <ul>
<li><a href="https://beacon-project.io/categories/people.html">ELIXIR Beacon team</a></li>
<li><a href="https://beacon-project.io/people/Sabela-de-la-Torre/">Sabela de la Torre Pernas</a></li>
<li><a href="https://beacon-project.io/people/Jordi-Rambla/">Jordi Rambla De Argila</a></li>
<li><a href="https://orcid.org/0000-0002-9903-4248">Michael Baudis</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Source (2.0.0-draft.1)</th>
    <td>
      <ul>
        <li><a href="current/BiosampleResponse.json" target="_BLANK">raw source [JSON]</a></li>
        <li><a href="https://github.com/ga4gh-beacon/specification-v2-test-schemas/blob/master/schemas/BiosampleResponse.yaml" target="_BLANK">Github</a></li>
      </ul>
    </td>
  </tr>
</table>

<div id="schema-attributes-title">
  <h3>Attributes</h3>
</div>

  
__Type:__ object  
__Description:__ Response of a query over biosamples.

### Properties

<table id="schema-properties-table">
  <tr>
    <th>Property</th>
    <th>Type</th>
  </tr>
  <tr>
    <th>meta</th>
    <td>./ResponseMeta [<a href="./ResponseMeta.html" target="_BLANK">HTML</a>]</td>
  </tr>
  <tr>
    <th>response</th>
    <td>./BiosampleResponseContent [<a href="./BiosampleResponseContent.html" target="_BLANK">HTML</a>]</td>
  </tr>

</table>


#### meta

* type: ./ResponseMeta [<a href="./ResponseMeta.html" target="_BLANK">HTML</a>]




#### response

* type: ./BiosampleResponseContent [<a href="./BiosampleResponseContent.html" target="_BLANK">HTML</a>]



<hr/>
<div id="schema-footer">
This schema representation is for information and testing purposes. The authorative 
version remains with the main Beacon development project.
</div>


