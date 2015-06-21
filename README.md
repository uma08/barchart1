# barchart1
<!DOCTYPE html>
 <html>
   <head>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/3.5.5/d3.min.js" charset="utf-8"></script>
   </head>
   <body>
   <script>
   
 
   
   var  canvas = d3.select("body")
				.append("svg")
				.attr("width",500)
				.attr("height",500);
				
				var circle = canvas.append("circle")
								.attr("cx",250)
								.attr("cy",250)
								.attr("r",50)
								.attr("fill","red");
								
				var rect = canvas.append("rect")
							.attr("width",100)
							.attr("height",50);
							
							var line = canvas.append("line")
										.attr("x1",0)
										.attr("y1",100)
										.attr("x2",400)
										.attr("y2",400)
										.attr("stroke","green")
										.attr("stroke-width",10);
										
   
   
   </script>
    
   </body>
   
 </html>
 
