<h1>ACF Field Types</h1>
<br>

<h3>True / False</h3>
<p>Type: <code>true_false</code>
<p><strong>Options:</strong></p>
<table>
<thead>
<td><strong>Name</strong></td>
<td><strong>Value</strong></td>
<td><strong>Default</strong></td>
</thead>
<tr><td><code>default_value</code></td><td> <code>0</code> Disbaled or <code>1</code> Enabled</td><td><code>0</code></td></tr>
<tr><td><code>message</code></td><td> String</td><td><code>''</code></td></tr>
<tr><td><code>ui</code></td><td> <code>0</code> Disbaled or <code>1</code> Enabled</td><td><code>0</code></td></tr>
<tr><td><code>ui_on_text</code></td><td>  String </td><td><code>''</code></td></tr>
<tr><td><code>ui_off_text</code></td><td>  String </td><td><code>''</code></td></tr>
</table>

<br>

<h3>Post Object</h3>
<p>Type: <code>post_object</code>
<p><strong>Options:</strong></p>
<table>
<thead>
<td><strong>Name</strong></td>
<td><strong>Value</strong></td>
<td><strong>Default</strong></td>
</thead>
<tr><td><code>post_type</code></td><td> array </td><td>empty array</td></tr>
<tr><td><code>taxonomy</code></td><td> array </td><td>empty array</td></tr>
<tr><td><code>allow_null</code></td><td> <code>0</code> Disbaled or <code>1</code> Enabled</td><td><code>0</code></td></tr>
<tr><td><code>multiple</code></td><td> <code>0</code> Disbaled or <code>1</code> Enabled</td><td><code>0</code></td></tr>
<tr><td><code>return_format</code></td><td><code>object</code> or <code>id</code></td><td><code>object</code></td></tr>
<tr><td><code>ui</code></td><td> <code>0</code> Disbaled or <code>1</code> Enabled</td><td><code>0</code></td></tr>
</table>

<br>

<h3>Repeater</h3>
<p>Type: <code>repeater</code>
<p><strong>Options:</strong></p>
<table>
<thead>
<td><strong>Name</strong></td>
<td><strong>Value</strong></td>
<td><strong>Default</strong></td>
</thead>
<tr><td><code>sub_fields</code></td><td> array </td><td>empty array</td></tr>
<tr><td><code>layout</code></td><td> table/block/row </td><td>table</td></tr>
<tr><td><code>min</code></td><td> Min number of rows </td><td><code>null</code></td></tr>
<tr><td><code>max</code></td><td> Max number of rows </td><td><code>null</code></td></tr>
</table>
