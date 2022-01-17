+++
author = "Matthew Goldman"
categories = ["Home", "water", "drought", "california"]
date = 2016-01-24T12:35:00Z
description = ""
draft = false
image = "__GHOST_URL__/content/images/2017/02/front-yard.JPG"
slug = "water-usage-in-the-drought"
tags = ["Home", "water", "drought", "california"]
title = "Water Usage in The Drought"

+++


As a New Mexican, water conservation has been a part of my life since well before California's recent drought. Yet, despite best efforts, I have had a hard time decreasing usage, until recently.

Although my records don't last the entire time I've lived in my current house, I do have more than two years of utility bills handy to review my usage. As you can see in the chart, only in the past few months have I made significant year-over-year progress.

<div id="chartContainer" style="height: 420px; width: 100%;"></div>
<script src="http://canvasjs.com/assets/script/canvasjs.min.js"></script>
<script>
	var chart= new CanvasJS.Chart("chartContainer", {
	    title:{
	        text: "Water Usage Over Time"
	    },
           legend: { fontFamily: "Arial" },
	    axisY2: {
	        includeZero: false,
	        title: "Year-Over-Year Change (%)"
	    },
	    axisY: {        
	        title: "Hundred Cubic Feet of Water Per Two Month Billing Cycle"
	    },
	    data: [
	    {
	        type: "line", 
                showInLegend: true, 
                name: "series1",
                legendText: "HCF Used",       
	        dataPoints: [
	            { x: new Date(2012, 12, 28), y: 18 },            
	            { x: new Date(2013, 02, 27), y: 19 },
				{ x: new Date(2013, 04, 29), y: 32 },
				{ x: new Date(2013, 06, 27), y: 32 },
				{ x: new Date(2013, 08, 28), y: 43 },
				{ x: new Date(2013, 10, 28), y: 40 },
				{ x: new Date(2013, 12, 30), y: 25 },
				{ x: new Date(2014, 02, 27), y: 23 },
				{ x: new Date(2014, 04, 28), y: 22 },
				{ x: new Date(2014, 06, 27), y: 45 },
				{ x: new Date(2014, 08, 28), y: 48 },
				{ x: new Date(2014, 10, 29), y: 43 },
				{ x: new Date(2014, 12, 30), y: 25 },
				{ x: new Date(2015, 02, 27), y: 19 },
				{ x: new Date(2015, 04, 29), y: 19 },
				{ x: new Date(2015, 06, 29), y: 36 },
				{ x: new Date(2015, 08, 28), y: 26 },
	            { x: new Date(2015, 10, 28), y: 27 },
				{ x: new Date(2015, 12, 29), y: 19 }
	        ]
	    },
	    {
	        type: "line",
                showInLegend: true, 
                name: "series2",
                legendText: "Year-over-Year Change (%)",
	        axisYType: "secondary",
	        dataPoints: [        
				{ x: new Date(2013, 12, 30), y: 33 },
				{ x: new Date(2014, 02, 27), y: 26 },
				{ x: new Date(2014, 04, 28), y: -29 },
				{ x: new Date(2014, 06, 27), y: 39 },
				{ x: new Date(2014, 08, 28), y: 12 },
				{ x: new Date(2014, 10, 29), y: 5 },
				{ x: new Date(2014, 12, 30), y: 0 },
				{ x: new Date(2015, 02, 27), y: -18 },
				{ x: new Date(2015, 04, 29), y: -16 },
				{ x: new Date(2015, 06, 29), y: -21 },
				{ x: new Date(2015, 08, 28), y: -44 },
	            { x: new Date(2015, 10, 28), y: -36 },
				{ x: new Date(2015, 12, 29), y: -23 }
	        ]
	    }
	    ]


	});
	chart.render();
	</script>


Before the chart went down we did a number of things:

* Install rain barrels
* Convert to rotor sprinkler heads from spray
* Convert some sprinklers to drip where appropriate
* Continually attempt to adjust the schedule
* Converted our curb to xeriscape/drought-tolerant

Last year, we noticed a very significant issue wherein it turned out our sprinkler controller would go off, quite randomly. The latest in Internet-connected controllers weren't ready, so we had our landscapers put in a "smart" device.

The new controller:

* Doesn't go off randomly
* Has soil type and sprinkler type intelligence
* Has a moisture detector to turn-off during rain, etc.

This had a significant impact on improving (decreasing) water usage. It was easy to turn off in the rare case of rain, and didn't run excessively (once we figured it out, that took a while).

This fall, we also converted 75% of our front yard to xeriscape. The remaining 25% is UC Davis Verde Buffalo grass, which is a hybrid designed to be low water (once established).

As you can see from the chart above, this has had a significant impact so far. We're excited to see this continue and contribute to the 28% Pasadena goal. We aren't hitting that goal every month, but we're doing pretty well, I think.

As a side note, this is really being done for environmental reasons. The cost of converting to drought tolerant (including a new walkway in the front) would take years and year to make back in water savings. Water is still very cheap.

