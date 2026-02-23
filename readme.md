


# libApexCharts

Convertigo NGX builder Project


For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Mobile Application](#mobile-application)
    - [Pages](#pages)
        - [Page](#page)
    - [Shared Components](#shared-components)
        - [apxAreaChart](#apxareachart)
        - [apxBarChart](#apxbarchart)
        - [apxBoxPlotChart](#apxboxplotchart)
        - [apxBubbleChart](#apxbubblechart)
        - [apxCandlestickChart](#apxcandlestickchart)
        - [apxChart](#apxchart)
        - [apxDonutChart](#apxdonutchart)
        - [apxHeatmapChart](#apxheatmapchart)
        - [apxLineChart](#apxlinechart)
        - [apxPieChart](#apxpiechart)
        - [apxPolarAreaChart](#apxpolarareachart)
        - [apxRadarChart](#apxradarchart)
        - [apxRadialBarChart](#apxradialbarchart)
        - [apxRangeAreaChart](#apxrangeareachart)
        - [apxRangeBarChart](#apxrangebarchart)
        - [apxScatterChart](#apxscatterchart)
        - [apxTreemapChart](#apxtreemapchart)


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

#### apxAreaChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">["00h","04h","08h","12h","16h","20h"]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[{"name":"Load","data":[32,40,28,51,42,49]}]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Area chart example"
```

</pre></td>
</tr>
</table>

#### apxBarChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">["Jan","Feb","Mar","Apr","May","Jun"]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">[]
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
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Bar chart example"
```

</pre></td>
</tr>
</table>

#### apxBoxPlotChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[{"type":"boxPlot","data":[{"x":"Jan","y":[54,66,69,75,88]},{"x":"Feb","y":[43,65,69,76,81]},{"x":"Mar","y":[31,39,45,51,59]}]}]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Box plot chart example"
```

</pre></td>
</tr>
</table>

#### apxBubbleChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[{"name":"Bubbles","data":[[20,30,15],[40,10,20],[30,40,12],[10,25,18]]}]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Bubble chart example"
```

</pre></td>
</tr>
</table>

#### apxCandlestickChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[{"data":[{"x":"2026-01-01","y":[34,40,32,38]},{"x":"2026-01-02","y":[38,42,35,40]},{"x":"2026-01-03","y":[40,45,37,43]}]}]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Candlestick chart example"
```

</pre></td>
</tr>
</table>

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

#### apxDonutChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">["Desktop","Mobile","Tablet","Other"]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[35,25,22,18]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Donut chart example"
```

</pre></td>
</tr>
</table>

#### apxHeatmapChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[{"name":"Metric","data":[{"x":"Jan","y":22},{"x":"Feb","y":29},{"x":"Mar","y":13},{"x":"Apr","y":32}]}]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Heatmap chart example"
```

</pre></td>
</tr>
</table>

#### apxLineChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">["W1","W2","W3","W4","W5","W6"]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[{"name":"Signups","data":[5,9,7,11,13,15]},{"name":"Trials","data":[3,5,4,7,8,9]}]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Line chart example"
```

</pre></td>
</tr>
</table>

#### apxPieChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">["Direct","Organic","Ads","Referral"]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[44,55,13,43]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Pie chart example"
```

</pre></td>
</tr>
</table>

#### apxPolarAreaChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">["North","South","East","West"]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[14,23,21,17]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Polar area chart example"
```

</pre></td>
</tr>
</table>

#### apxRadarChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">["Design","Code","Tests","Docs","UX","Ops"]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[{"name":"Score","data":[80,50,30,40,100,20]}]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Radar chart example"
```

</pre></td>
</tr>
</table>

#### apxRadialBarChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">["Progress","Quality","Delivery"]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[67,84,92]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Radial bar chart example"
```

</pre></td>
</tr>
</table>

#### apxRangeAreaChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[{"name":"Range","data":[{"x":"Jan","y":[31,39]},{"x":"Feb","y":[35,44]},{"x":"Mar","y":[33,41]}]}]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Range area chart example"
```

</pre></td>
</tr>
</table>

#### apxRangeBarChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[{"data":[{"x":"Task A","y":[1,5]},{"x":"Task B","y":[3,8]},{"x":"Task C","y":[6,11]}]}]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Range bar chart example"
```

</pre></td>
</tr>
</table>

#### apxScatterChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[{"name":"Points","data":[[10,15],[15,35],[20,22],[25,48],[30,30]]}]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Scatter chart example"
```

</pre></td>
</tr>
</table>

#### apxTreemapChart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>categories</td><td>Defines category labels used on axis-based charts.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>height</td><td>Defines the chart height in pixels.
Example value:
<pre><code class="language-json">320
```

</pre></td>
</tr>
<tr>
<td>labels</td><td>Defines labels used by pie-like chart types.
Example value:
<pre><code class="language-json">[]
```

</pre></td>
</tr>
<tr>
<td>series</td><td>Defines the data series rendered by the chart.
Example value:
<pre><code class="language-json">[{"data":[{"x":"A","y":28},{"x":"B","y":16},{"x":"C","y":9},{"x":"D","y":13}]}]
```

</pre></td>
</tr>
<tr>
<td>themeMode</td><td>Defines the chart theme mode.
Example value:
<pre><code class="language-json">"light"
```

</pre></td>
</tr>
<tr>
<td>title</td><td>Defines the title text displayed above the chart.
Example value:
<pre><code class="language-json">"Treemap chart example"
```

</pre></td>
</tr>
</table>



