
# ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/project_color_16x16.png?raw=true "Project") libApexCharts

Convertigo NGX builder Project

<details><summary><span style="color:DarkGoldenRod"><i>Connectors</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/connectors/images/sqlconnector_color_16x16.png?raw=true "SqlConnector") void

void connector, replace or don't use it

<details><summary><span style="color:DarkGoldenRod"><i>Transactions</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/transactions/images/sqltransaction_color_16x16.png?raw=true "SqlTransaction") void

does nothing
</p></blockquote></details>
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Mobile Application</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/mobileapplication_color_16x16.png?raw=true "MobileApplication") Application

Describes the mobile application global properties

<details><summary><span style="color:DarkGoldenRod"><i>Pages</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/pagecomponent_color_16x16.png?raw=true "PageComponent") Page

A simple example to show apex chart usage
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Shared Components</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uisharedcomponent_16x16.png?raw=true "UISharedRegularComponent") apxChart



<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;annotations
</td>
<td>
Defines annotation markers and labels displayed on chart points or axes.
Example value:
<pre><code class="language-json">{"yaxis":[{"y":42,"borderColor":"#ff4560","label":{"text":"Target"}}]}
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;chart
</td>
<td>
Defines the "chart" input of the shared ApexCharts component.
Example value:
<pre><code class="language-json">{"type":"bar","height":320,"toolbar":{"show":false}}
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;colors
</td>
<td>
Defines the "colors" input of the shared ApexCharts component.
Example value:
<pre><code class="language-json">["#2563eb","#0ea5e9","#22c55e"]
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;dataLabels
</td>
<td>
Defines data label visibility and style options.
Example value:
<pre><code class="language-json">{"enabled":true,"style":{"fontSize":"12px","fontWeight":"bold"}}
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;fill
</td>
<td>
Defines fill style such as solid or gradient.
Example value:
<pre><code class="language-json">{"type":"gradient","gradient":{"shadeIntensity":0.4,"opacityFrom":0.8,"opacityTo":0.2}}
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;grid
</td>
<td>
Defines chart grid visibility and style.
Example value:
<pre><code class="language-json">{"show":true,"strokeDashArray":4}
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;labels
</td>
<td>
Defines category labels for charts such as pie or donut.
Example value:
<pre><code class="language-json">["Direct","Organic","Ads","Referral"]
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;legend
</td>
<td>
Defines legend behavior and placement.
Example value:
<pre><code class="language-json">{"show":true,"position":"bottom"}
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;plotOptions
</td>
<td>
Defines type-specific rendering options.
Example value:
<pre><code class="language-json">{"bar":{"horizontal":false,"columnWidth":"50%"}}
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;responsive
</td>
<td>
Defines chart options overridden for specific breakpoints.
Example value:
<pre><code class="language-json">[{"breakpoint":768,"options":{"legend":{"position":"bottom"}}}]
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;series
</td>
<td>
Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[{"name":"Revenue","data":[12,18,15,22,28,24]}]
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;states
</td>
<td>
Defines hover and active visual states.
Example value:
<pre><code class="language-json">{"hover":{"filter":{"type":"lighten","value":0.1}}}
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;stroke
</td>
<td>
Defines line or area stroke style.
Example value:
<pre><code class="language-json">{"curve":"smooth","width":2}
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;subtitle
</td>
<td>
Defines an optional subtitle displayed under the title.
Example value:
<pre><code class="language-json">{"text":"FY 2026 - first half","align":"left"}
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;theme
</td>
<td>
Defines chart theme and color palette mode.
Example value:
<pre><code class="language-json">{"mode":"dark","palette":"palette4"}
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;title
</td>
<td>
Defines the main chart title.
Example value:
<pre><code class="language-json">{"text":"Monthly revenue","align":"left"}
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;tooltip
</td>
<td>
Defines tooltip display options.
Example value:
<pre><code class="language-json">{"enabled":true,"shared":true}
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;xaxis
</td>
<td>
Defines x-axis categories and labels.
Example value:
<pre><code class="language-json">{"categories":["Jan","Feb","Mar","Apr","May","Jun"]}
```

</pre>
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;yaxis
</td>
<td>
Defines y-axis scale and label formatting.
Example value:
<pre><code class="language-json">{"min":0,"max":100,"tickAmount":5}
```

</pre>
</td>
</tr>
</table>

</p></blockquote></details>
</p></blockquote></details>
