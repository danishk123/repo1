Requirements
************

For the following use the github repository you made for your project.
Load some data you have gathered for your project into Python.
Identify some numeric and categorical features in your data. Write this up in a file called README.md
Run some summary statistics over the numeric data.
Are there any interesting features of the data that jump out?
Generate some data visualisations that would be useful for you to explore your data set, particularly the numeric data right now.
If you can find any good candidates for a regression, try some regressors out.



Actions Taken
*************

Data set chosen: The NTSB aviation accident database contains information from 1962 and later about civil aviation accidents and selected incidents within the United States, its territories and possessions, and in international waters. I am looking to analyze this dataset to investigate patterns and correlations between events. The dataset contains information on location, aircraft type, number of engines etc.


Data contains the following columns:
Index([u'Event.Id', u'Investigation.Type', u'Accident.Number', u'Event.Date',
       u'Location', u'Country', u'Latitude', u'Longitude', u'Airport.Code',
       u'Airport.Name', u'Injury.Severity', u'Aircraft.Damage',
       u'Aircraft.Category', u'Registration.Number', u'Make', u'Model',
       u'Amateur.Built', u'Number.of.Engines', u'Engine.Type',
       u'FAR.Description', u'Schedule', u'Purpose.of.Flight', u'Air.Carrier',
       u'Total.Fatal.Injuries', u'Total.Serious.Injuries',
       u'Total.Minor.Injuries', u'Total.Uninjured', u'Weather.Condition',
       u'Broad.Phase.of.Flight', u'Report.Status', u'Publication.Date'],
      dtype='object')
      
      
I have applied some basic statistical fucntions to the numerical data. However, I will need to convert some of the fields (for e.g. date, some of the category field (such as Accident & Investigation Type to numerical values.



Question for Greg, Amanda & Self: is there a way to remove the '.' in the column header names and replace it with a '_'? This will be a problem, I suppose when writing code.


I am very keen to examine if there is a pattern between number of accidents & location, i.e. the Bermuda Triangle Effect!
Is there a link between Aircraft category and accident? Any relationship between accidents and the phase of flight (Takeoff, Descent etc)?


I will be working on the regressions and visualizations over the coming days. It would be great to get feedback on some of the work so far, the dataset and the intended outcomes. 







