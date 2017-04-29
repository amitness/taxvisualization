# Tax Visualization
 This project is the representation of tax paid by different private institutions, governmental branches and the citizens. We are trying to show the statistics of taxes paid throughout the country. 
 
 The project was a wordpress powered website which visualized different statistic related to tax in Nepal. We scraped datas related to tax and saved them in CSV format. The the csv were hosted on cloud in google drive and we made interactive graphs and charts using the CSV. Any changes made to the spreadsheet updated the graphs as well. 

You can have a look at the live demo [here](http://taxv.16mb.com).

It was made at the hackathon orgranised by YoungInnovations on the occasion of **"Open Data Day 2015"** at DeerWalk Institute of Technology, Sifal.

### Local Setup:

1. Setup a wordpress blog.
2. Install and activate [Interface Theme](https://wordpress.org/themes/interface).
3. Install [Wordpress Visualizer](https://wordpress.org/plugins/visualizer/) plugin.
4. Install [Disable Comments](https://wordpress.org/plugins/disable-comments/) plugin.
5. Activate *Disable Comments* plugin and goto Settings > Disable Comments and select *Everywhere* option.
6. From Dashboard, goto tools > import and import the visualizations.xml file.
7. From Settings > Reading, set Front page displays to *A static page* and select front page as *Highest Tax Payers of Nepal*.

### Datasets:
The tax data scraped by us is inside the datasets folder. Feel free to use it and contribute.
