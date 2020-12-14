# Mission-to-Mars
UT McCombs Module 10: Mission to Mars - Web Scraping with HTML/CSS

## Data Environment
1.  BeautifulSoup4 4.9.3
2.  Bootstrap 3.3.7
3.  DateTime 4.3
4.  Flask 1.1.2
5.  Flask-PyMongo 2.3.0
6.  html5lib 1.1
7.  Jupyter Notebook 6.1.4
8.  MongoDB 4.4.2
9.  Numpy 1.19.3 
10. Pandas 1.1.4
11. PyMongo 3.11.2
12. Splinter 0.14.0
13. webdriver-manager 3.2.2

## Deliverable 1 Requirements
Code is written that retrieves the full-resolution image and title for each hemisphere image (10 pt)
The full-resolution images of the hemispheres are added to the dictionary. (10 pt)
The titles for the hemisphere images are added to the dictionary. (10 pt)
The list contains the dictionary of the full-resolution image URL string and title for each hemisphere image. (10 pt)

# Dictionary in Jupyter Notebook
![Pic 1](https://github.com/Baylex/Mission-to-Mars/blob/main/Resources/hemi_dict.PNG)


## Deliverable 2 Requirements
The scraping.py file contains code that retrieves the full-resolution image URL and title for each hemisphere image (10 pt)
The Mongo database is updated to contain the full-resolution image URL and title for each hemisphere image (10 pt)
The index.html file contains code that will display the full-resolution image URL and title for each hemisphere image (10 pt)
After the scraping has been completed, the web app contains all the information from this module and the full-resolution images and titles for the four hemisphere images (10 pt)

Code from Scraping file may differ slightly from the Jupyter Notebook Mars Mission Challenge file.  Some variables needed to be changed to match other files. 

# Final code in the scraping file:
![Pic 2](https://github.com/Baylex/Mission-to-Mars/blob/main/Resources/code_top.PNG)
![Pic 3](https://github.com/Baylex/Mission-to-Mars/blob/main/Resources/code_bottom.PNG)

# Scraping Success:
![Pic 4](https://github.com/Baylex/Mission-to-Mars/blob/main/Resources/Successful_scrape.PNG)

# Website after scraping:
![Pic 5](https://github.com/Baylex/Mission-to-Mars/blob/main/Resources/website_top.PNG)
![Pic 6](https://github.com/Baylex/Mission-to-Mars/blob/main/Resources/website_bottom.PNG)

## Deliverable 3 Requirements
# The webpage is mobile-responsive (10 pt)
Changed everything to col-xs, which is the smallest option.  Everything will scale up from there. 

# Two additional Bootstrap 3 components are used to style the webpage (10 pt)
1. Changed the button color to warning, which is orange to match the header color.
2. Added a tooltip that says Click Me!, when you hoover over the Scape button.
3. Changed the colors of various areas, adjusted some heights, added a striped table pattern.
