# ***Green Accessibility Index*** by Dominant Area with different transportation modes - Helsinki

### **SOME RESULTS**
![Walking green accessibility](maps and charts/walking_green_index.png)
![Car green accessibility low income](maps and charts/car_low_income_green_index.png)
![Green access all people](maps and charts/all_pop_green_index_variation.png)
![Green access low income group](maps and charts/low_income_green_index_variation.png)

### **INTRODUCTION**
In our work we utilise a common premise on the knowledge and information gathered about people’s access to green areas and its positive (self reported and experienced) health and wellbeing impacts, the norm considered as sustainable is 26 m2 (Badiu, 2016); particularly arguing the possibilities to access wellbeing in the form of (urban) green are equal / different by different social group (genre, socioeconomic factor, age, etc) and by different travel modes (walk, bike, car, bus).  This point of view generates research enveloped into accessibility and sustainability (spatial justice) for urban areas.
Therefore we want to examine how accessible (urban) green is to people residing in the capital region in Finland: the goal is to explore green areas supporting user health and wellbeing - what is the “price” (in terms of accessibility; travel time with different transport modes, green areas accessibility variation by different travel modes ) of wellbeing derived from urban green for users living in urban core areas and in different parts or locations of the capital region (i.e. the municipalities/travel zones of the capital region). In this assignment we might analyze selected urban and national parks as green areas in the metropolitan area of Helsinki. The point is to measure green areas accessibility variation of the population by utilising the capital region travel time matrix zonafied into dominant travel zones (minimum travel times) with different travel modes. Then, compare how the ‘green access index’ (green areas per person) varies by different travel modes in dominant travel areas. Afterwards, comprehend if there is such variation of ‘green access index’ with specific social groups and for this case the low income inhabitants were used. In order to achieve this purpose the next research questions were formulated.

 ***Key words: green area, health, accessibility, modal variation***
 
 ### **RESEARCH QUESTIONS**
- Which travel mode gives the better ‘green access index’ for urban and national parks in the dominant travel zones?
> ***Answer: Public Transport. Public transport mode is the one which provides the more equality of access(chart 1). The lower the ‘green access index’ the more people have the opportunity to reach and Public Transport provides more opportunities to more people. On the other hand, Walking provides inequality of green access because it lets access to few people and this is why the ‘green access index’ is very high.***

- How do the opportunities to access green areas by transportation modes in the capital region change with low income as a social group?
> ***Answer. The situation is similar by analyzing a low income social group. But with some differences in Car and Bike transport modes.***

- What is the green area which gives more inequality for ‘green access index’?
> ***Answer: Nuuksio. Because it has a very high ‘green access index’ which means there are a lot of green areas only for a few people. The transportation mode analysis shows in which transport mode provides more equality of access. Be aware that the higher the ‘green access index’ the higher the inequality. This happens because when the ‘green access index’ increases there only few people who have the benefit of green area access. For sure, the transportation mode can change this inequality.***

### **DATA**
The main dataset utilized is the Travel Time Matrix of Helsinki which corresponds to the Travel Time by different travel modes. The particularity of this assignment is that we analyze the minimum travel time based on the travel time matrix of each urban and national park in order to obtain the dominant travel zones. Additionally, with the dominan travel zones, we use the dataset of Green Areas of Helsinki HMA and Low Income Social Group by postal areas from stats.fi.
The urban and national parks consider for this accessibility/sustainability study at the moment are:
- Nuuksio National Park (Luontokeskus Haltiala)| Nuuksiontie 84, 02820 Espoo | GRID 5870551
- Sipoonkorpi National Park (Cafe Kuusijärvi) | Kuusijärventie 3, 01260 Vantaa | GRID 5861358
- Kallalahdenharju Nature Reserve | Kallvikintie 48, 00980 Helsink | GRID 5954808
- Espoo Central Park (Puolarmaarin ulkoilukeskus) | Puolarmaari 12, 02210 Espoo | GRID 5967121
- Haltialan aarnialue (Niskalan arboretum) | Kuninkaantammentie, 00690 Helsinki | GRID 5892859
- Urban Central Park (Helsinki central park) | Maunulan luontopolku, Metsäläntie 9 | GRID 5934915

### **METHODS**
The dominant travel zones are zonified by minimum travel time in the matrix. The workflow is carried out in Python 3 script (check notebooks 1 and 2). The main tools used from Geopandas library are dissolve, spatial join, overlay/intersection which let us aggregate the population and green areas info into dominant travel zones. For the chart, spline methods were applied to smooth the lines and visualize the differences of accessibility by transportation mode.

### **CONDUCT ANALYSIS**
The outcomes of the study are going to be presented in eight different maps: green access index by walking (all population and low income group), green access index by cycling (all population and low income group), green access index by car (all population and low income group), and green access index by public transport (all population and low income group). 
Then, to understand the variability of green access index and spline line charts were presented including the index and the travel modes (all population and low income group). These charts will let us visualize which transport mode gives the better green access index.

### ** REASON FINDINGS**
This assignment matches with sustainability literature for urban infrastructure which study the health and quality of life of citizens as a key point. Some studies can be reviewed by Badiu (2016). What it is originally from this own assignment is that we are considering green areas accessibility based on the best travel mode which gives the opportunity to reach green areas.
Some studies about accessibility consider 750m as a service area which corresponds to 15 minutes walking at 3km/h like Pafi (2016). These points will be developed with the Helsinki travel time matrix which considers more persize the travel times and by choosing the best travel mode for green access we are able to promote this assignment as a tool for urban promoters or local governments.





