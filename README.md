# Module #11
Mars news & weather

Deliverable #1:

In Part 1 of this project, I'll be opening the Jupyter Notebook named part_1_mars_news.ipynb from the starter code folder. As I work through this code, I'll follow the steps below to scrape the Mars News website.

First, I'll use automated browsing techniques to visit the Mars news site and inspect the page to identify the specific elements that I need to scrape.

To make things easier, I'll create a Beautiful Soup object to help me extract the necessary text elements from the website.

My main goal here is to extract both the titles and preview text from the news articles on the website. I'll organize the results using Python data structures in the following way:

For each news article, I'll create a Python dictionary with two keys: 'title' and 'preview'. 

All these dictionaries will be stored within a Python list.

To confirm my progress, I'll print out this list directly in my notebook.

There's an optional task as well: I can choose to save the scraped data to a file, maybe a JSON file, which would make sharing the data with others easier. However, it's good to know that there won't be any extra points awarded for completing this optional step.

By following these steps, I should be able to successfully scrape and gather the titles and preview text from the Mars News website.

Deliverable #2:

I'll start by opening the Jupyter Notebook named part_2_mars_weather.ipynb from the starter code folder. As I go through this code, I'll follow the steps below to scrape and analyze Mars weather data.

First, I'll use automated browsing techniques to access the Mars Temperature Data Site and inspect the page to figure out which elements I need to scrape. The URL for this is https://static.bc-edx.com/data/web/mars_facts/temperature.html.

I'll keep in mind the hint provided and create a Beautiful Soup object to extract the data from the HTML table. Although I could use the Pandas read_html function, I'll choose Beautiful Soup to practice and enhance my web scraping skills.

I'll then organize the scraped data into a Pandas DataFrame. The columns in the DataFrame will match the headings in the table on the website. Here's what each heading means:

id: identification number of a single transmission from the Curiosity rover
terrestrial_date: the date on Earth
sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls: the solar longitude
month: the Martian month
min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
pressure: The atmospheric pressure at Curiosity's location
I'll take a look at the data types currently associated with each column. If necessary, I'll perform data type conversions to ensure they are appropriate for further analysis—this might involve converting to datetime, int, or float types.

To delve into the dataset, I'll utilize various Pandas functions to answer some key questions:

How many months exist on Mars?
How many Martian (and not Earth) days' worth of data are present in the scraped dataset?
What are the coldest and warmest months on Mars at the Curiosity's location? I'll find the average minimum daily temperature for all months and visualize the results using a bar chart.
Which months have the lowest and highest atmospheric pressure on Mars? I'll calculate the average daily atmospheric pressure for all months and visualize it using a bar chart.
I'll also estimate how many terrestrial (Earth) days exist in a Martian year. To do this, I'll consider the number of days on Earth while Mars completes its orbit around the Sun. I'll visualize this estimation by plotting the daily minimum temperature.
Lastly, I'll ensure all the insights are saved by exporting the DataFrame to a CSV file.

Through these steps, I'll be able to successfully scrape, analyze, and visualize Mars weather data using Python and relevant libraries.

![image](https://github.com/loisstetson/Module_11_Mars/assets/127718619/16b9709e-97c4-4d31-ad2d-2b5ecd8eb7f8)

