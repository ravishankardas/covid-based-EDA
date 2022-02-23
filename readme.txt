Dependencies:
This project has these dependancies which are pandas, numpy ,openpyxl,so make sure they are installed


content:

1) Modify the neighbor districts data according to the districts found from the Covid19 portal. A neighbor of a larger district is a combination of all the neighbors of its components. Output the new data as neighbor-districts-modified.json. Use the state code and district codes from vaccination data as their ids. Arrange all the district and state keys in alphabetical order. Only include common districts from vaccination data and covid data.

2)  Construct an undirected graph of districts out of this new file. In the graph, every district is a node. A district node is connected by an edge to every adjacent district of it, and vice-versa.

3) For every district i, find the number of cases from the Covid-19 portal. Take the time-period of analysis from 15th March, 2020 to 14th August, 2021.

4)For every district, state and overall, find the week and month having peak (highest) number of active cases for wave-1 and wave-2.

5) Find the number of people vaccinated with 1 or 2 doses of any vaccine.

6) For each state, district and overall, find the following ratios: total number of females vaccinated (either 1 or 2 doses) to total number of males vaccinated (same). For that
district/state/country, find the ratio of population of females to males. (If a district is absent in 2011 census, drop it from analysis.) Now find the ratio of the two ratios, i.e., vaccination ratio to population ratio.

7) For each state, district and overall, find the following ratios: total number of Covishield vaccinated persons (either 1 or 2 doses) to total number of Covaxin vaccinated persons(same).

8) For each state, district and overall, find the following ratio: total number of persons vaccinated (both 1 and 2 doses) to total population. (If a district is absent in 2011 census, drop it from analysis.)
 
 9) For every state, find the date on which the entire population will get at least one does of vaccination. Assume the same rate of vaccination as in the week ending on 14th Aug, 2021. (Do not treat children separately, and assume the same rate of vaccination.)









































