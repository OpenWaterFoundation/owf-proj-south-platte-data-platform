# South Platte Data Platform / Stories #

Stories within the South Platte Data Platform consist of multiple datasets and visualizations integrated in a way
that provides context and perspective, in order to educate and illustrate about water resource issues.
Stories are intended to integrate data and science with human connection in order to achieve greater understanding and dialogue.

* [Stories of Interest](#stories-of-interest)
* [Potential Technologies](#potential-technologies)

---------------

## Stories of Interest ##

Stories of interest to South Platte Roundtable stakeholders include the following.
These stories are being evaluated to focus on a subset that can be achieved with available
data and other resources.
**Perhaps need to use bold to indicate stories and story components that are priorities?**

1. Agricultural
	1. Story:  Return flows - significance in South Platte
		1. What happens to returns when agriculture gets more efficient?
		2. Extract data from [StateMod South Platte model](http://cdss.state.co.us/Modeling/Pages/SurfaceWaterStateMod.aspx)
		3. Use [Source Water Route Framework](http://cdss.state.co.us/GIS/Pages/AllGISData.aspx) for stream segments
		4. Also can link to [Visual South Platte](http://www.lspwcd.org/index_files/POINTFLOW2.htm)
		5. Display acreage served by sprinklers above a point on river?
		6. Display returns at points on river
		7. One or more case studies at specific locations showing change over time
		8. Visualize "water colors" such as natural flow, reservoir release, return flows
	2. Story:  Irrigated agriculture change over time
		1. [Animation of irrigated lands](http://viz.openwaterfoundation.org/co/co-irrigated-ag-animation/index.html)
		2. Agriculture peaked in 1970s and has been declining since
		3. Where is dry-up occurring?
	3. Story:  ATMs - adoption and effectiveness for addressing water supply gap
		1. Show locations on maps - need public ATM dataset from CWCB or someone else
		2. Link to studies, operations documents, etc. - need public ATM dataset from CWCB or someone else
2. Municipal
	1. Story:  Population historical trends and forecasts
		1. Locations of [municipalities](https://github.com/OpenWaterFoundation/owf-data-co-municipalities/blob/master/data/Colorado-Municipalities.geojson) and
		[municipal water providers](https://github.com/OpenWaterFoundation/owf-data-co-municipal-water-providers/blob/master/data/Colorado-Municipal-Water-Providers.geojson)
		2. Population historical trends by city, county
	2. Story:  Change in water use efficiency
		1. Links to websites, conservation/efficiency plans
		2. Highlight success stories (Denver Water, others)
		3. Use [HB 1051 data](http://cwcb.state.co.us/water-management/waterEfficiency/Pages/ReportingWaterUseWaterConservationData.aspx).
3. Environmental & Recreational
	1. Story:  River health
		1. OWF has been working on a [river health visualization tool - see Eagle River example](http://viz.openwaterfoundation.org/co/owf-viz-co-eagle-river-health-sunburst/)
		2. Need to grind some existing South Platte data into format used by this tool
	2. Story:  Duck Flyover recharge and habitat from same project
		1. Recharge locations - need project location data from DU or SWSI E&R results?
		2. Explain benefits for duck flyovers
		3. Explain trends - dependency on corn?
	3. Story:  Importance of recreation in the basin
		1. Map showing camping areas, other recreation - need from CPW
		2. Display dataset of
		[outfitters and stream reaches](https://github.com/OpenWaterFoundation/owf-data-co-river-outfitters/blob/master/data/Colorado-River-Outfitters.geojson) - need
		better public dataset from outfitters
4. Industrial
	1. Story: Largest use types
		1. Energy?
		2. [Breweries](https://github.com/OpenWaterFoundation/owf-data-co-breweries)?  Case study?
5. Other stories
	1. Story:  Change in water availability over past 40-50 years
		1. Extract data from [StateMod South Platte dataset](http://cdss.state.co.us/Modeling/Pages/SurfaceWaterStateMod.aspx)
		2. Display natural and available flow from model
		3. Display wet/dry/average years
		4. What is SWSI base supply scenario versus hydrology?
		5. Change in snowpack.  [See map](http://projects.openwaterfoundation.org/owf-proj-co-cwcb-2016-snodas/prototype/index.html).
		[See animation for water years](http://viz.openwaterfoundation.org/co/owf-viz-co-snodas-gapminder/).
		6. [Transbasin diversions?](https://github.com/OpenWaterFoundation/owf-data-co-transbasin-diversions)
	2. Story:  Projects to address gap
		1. [Maps of IPP locations](https://github.com/OpenWaterFoundation/swsi-data-ipps) (private), and characteristics of IPPs
		2. Map showing master plan extent in river basins - could be difficult to get the spatial data
	3. Story: Aquifer storage and recovery (ASR)
		1. What is story?

## Potential Technologies ##

The following are technologies that are being evaluated to implement stories.

* [ArcGIS Story Maps](https://storymaps.arcgis.com/en/)
* [Observable](https://beta.observablehq.com/?utm_source=blocks) - story notebooks based on [D3.js](https://d3js.org/)
* [Scrolling web application layout](https://startbootstrap.com/template-overviews/scrolling-nav/)

Considerations for using a specific technology include:

* Compatibility of solution with State of Colorado IT environment
* Hosting cost
* Ability to automate data uploads (so that story content can be updated over time)
* Implementation effort
* Integration with version control (so that content changes can be tracked)
