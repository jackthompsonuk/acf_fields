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
<tr><td><code>layout</code></td><td> <code>table</code> / <code>block</code> / <code>row</code> </td><td>table</td></tr>
<tr><td><code>min</code></td><td> int or null </td><td><code>null</code></td></tr>
<tr><td><code>max</code></td><td> int or null </td><td><code>null</code></td></tr>
</table>

<br>

<h3>Wysiwyg</h3>
<p>Type: <code>wysiwyg</code>
<p><strong>Options:</strong></p>
<table>
<thead>
<td><strong>Name</strong></td>
<td><strong>Value</strong></td>
<td><strong>Default</strong></td>
</thead>
<tr><td><code>tabs</code></td><td> <code>all</code> / <code>visual</code> / <code>text</code> </td><td><code>all</code></td></tr>
<tr><td><code>toolbar</code></td><td> <code>full</code> / <code>basic</code> </td><td><code>full</code></td></tr>
<tr><td><code>media_upload</code></td><td> <code>0</code> Disbaled or <code>1</code> Enabled </td><td><code>1</code></td></tr>
</table>

<br>

<h3>Select</h3>
<p>Type: <code>select</code>
<p><strong>Options:</strong></p>
<table>
<thead>
<td><strong>Name</strong></td>
<td><strong>Value</strong></td>
<td><strong>Default</strong></td>
</thead>
<tr><td><code>choices</code></td><td> array </td><td>empty array</td></tr>
<tr><td><code>allow_null</code></td><td> <code>0</code> Disbaled or <code>1</code> Enabled</td><td><code>0</code></td></tr>
<tr><td><code>multiple</code></td><td> <code>0</code> Disbaled or <code>1</code> Enabled</td><td><code>0</code></td></tr>
<tr><td><code>return_format</code></td><td><code>value</code> / <code>label</code> / <code>both</code></td><td><code>value</code></td></tr>
<tr><td><code>ui</code></td><td> <code>0</code> Disbaled or <code>1</code> Enabled</td><td><code>0</code></td></tr>
</table>
