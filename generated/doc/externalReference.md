
<div id="schema-header-title">
  <h2><span id="schema-header-title-project">sb-beacon-api</span> ExternalReference <a href="https://github.com/ga4gh-schemablocks/sb-beacon-api" target="_BLANK">[ &nearr; ]</a></h2>
</div>

<table id="schema-header-table">
<tr>
<th>{S}[B] Status <a href="https://schemablocks.org/about/sb-status-levels.html">[i]</a></th>
<td><div id="schema-header-status">proposed</div></td>
</tr>
<tr><th>Provenance</th><td><ul>
<li><a href="https://github.com/ga4gh-beacon/beacon-v2">Beacon v2</a></li>
<li><a href="http://docs.genomebeacons.org">Beacon v2 documentation</a></li>
</ul></td></tr>
<tr><th>Used by</th><td><ul>
<li><a href="https://ga4gh-approval-service-registry.ega-archive.org">Beacon v2 frontline implementers</a></li>
<li><a href="https://docs.progenetix.org/beaconplus/">Progenetix database schema (Beacon+ backend)</a></li>
</ul></td></tr>


<!--more-->
<tr><th>Contributors</th><td><ul>
<li><a href="https://beacon-project.io/categories/people.html">ELIXIR Beacon project team</a></li>
</ul></td></tr>
<tr><th>Source (2.0.0)</th><td><ul>
<li><a href="current/externalReference.json" target="_BLANK">raw source [JSON]</a></li>
<li><a href="https://github.com/ga4gh-schemablocks/sb-beacon-api/blob/master/schemas/beacon-v2-default-model/common/externalReference.yaml" target="_BLANK">Github</a></li>
</ul></td></tr>
</table>

<div id="schema-attributes-title"><h3>Attributes</h3></div>

  
__Type:__ object  
__Description:__ Definition of an external reference class. Provenance: GA4GH Phenopackets v2 `ExternalReference`
### Properties

<table id="schema-properties-table">
<tr><th>Property</th><th>Type</th></tr>
<tr><th>id</th><td>string</td></tr>
<tr><th>notes</th><td>string</td></tr>
<tr><th>reference</th><td>string</td></tr>
</table>


#### id

* type: string

An application specific identifier. RECOMMENDED.

##### `id` Value Example  

```
"PMID:34054918"
```

#### notes

* type: string

An optional text descriptor. Renamed compared to GA4GH Phenopackets v2 `ExternalReference.description`

##### `notes` Value Example  

```
"Signatures of Discriminative Copy Number Aberrations in 31 Cancer Subtypes"
```

#### reference

* type: string

A url.

##### `reference` Value Example  

```
"https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8155688/"
```

