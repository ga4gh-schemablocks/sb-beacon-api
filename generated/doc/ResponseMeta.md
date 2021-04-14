
<div id="schema-header-title">
  <h2><span id="schema-header-title-project">beacon-v2</span> ResponseMeta <a href="https://github.com/ga4gh-beacon/sb-beacon-api" target="_BLANK">[ &nearr; ]</a></h2>
</div>

<table id="schema-header-table">
<tr>
<th>{S}[B] Status <a href="https://schemablocks.org/about/sb-status-levels.html">[i]</a></th>
<td><div id="schema-header-status">proposed</div></td>
</tr>
<tr><th>Provenance</th><td><ul>
<li><a href="https://github.com/ga4gh-beacon/specification-v2">Beacon v2</a></li>
</ul></td></tr>
<tr><th>Used by</th><td><ul>
<li><a href="https://github.com/progenetix/schemas/">Progenetix database schema (Beacon+ backend)</a></li>
</ul></td></tr>


<!--more-->
<tr><th>Contributors</th><td><ul>
<li><a href="https://beacon-project.io/categories/people.html">ELIXIR Beacon project team</a></li>
<li><a href="https://github.com/jrambla">Jordi Rambla</a></li>
<li><a href="https://github.com/sdelatorrep">Sabele de la Torre</a></li>
<li><a href="https://github.com/mamanambiya">Mamana Mbiyavanga</a></li>
<li><a href="https://orcid.org/0000-0002-9903-4248">Michael Baudis</a></li>
</ul></td></tr>
<tr><th>Source (2.0.0-draft.3)</th><td><ul>
<li><a href="current/ResponseMeta.json" target="_BLANK">raw source [JSON]</a></li>
<li><a href="https://github.com/ga4gh-beacon/sb-beacon-api/blob/master/schemas/ResponseMeta.yaml" target="_BLANK">Github</a></li>
</ul></td></tr>
</table>

<div id="schema-attributes-title"><h3>Attributes</h3></div>

  
__Type:__ object  
__Description:__ Meta information about the reponse.

### Properties

<table id="schema-properties-table">
<tr><th>Property</th><th>Type</th></tr>
<tr><th>apiVersion</th><td>string</td></tr>
<tr><th>beaconId</th><td>string</td></tr>
<tr><th>receivedRequest</th><td>Request.yaml#/ [<a href="./Request.html">HTML</a>]</td></tr>
<tr><th>returnedSchemas</th><td>RequestedSchemas.yaml#/ [<a href="./RequestedSchemas.html">HTML</a>]</td></tr>
</table>


#### apiVersion

* type: string

Version of the API. If specified, the value must match `apiVersion` in Beacon


#### beaconId

* type: string

Identifier of the beacon, as defined in `Beacon`.



#### receivedRequest

* type: Request.yaml#/ [<a href="./Request.html">HTML</a>]




#### returnedSchemas

* type: RequestedSchemas.yaml#/ [<a href="./RequestedSchemas.html">HTML</a>]




