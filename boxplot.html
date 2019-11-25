<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Boxplots</title>
    <script src="https://d3js.org/d3.v5.min.js"></script>
  </head>

	<body>

		<div style="padding: 50px; float:left;">
		</div>

		<div id="chart" style="width: 400px; float:left;">
			<h3>Create a boxplot</h3>
			<p>Click in the center of the blue strip to add points.</p>
		</div>

		<div id="summary" style="width: 400px; float: left;">
			<h3>How to Read a Boxplot</h3>
			<p>[add text here]</p> 
		</div>
		
		
		<script type="text/javascript">

			//Add or Remove Form
			d3.select("#chart").append("form").attr("id", "selection");

			d3.select("form").append("input")
				.attr("type", "radio")
				.attr("id", "add")
				.attr("name", "mode");

			d3.select("form").append("label")
				.attr("for", "add")
				.text("Add");

			d3.select("form").append("input")
				.attr("type", "radio")
				.attr("id", "remove")
				.attr("name", "mode");

			d3.select("form").append("label")
				.attr("for", "remove")
				.text("Remove");

			TOTALWIDTH = 300;
			TOTALHEIGHT = 400;

			LINENUMBERSXMARGIN = 0.02
			LINEXMARGIN = 0.12; //Should be less enough than GRAPHXMARGIN to allow for scale text
			GRAPHXMARGIN = 0.20;
			INNERRECTXMARGIN = 0.3;
			GRAPHVERTICALMARGIN = 0.12;


			d3.select("#chart").append("svg").attr("width",TOTALWIDTH).attr("height",TOTALHEIGHT);

			graphy = TOTALHEIGHT*GRAPHVERTICALMARGIN
			graphx = TOTALWIDTH*GRAPHXMARGIN
			graphwidth = TOTALWIDTH*(1-2*GRAPHXMARGIN)
			graphheight = TOTALHEIGHT*(1-2*GRAPHVERTICALMARGIN)
			
			d3.select("svg").append("rect")
				.attr("width", TOTALWIDTH).attr("height", TOTALHEIGHT)
				.attr("x", 0).attr("y", 0)
				.attr("fill", "yellow");

			d3.select("svg").append("rect")
				.attr("width", graphwidth).attr("height", graphheight)
				.attr("x", graphx).attr("y", graphy)
				.attr("fill", "lightgreen");

			linex = TOTALWIDTH*LINEXMARGIN;
			d3.select("svg").append("line")
				.attr("x1", linex).attr("y1", graphy)
				.attr("x2", linex).attr("y2", graphy + graphheight)
				.attr("style", "stroke:rgb(0,0,0);stroke-width:2");

			scalenumbersx = TOTALWIDTH*LINENUMBERSXMARGIN;
			ygap = graphheight/4;
			for (i = 0; i < 5; i++) {
				num = 100 - 50*i;
				d3.select("svg").append("text")
					.text(num)
					.attr("x",scalenumbersx).attr("y",graphy + ygap*i);
			}

			innerrectx = TOTALWIDTH*INNERRECTXMARGIN;
			innerrectwidth = TOTALWIDTH*(1-2*INNERRECTXMARGIN);
			boxwidth =  TOTALWIDTH*(1-2*INNERRECTXMARGIN);
			d3.select("svg").append("rect")
				.attr("x", innerrectx).attr("y", graphy)
				.attr("width", innerrectwidth).attr("height", graphheight)
				.attr("fill", "aquamarine")
				.attr("id", "innerrect");

			seconddiv = d3.select("#summary");

		      seconddiv.append("p").text("Data values: ").attr("id", "DataValues");
		      seconddiv.append("p").text("Outliers:").attr("id", "Outliers");
		      seconddiv.append("p").text("Upper whisker:").attr("id", "UpperWhisker");
		      seconddiv.append("p").text("Q3:").attr("id", "Q3");
		      seconddiv.append("p").text("Median:").attr("id", "Median");
		      seconddiv.append("p").text("Q1:").attr("id", "Q1");
		      seconddiv.append("p").text("Lower whisker:").attr("id", "LowerWhisker");


			  d3.select("svg").append("line").attr("x1", 0)
                        .attr("y1", 0)
                    	.attr("x2", 0)
                    	.attr("y2", 0).attr("style", "stroke:rgb(255,0,0);stroke-width:2").attr("id","BoxUp");

				d3.select("svg").append("line").attr("x1", 0)
                        .attr("y1", 0)
                    	.attr("x2", 0)
						.attr("y2", 0).attr("style", "stroke:rgb(255,0,0);stroke-width:2").attr("id","BoxDown");
					
				d3.select("svg").append("line").attr("x1", 0)
                        .attr("y1", 0)
                    	.attr("x2", 0)
						.attr("y2", 0).attr("style", "stroke:rgb(255,0,0);stroke-width:2").attr("id","BoxLeft");

				d3.select("svg").append("line").attr("x1", 0)
                        .attr("y1", 0)
                    	.attr("x2", 0)
						.attr("y2", 0).attr("style", "stroke:rgb(255,0,0);stroke-width:2").attr("id","BoxRight");

				d3.select("svg").append("line").attr("x1", 0)
					.attr("y1", 0)
					.attr("x2", 0)
					.attr("y2", 0).attr("style", "stroke:rgb(255,0,0);stroke-width:2").attr("id","Median");

				d3.select("svg").append("line").attr("x1", 0)
					.attr("y1", 0)
					.attr("x2", 0)
					.attr("y2", 0).attr("style", "stroke:rgb(255,0,0);stroke-width:2").attr("id","UpperStem");

				d3.select("svg").append("line").attr("x1", 0)
					.attr("y1", 0)
					.attr("x2", 0)
					.attr("y2", 0).attr("style", "stroke:rgb(255,0,0);stroke-width:2").attr("id","LowerStem");

				d3.select("svg").append("line").attr("x1", 0)
					.attr("y1", 0)
					.attr("x2", 0)
					.attr("y2", 0).attr("style", "stroke:rgb(255,0,0);stroke-width:2").attr("id","UpperWhisker");
				
				d3.select("svg").append("line").attr("x1", 0)
					.attr("y1", 0)
					.attr("x2", 0)
					.attr("y2", 0).attr("style", "stroke:rgb(255,0,0);stroke-width:2").attr("id","LowerWhisker");

		    function scalecoords(ycoord){
				return 100-(ycoord-graphy)*200/(graphheight)
			}
			
			function inversescale(datvalue){
				return graphy + (100-datvalue)*graphheight/200;
			}

		    function sumstats(datavalues){
		    	datavalues.sort(d3.ascending);
				var q1 = d3.quantile(datavalues, 0.25);
				var q2 = d3.quantile(datavalues, 0.5);
				var q3 = d3.quantile(datavalues, 0.75);

				var iqr = q3-q1;
				var lowhinge = q1 - 1.5*iqr;
				var upperhinge = q3 + 1.5*iqr;

				outliers = datavalues.filter(function(a) {
					return a < lowhinge || a > upperhinge;
				})
				var filtereddatavalues = datavalues.filter(function(a) {
					return a >= lowhinge && a <= upperhinge;
				});

				var minval = Math.min.apply(Math, filtereddatavalues);
				var maxval = Math.max.apply(Math, filtereddatavalues);

				return [minval, q1, q2, q3, maxval, outliers];
		    }

			function updateStats(datavalues){
				var mystats = sumstats(datavalues);
				var minval = mystats[0];
				var q1 = mystats[1];
				var q2 = mystats[2];
				var q3 = mystats[3];
				var maxval = mystats[4];
				var outliers = mystats[5];

				seconddiv.select("#DataValues").text("Data Values: " + datavalues.map(Math.round).join(", "));
				seconddiv.select("#Outliers").text("Outliers: " + outliers.map(Math.round).join(", "));
				seconddiv.select("#UpperWhisker").text("Upper whisker: " + Math.round(maxval));
				seconddiv.select("#LowerWhisker").text("Lower whisker: " + Math.round(minval));
				seconddiv.select("#Median").text("Median: " + Math.round(q2));
				seconddiv.select("#Q1").text("Q1: " + Math.round(q1));
				seconddiv.select("#Q3").text("Q3: " + Math.round(q3));

				var points = Array.from(d3.select("svg").selectAll("circle")._groups)[0];

				for (index=0; index < points.length; index++){
					point = points[index];
					point.setAttribute("fill", "black");
				}

				for (index=0; index < points.length; index++){
					point = points[index];
					datavalue = scalecoords(point.getAttribute("cy"));
					if (datavalue < q1 - (q3-q1)*1.5 || datavalue > q3 + (q3-q1)*1.5){
						point.setAttribute("fill", "red");
					}
				}
			}

			function drawbox(datavalues){
				var mystats = sumstats(datavalues);
				var minval = inversescale(mystats[0]);
				var q1 = inversescale(mystats[1]);
				var q2 = inversescale(mystats[2]);
				var q3 = inversescale(mystats[3]);
				var maxval = inversescale(mystats[4]);

				var transitionTime = 750;

				d3.select("#BoxUp").transition().duration(transitionTime).attr("x1", innerrectx)
                        .attr("y1", q3)
                    	.attr("x2", innerrectx+innerrectwidth)
                    	.attr("y2", q3);

				d3.select("#BoxDown").transition().duration(transitionTime).attr("x1", innerrectx)
                        .attr("y1", q1)
                    	.attr("x2", innerrectx+innerrectwidth)
						.attr("y2", q1);
					
				d3.select("#BoxLeft").transition().duration(transitionTime).attr("x1", innerrectx)
                        .attr("y1", q1)
                    	.attr("x2", innerrectx)
						.attr("y2", q3);

				d3.select("#BoxRight").transition().duration(transitionTime).attr("x1", innerrectx+innerrectwidth)
                        .attr("y1", q1)
                    	.attr("x2", innerrectx+innerrectwidth)
						.attr("y2", q3);

				d3.select("#Median").transition().duration(transitionTime).attr("x1", innerrectx)
					.attr("y1", q2)
					.attr("x2", innerrectx+innerrectwidth)
					.attr("y2", q2);

				d3.select("#UpperWhisker").transition().duration(transitionTime).attr("x1", innerrectx)
					.attr("y1", maxval)
					.attr("x2", innerrectx+innerrectwidth)
					.attr("y2", maxval);
				
				d3.select("#LowerWhisker").transition().duration(transitionTime).attr("x1", innerrectx)
					.attr("y1", minval)
					.attr("x2", innerrectx+innerrectwidth)
					.attr("y2", minval);

				d3.select("#UpperStem").transition().duration(transitionTime).attr("x1", innerrectx+innerrectwidth/2)
					.attr("y1", q3)
					.attr("x2", innerrectx+innerrectwidth/2)
					.attr("y2", maxval);
				
				d3.select("#LowerStem").transition().duration(transitionTime).attr("x1", innerrectx+innerrectwidth/2)
					.attr("y1", q1)
					.attr("x2", innerrectx+innerrectwidth/2)
					.attr("y2", minval);
			}

			d3.select("#innerrect").on("click", function(){
				var coords = d3.mouse(this);
				var ycoord = coords[1];
				var toadd = document.getElementById("add").checked;

				if (toadd) {
					var existingdata = d3.select("svg").selectAll("circle").data();
					existingdata.push(ycoord);

					var datavalues = existingdata.map(scalecoords);

					d3.select("svg").selectAll("circle")
						.data(existingdata).enter().append("circle")
						.attr("cx", coords[0]).attr("cy", coords[1])
						.attr("r", 3).attr("fill", "black");

					updateStats(datavalues);
					drawbox(datavalues);

					//Reapplying the onclick remove functionality since new circles might be added
					d3.select("svg").selectAll("circle").on("click", function() {
						toremove = document.getElementById("remove").checked;
						if (toremove){
							d3.select(this).remove();
							var existingdata = d3.select("svg").selectAll("circle").data();
							var datavalues = existingdata.map(scalecoords);

							updateStats(datavalues);
							drawbox(datavalues);
						}
					});
				}
			});

			//Make sure there's no onclick functionality that you don't want to click on page load
			//I'm calling this to set a default for sanity sake
			document.getElementById("add").click();
			document.getElementById("DataValues").style.wordWrap = "break-word";
			document.getElementById("Outliers").style.wordWrap = "break-word";
		</script>

	</body>

</html>