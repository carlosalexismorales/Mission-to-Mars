# Mission-to-Mars Web App


## Project Overview

The assignment is to build a Web App that will scrape and extract data from several websites for images of Mars’s hemispheres. This is accomplished by using BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, storing the scraped data on a Mongo database, using a web application to display the data, and altering the design of the web app to accommodate these images. 

## Challenge Overview

1. Scrape Full-Resolution Mars Hemisphere Images and Titles
2. Update the Web App with Mars Hemisphere Images and Titles
3. Add Bootstrap 3 Components

## Resources

- Anaconda version 1.10.0
- Conda version 4.13.3
- Python version 3.9.12
- Jupyter-Notebook version 6.4.11
- Pandas version 1.4.2
- ipykernal version 6.9.1
- Numpy version 1.21.5
- Flask 1.1.2

## Results

### Scraping High-Resolution Mars' Hemisphere Image and Title


In the image below, we see the code that is being used to scrap the website for its data - particularly the images that we need to display on the web app. 




<img width="1095" alt="Screen Shot 2022-08-03 at 9 24 39 PM" src="https://user-images.githubusercontent.com/102444078/182762861-c53991bd-ccf3-4bcf-ba9f-0cfb2abadbf1.png">





<img width="1093" alt="Screen Shot 2022-08-03 at 9 25 07 PM" src="https://user-images.githubusercontent.com/102444078/182762909-c37d87ad-73fc-4b82-a633-379020ffebe5.png">





In the image below, we see the code that is being used to scrape the hemisphere data from the website - this code indicates that it automatically goes to the browser and gathers the images that will be displayed on the web app. 





<img width="849" alt="Screen Shot 2022-08-03 at 9 27 44 PM" src="https://user-images.githubusercontent.com/102444078/182763201-9fd2e370-4777-4141-8356-93cf1913f4b2.png">






In the images below, we first see the output of our code when we run 'python app.py' in our termina - the images that we wanted are displayed in a stylish manner. Second, we see that the web app is also mobile-responsive. 


<img width="1425" alt="Screen Shot 2022-08-03 at 9 28 41 PM" src="https://user-images.githubusercontent.com/102444078/182763314-9b2c4d70-a082-489f-874b-85512064257a.png">






<img width="1438" alt="Screen Shot 2022-08-03 at 9 31 10 PM" src="https://user-images.githubusercontent.com/102444078/182763584-9d5117b7-129e-4910-92d7-a494e2db046a.png">





<img width="422" alt="Screen Shot 2022-08-03 at 9 33 50 PM" src="https://user-images.githubusercontent.com/102444078/182763854-32264282-1906-4a3e-a1c4-e60cdb9439ef.png">
