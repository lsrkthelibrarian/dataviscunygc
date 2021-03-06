# Final Portfolio Draft

## Research Question: 
Jenna Freedman and I have been conducting ongoing work at the GC to develop a Zine Union Catalog that will allow scholars, researchers, zinesters, and anyone else interested in locating zine collections through a single search interface.  It is called [ZineCat](http://browse.zinecat.org/index.php). 

First, a zine is a self published, small circulation, original work often featuring artistic, counter cultural, political, or highly personal content.  Second, if you’re not familiar with a union catalog, it is a catalog that allows one to search across many collections.  Libraries across the world have been collecting zines and making them locally findable (i.e. through the institution’s own catalog), but they are rarely made findable via larger union catalogs, a la Worldcat, and often have different means for describing the zines (aka non-standardized metadata).  

For our ITP Core II course this past spring, we wrote: “Because zines exist in a counterculture space, they have historically been collected and circulated first by independent collectors, then zine libraries and activist centers, followed later by research institutions. Over the last fifteen to twenty years, public libraries, special collections, and academic research libraries have begun collecting zines as scholarly resources, as well as part of leisure reading collections. This hybrid environment of zine collections translates into dispersed and sometimes erratic mechanisms for access (not all libraries describe material in the same, standardized way). Zine descriptions and metadata, thus discovery of zines, are scattered across library catalogs, archival finding aids, standalone databases, spreadsheets, and online platforms such as LibraryThing. This diversity of access points poses impediments to finding and using zines in aggregate for research, teaching, and learning in the humanities. The Zine Union Catalog (ZUC) seeks to federate metadata from these disparate sources.” (Full paper linked [here](https://docs.google.com/document/d/12I5JAyfy5hmu7Jgb9JrS0OLekvLVgGk392hQZD4N1uw/edit?usp=sharing).)

Since there is a discrepancy in describing zines, I would like to analyze two fields of the zine collections we have in ZineCat: creator (aka author) and keywords (aka subject headings).  When we launched ZineCat in spring, 2017, we did not include keywords as they presented  a challenge for our system, but they are a very essential part of how users will search for, and find, the zines in the union catalog.  At this moment, my research question is: How can visualizations assist me in discovering the inconsistencies and impediments of describing the zine collections in The Zine Union Catalog (ZUC)?  With new discoveries through visualizations, how can the metadata for organizing zines be improved (and/or standardized) to make finding zines through ZUC easier?

## Audience: 
Audience: The immediate audience for this project is me and Jenna Freedman, along with any other members of the zine union catalog community.  However, this project has a larger audience in the wider zine community and will reach any individual or group that ends up using the Zine Union Catalog (including students, scholars, researchers, librarians, zinesters, catalogers, etc.).

## The Data: 
I will use a sampling of data from the three institutions that are currently represented in the Zine Union Catalog: Barnard Zine Library, Denver Zine Library, and the Queer Zine Archive Project (QZAP).  Stored in the [xZINECOREx](https://github.com/zinecat/xZINECOREx) Github repository are samplings of records the three collections.  I’ve identified QZAP’s data set to be the “easiest” to use as it will require the least amount of cleaning (so it’s possible I will just use this set), but ideally, I would like to have all three collections that are currently visible in ZUC to be represented in my visualizations.  In the ZUC, there are about 20 items from each collection, so I may pull out the information on those items specifically for the visualization or I may just use QZAP’s data.  

{% include plot4.html %}

**After our in-class pin-up and feedback from the class, I have made several updates to the visualization.**

{% include plot5.html %}



In case the visualization does not appear above, please click this [link](https://public.tableau.com/views/FinalProjectAttempt3/ZineCatFinal?:embed=y&:display_count=yes&publish=yes) to visit my Tableau page.  

## Data Design and Decisions: 
I created a lot more versions of the data for this final assignment than what I have been doing up until now.  In the first two assignments, my realized visualization very much matched my original sketch, but for this assignment, I was quite at a loss as to what works best.  I want to use my data set most effectively to determine discrepancies in metadata description and to show how complicated describing zines is.  I think the visualizations represent this, but I do not like the way the bar charts require the viewer to do a lot of scrolling and want to find a better way to present this data.  Also, with so many keywords represented in one of the bar charts, it was not a good design decision to use one color, but I am unhappy with the clashing color scheme.  The project I am analyzing this data for has a color scheme of red and black, so I would like the visualizations to conform to the same color aesthetic.  Two out of three visualizations do, but the one that is most representative of the keywords does not conform.  

## Next Steps: 
I want to improve the three visualizations so that they are more aesthetically aligned and tell a more cohesive story.  I also want to include data from the other two collections in ZineCat: The Barnard Zine Library and the The Denver Zine Archive.  For this draft of the final, I only used QZAP's data as it did end up being the easiest to work with (although I believe some of the visualizations are falsely representing the number of zine within the set due to the pivoting of information I needed to do...i.e. long and skinny), so I'd like to clean up QZAP more as well as include (and connect) the other two data sets.  I'm looking forward to hearing other's perspectives on the visualization!

< [Return to Home](./index.md)
