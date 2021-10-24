---
title: version_name
slug: Mozilla/Add-ons/WebExtensions/manifest.json/version_name
tags:
  - Add-ons
  - Extensions
  - WebExtensions
browser-compat: webextensions.manifest.version_name
---
<p>{{AddonSidebar}}</p>

<table class="fullwidth-table standard-table">
 <tbody>
  <tr>
   <th scope="row">Type</th>
   <td><code>String</code></td>
  </tr>
  <tr>
   <th scope="row">Mandatory</th>
   <td>No</td>
  </tr>
  <tr>
   <th scope="row">Example</th>
   <td>
    <pre class="brush: json">
"version_name": "0.1 beta"</pre>
   </td>
  </tr>
 </tbody>
</table>

<p>In addition to the <a href="/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/version">version</a> field, which is used for update purposes, <a href="https://developer.chrome.com/extensions/manifest/version">version_name</a> can be set to a descriptive version string and will be used for display purposes if present.</p>

<p>If no <strong>version_name</strong> is present, the <strong>version</strong> field will be used for display purposes as well.</p>

<h2 id="Browser_compatibility">Browser compatibility</h2>

<p>{{Compat}}</p>