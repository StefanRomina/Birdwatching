## Birdwatching
### Mountain Birdwatch 1.0 monitoring program analysis and visualization

Dataset Link: https://knb.ecoinformatics.org/view/doi:10.5063/F1DN430G<br/>
Language : Python<br/>
Tool/Environment : Jupyter Notebook<br/>
Packages Used : pandas, numpy, matplotlib, seaborn, shapefile, folium, geopandas, plotly, iplot

**Motivation:**

Birds are amazing animals and not many days go by in our lives where we don’t see at least a few of them flapping around. We are surrounded by these colorful, intelligent, vocal, flying creatures.
It can be a superb delight to get to know them better.<br/>
Birdwatching helps you connect with nature, to get outside, to explore new places.
Spending time and energy finding and observing birds is great for your physical, mental, and emotional health.
Looking for birds gets you outside in the fresh air and gets you moving. Even just pottering around at an easy pace is far better for your health than watching Netflix on your couch or sitting at a desk for hours.

**Conclusions :**

Sampling Area And Frequency : Upper montane forests above 2700 feet in the Northeastern United States (ME, VT, NH, MA, NY) from 2000 to 2010. <br/>
Primary emphasis was placed on Bicknell’s Thrush , most comments noted in SurveyNotes are about this bird detected between survey point 1 and 2 on hike up, on the route.

**Vermont** is the state where **14339** observations were counted, followed by:
- New York (9258), 
- New Hampshire (6061), 
- Maine (3434) and
- Massachusetts (154).<br/>

There are **211** routes where top 10 most visited for the Mountain Birdwatch program were: Snow (Vermont), Mansfield (Vermont), Plateau (New York), East (Vermont), Ranch Brook (Vermont),
Madonna (Vermont), Burke (Vermont), Westmore (Vermont), Pillsbury (New York), Twin NY. - plots: "Routes.png" , "Routes.png" <br/>

I found 213 records with missing species and 85 with no RouteLatitude and RouteLongitude registered.
You can see all species with their number of appearances located by state and geographical coordinates in plots: "State_birds.png" , "Geo.png" and iplots in the notebook file .

Top **10 birds** most seen are:
- White-throated Sparrow **907**
- Winter Wren **900**
- Blackpoll Warbler **890**
- Swainson's Thrush **855**
- Bicknell's Thrush **550**
- Myrtle Warbler **337**
- Slate-colored Junco **309**
- Magnolia Warbler **273**
- Yellow-bellied Flycatcher **254**
- Dark-eyed Junco **216**

Some birds are long distance migratory like: Blackpoll Warbler, Swainson's Thrush, Bicknells_Thrush, Magnolia Warbler, Yellow-bellied_Flycatcher, some are short distance like:
Winter Wren and Myrtle_warbler.<br/>

In the monitoring area where birds were spotted, some were in breeding period (White-throated Sparrow, Winter Wren, Myrtle_warbler, Magnolia Warbler, Nashville_Warbler),
some in migration (Blackpoll Warbler, Swainson's Thrush, Bicknells_Thrush, Yellow-bellied_Flycatcher).<br/>

Conservation status: Least concern for most ones, but there are species like Bicknells_Thrush, Chimney Swifts that are Vulnerable, Blackpoll Warbler, Olive-sided Flycatcher that are Near Threatened.<br/>

Top **5 species** can be watched in 'Top5_birds.html' map.<br/>

From the birds detected **once** we can observe big species like hawks, black duck, owl, common loon.<br/>
- Barred Owl, Olive-sided Flycatcher, Swamp Sparrow, Eastern Gray Squirrel, Red-tailed Hawk, Pileated Woodpecker, 
- Common Loon, Chimney Swift, American Pipit, Eastern Towhee, Alder Flycatcher, Tree Swallow, Wood Thrush, 
- Indigo Bunting, Ruby-throated Hummingbird, Peregrine Falcon, Sharp-shinned Hawk, American Black Duck, 
- Eastern Wood-Pewee, Broad-winged Hawk. 

Red-tailed Hawk, Peregrine Falcon, Sharp-shinned Hawk, Broad-winged Hawk, Barred Owl can be seen in 'Hawks_Falcon_Owl.html'.

Besides birds American Red Squirrel was noticed 213 times and Eastern Gray Squirrel once.
