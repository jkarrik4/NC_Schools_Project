# NC_Schools_Project

- create map with different layers using leaflet to plot schools in meklenburg, nc
- data markers to give school rating information and address when clicked
- create heatmap using leaflet to show median income and median housing prices in mecklenburg county

Description:
-Main webpage is in 05_schools_leaflet folder (index.html)
-flask should route the button to next page (school.html)
-school.html should display markers of all cms schools. down arrow should bring user to next page (heatmap.html)
-heatmap.html should display heatmap of median housing prices within mecklenburg county, based on smaller boundaries known as NPA and is defined by the county. on the heatmap, user should have options to turn on schoolmarkers (in clusters). Down arrow should bring user to next page (cluster.html)
-cluster.html should allow user to zoom in and visualize the quantitiy of schools within area of choice based on the median hosuing prices. From there on, continuing to zoom in and be able to clik on markers and view school ratings, address, and click on links to the respective school.

Future progress anticipated:
-using api to get school markers and update ratings
-using real-estate api to pull data, store in database, and update on webpage heatmap.
-generate optional dropdowns and search button to choose schools of different grades and ratings, and input zipcode of choice.
