# Veridion Assignment

## Project One
The .CVS file contains multiple sources for the same company. So, I combined these sources to make sure that there was as little missing data as possible.

I started off with what I considered to be the most important variable, the URL link. I checked which source had the least null values then I replaced the missing values with the ones with the second most non-null values. I repeated this until I had no more null values. If the URL was missing from all the sources, then I deleted the whole row.

I repeated this process to all the columns, but for the ones that weren't the URL I kept the rows with missing values.

After I considered that the data was clean and complete, I renamed the columns to have a better understanding of what they represent and saved the processed data frame to a CSV file for future use.

## Project Two

1. Created a site map of the original Wiki page
   
    ![alt text](/resources/screenshots/image.png)
   
2. Created a selector to select all the constituent elements
   
    ![alt text](/resources/screenshots/image-1.png)
   
3. Selected the links

   ![alt text](/resources/screenshots/image-2.png)

    ![alt text](/resources/screenshots/image-3.png)
   
5. Created separate selectors for each table element

   ![alt text](/resources/screenshots/image-4.png)
   
6. Scrape

7. Download .CSV

![alt text](/resources/screenshots/image-5.png)

## Project Three

I would start off by importing and processing the data, and make sure there's no duplicate or null data. Then, I would try to standardize the terms. If multiple rows from a source mean the same thing, choose only one category.

Next, I would examine the sources separately to understand why the categories are named the way they are. For both of them, I would check how deep the categories go. Do they represent a broad category or a specific element from a bigger category? 

After quickly reading the CSV file, I noticed that 'Taxonomy 1' contains broader terms, while 'Taxonomy 2' is more specific. Based on this, I would go with a One-To-Many mapping.

This answer is based on a quick look at the data and some research I just did since I never made a 'crosswalk mapping' before.
