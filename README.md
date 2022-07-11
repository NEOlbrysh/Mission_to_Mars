# Mission_to_Mars

## Objective

The purpose of this project is to build a Web App that will scrape several websites for the most recent Mars data. The extracted data is stored in a NoSQL database and then an HTML page is created to display the findings. Robin's web app is looking good and functioning well, but she wants to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping friendly. She would like to adjust the current web app to include all four of the hemisphere images. To do this, you’ll use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.


Tables in HTML are basically made up of many smaller containers. The main container is the <table /> tag. Inside the table is <tbody />, which is the body of the table—the headers, columns, and rows.
<tr /> is the tag for each table row. Within that tag, the table data is stored in <td /> tags. This is where the columns are established.

Scraping Success:

After running app.py, the extracted data is successfully stored in MongoDB as seen in the screenshot below. A mars_app database must exist in mongo for the code to properly run.
To confirm that the mars_app database exists, run the following comma


Using Bootstrap 3 to modify the html file
Adding Bootstrap 3 components, such as the code below, allowed the four Mars hemisphere images to be displayed side-by-side on Desktop browsers, instead of a line. This allows users to see all four images at once.
Two additional Bootstrap 3 components are used to style the webpage
1.	Changed the button color to warning, which is orange to match the header color.
2.	Added a tooltip that says Click Me!, when the user hoovers over the Scrape button.


![2022-07-11 (14)](https://user-images.githubusercontent.com/103701561/178369580-779fc2c9-dc56-480a-8495-0493549c32d3.png)
![2022-07-11 (9)](https://user-images.githubusercontent.com/103701561/178369598-ee942cd6-8401-46e8-90b6-afafdbb543e0.png)
![2022-07-11 (11)](https://user-images.githubusercontent.com/103701561/178369605-2b794e9a-52a5-4401-a24f-5ecdc070c14b.png)
![2022-07-11 (12)](https://user-images.githubusercontent.com/103701561/178369618-1960f1d3-ca7b-4a82-a842-759d2f01f519.png)
![2022-07-11 (13)](https://user-images.githubusercontent.com/103701561/178369626-120d7d2c-f0ea-4592-8c2f-7f97d199db20.png)
![2022-07-11 (8)](https://user-images.githubusercontent.com/103701561/178369638-5051b129-3f4e-4abb-a7c0-e9d5b413c95c.png)
![2022-07-11 (7)](https://user-images.githubusercontent.com/103701561/178369643-fccb133e-d791-477d-91ae-ef01effe44a1.png)
![2022-07-11 (3)](https://user-images.githubusercontent.com/103701561/178369660-3275ba4f-7b10-4183-b6bd-ffe4cf0ece1b.png)
