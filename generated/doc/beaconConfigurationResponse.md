
<div id="schema-header-title">
  <h2><span id="schema-header-title-project">sb-beacon-api</span> beaconConfigurationResponse <a href="https://github.com/ga4gh-schemablocks/sb-beacon-api" target="_BLANK">[ &nearr; ]</a></h2>
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
<li><a href="current/beaconConfigurationResponse.json" target="_BLANK">raw source [JSON]</a></li>
<li><a href="https://github.com/ga4gh-schemablocks/sb-beacon-api/blob/master/schemas/framework/responses/beaconConfigurationResponse.yaml" target="_BLANK">Github</a></li>
</ul></td></tr>
</table>

<div id="schema-attributes-title"><h3>Attributes</h3></div>

  
__Type:__ object  
__Description:__ Information about the Beacon. Aimed to Beacon clients like web pages or Beacon networks.
### Properties

<table id="schema-properties-table">
<tr><th>Property</th><th>Type</th></tr>
<tr><th>meta</th><td>https://raw.githubusercontent.com/ga4gh-beacon/beacon-v2/main/framework/json/responses/sections/beaconInformationalResponseMeta.json [<a href="https://raw.githubusercontent.com/ga4gh-beacon/beacon-v2/main/framework/json/responses/sections/beaconInformationalResponseMeta.json">LINK</a>]</td></tr>
<tr><th>response</th><td>https://raw.githubusercontent.com/ga4gh-beacon/beacon-v2/main/framework/json/configuration/beaconConfigurationSchema.json [<a href="https://raw.githubusercontent.com/ga4gh-beacon/beacon-v2/main/framework/json/configuration/beaconConfigurationSchema.json">LINK</a>]</td></tr>
</table>


#### meta

* type: https://raw.githubusercontent.com/ga4gh-beacon/beacon-v2/main/framework/json/responses/sections/beaconInformationalResponseMeta.json [<a href="https://raw.githubusercontent.com/ga4gh-beacon/beacon-v2/main/framework/json/responses/sections/beaconInformationalResponseMeta.json">LINK</a>]

Information about the response that could be relevant for the Beacon client in order to interpret the results.


#### response

* type: https://raw.githubusercontent.com/ga4gh-beacon/beacon-v2/main/framework/json/configuration/beaconConfigurationSchema.json [<a href="https://raw.githubusercontent.com/ga4gh-beacon/beacon-v2/main/framework/json/configuration/beaconConfigurationSchema.json">LINK</a>]

Returning the Beacon configuration.


