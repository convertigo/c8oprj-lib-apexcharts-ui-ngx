


# libApexCharts

Convertigo NGX builder Project


For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Mobile Application](#mobile-application)
    - [Pages](#pages)
        - [Page](#page)
    - [Shared Components](#shared-components)
        - [apxChart](#apxchart)


## Installation

1. In your Convertigo Studio click on ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/icons/studio/project_import.gif?raw=true "Import a project in treeview") to import a project in the treeview
2. In the import wizard

   ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/tomcat/webapps/convertigo/templates/ftl/project_import_wzd.png?raw=true "Import Project")
   
   paste the text below into the `Project remote URL` field:
   <table>
     <tr><td>Usage</td><td>Click the copy button at the end of the line</td></tr>
     <tr><td>To contribute</td><td>

     ```
     libApexCharts=https://github.com/convertigo/c8oprj-lib-apexcharts-ui-ngx.git:branch=8.4.0.0
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     libApexCharts=https://github.com/convertigo/c8oprj-lib-apexcharts-ui-ngx/archive/8.4.0.0.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __libApexCharts__ project


## Mobile Application

Describes the mobile application global properties

### Pages

#### Page

A simple example to show apex chart usage

### Shared Components

#### apxChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>annotations</td><td>Defines annotation markers and labels displayed on chart points or axes.
Example value:
<pre><code class="language-json">{"yaxis":[{"y":42,"borderColor":"#ff4560","label":{"text":"Target"}}]}
```

</pre></td>
</tr>
<tr>
<td>chart</td><td>Defines the "chart" input of the shared ApexCharts component.
Example value:
<pre><code class="language-json">{"type":"bar","height":320,"toolbar":{"show":false}}
```

</pre></td>
</tr>
<tr>
<td>colors</td><td>Defines the "colors" input of the shared ApexCharts component.
Example value:
<pre><code class="language-json">["#2563eb","#0ea5e9","#22c55e"]
```

</pre></td>
</tr>
<tr>
<td>dataLabels</td><td>Defines data label visibility and style options.
Example value:
<pre><code class="language-json">{"enabled":true,"style":{"fontSize":"12px","fontWeight":"bold"}}
```

</pre></td>
</tr>
<tr>
<td>fill</td><td>Defines fill style such as solid or gradient.
Example value:
<pre><code class="language-json">{"type":"gradient","gradient":{"shadeIntensity":0.4,"opacityFrom":0.8,"opacityTo":0.2}}
```

</pre></td>
</tr>
<tr>
<td>grid</td><td>Defines chart grid visibility and style.
Example value:
<pre><code class="language-json">{"show":true,"strokeDashArray":4}
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines category labels for charts such as pie or donut.
Example value:
<pre><code class="language-json">["Direct","Organic","Ads","Referral"]
```

</pre></td>
</tr>
<tr>
<td>legend</td><td>Defines legend behavior and placement.
Example value:
<pre><code class="language-json">{"show":true,"position":"bottom"}
```

</pre></td>
</tr>
<tr>
<td>plotOptions</td><td>Defines type-specific rendering options.
Example value:
<pre><code class="language-json">{"bar":{"horizontal":false,"columnWidth":"50%"}}
```

</pre></td>
</tr>
<tr>
<td>responsive</td><td>Defines chart options overridden for specific breakpoints.
Example value:
<pre><code class="language-json">[{"breakpoint":768,"options":{"legend":{"position":"bottom"}}}]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[{"name":"Revenue","data":[12,18,15,22,28,24]}]
```

</pre></td>
</tr>
<tr>
<td>states</td><td>Defines hover and active visual states.
Example value:
<pre><code class="language-json">{"hover":{"filter":{"type":"lighten","value":0.1}}}
```

</pre></td>
</tr>
<tr>
<td>stroke</td><td>Defines line or area stroke style.
Example value:
<pre><code class="language-json">{"curve":"smooth","width":2}
```

</pre></td>
</tr>
<tr>
<td>subtitle</td><td>Defines an optional subtitle displayed under the title.
Example value:
<pre><code class="language-json">{"text":"FY 2026 - first half","align":"left"}
```

</pre></td>
</tr>
<tr>
<td>theme</td><td>Defines chart theme and color palette mode.
Example value:
<pre><code class="language-json">{"mode":"dark","palette":"palette4"}
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the main chart title.
Example value:
<pre><code class="language-json">{"text":"Monthly revenue","align":"left"}
```

</pre></td>
</tr>
<tr>
<td>tooltip</td><td>Defines tooltip display options.
Example value:
<pre><code class="language-json">{"enabled":true,"shared":true}
```

</pre></td>
</tr>
<tr>
<td>xaxis</td><td>Defines x-axis categories and labels.
Example value:
<pre><code class="language-json">{"categories":["Jan","Feb","Mar","Apr","May","Jun"]}
```

</pre></td>
</tr>
<tr>
<td>yaxis</td><td>Defines y-axis scale and label formatting.
Example value:
<pre><code class="language-json">{"min":0,"max":100,"tickAmount":5}
```

</pre></td>
</tr>
</table>



