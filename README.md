# Advanced Data Storage and Retrieval Challenge

This assignment involves using Python and SQLAlchemy to do basic climate analysis and data exploration of the climate database based in Hawaii.


![Hawaii](https://www.tripsavvy.com/thmb/Ni6OtHk7KtoCrQF_J8EZHQKpwl4=/950x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Disney-Aulani-Waikolohe-Valley-5ab94b540e23d9003764e230.jpg)

PART I: Data Engineering<br>
* Utilizing Python and pandas to import csv data on hawaii weather measurement and observation stations. <br>
* Create Jupyter Notebook file called `data_engineering.ipynb`<br>
<br>

PART II: Database Engineering<br>
* Create Engine and connections string for database Hawaii.sqlite<br>
* Create Measurement and Stations classes<br>
* Create Jupyter Notebook file called `database_engineering.ipynb`<br>
<br>

PART III: Data Analysis<br>
* Setting Up Database<br>
* Create table in database & Start Session<br>
* Reflect an existing database into a new model<br>
* Use Base Class to reflect database tables<br>
* Classes mapped in database<<br>
* Upload Measurement & Inspect the table<br>
* Upload Stations & Inspect the table<br>
* Save references to each table <br>
* Design a query to retrieve the last 12 months of precipitation data and plot the results <br>
* Save the query results as a Pandas DataFrame and set the index to the date column<br>
* Use Pandas Plotting with Matplotlib to plot the data<br>
* Use Pandas to calcualte the summary statistics for the precipitation data<br>
* Using the station id from the previous query, calculate the lowest temperature recorded, highest temperature recorded, and average temperature most active station <br>

![Image of Precipitation Analysis](https://github.com/erikku0519/Advanced-DataStorage-and-Retrieval-Challenge/blob/master/Precipitation_Analysis.png)

![Image of Station Analysis](https://github.com/erikku0519/Advanced-DataStorage-and-Retrieval-Challenge/blob/master/Station_Analysis_for_Station.png)



PART IV: Flask App<br>
* Database Set-up
* Flask Set-Up
* Flask Routes
- @app.route("/")<br>
- @app.route("/api/v1.0/precipitation")<br>
- @app.route("/api/v1.0/stations")<br>
- @app.route("/api/v1.0/tobs")<br>
- @app.route("/api/v1.0/temp/<start>")<br>
- @app.route("/api/v1.0/temp/<start>/<end>")<br>

