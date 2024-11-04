This code was written for an online OA

This program uses the REST framework python library in the backend. The frontend uses the react-apexcharts and bootstrap.css for formatting.

To run this code navigate to /backend folder and run: "source venv/bin/activate" then "python manage.py runserver"
Then in a separate terminal navigate to /frontend and run: "npm start"


I started off this project working on the backend. The general setup was pretty simple although I didn't use Django in the past
so I researched how to use Django API. I found that I needed to set up a venv virtual environment to run the server necessary. I used
rest_framework to define the calls for the frontend to fetch the data. As per instruction, I hard coded the data in the backend.

In the front-end, I had initially tried to use Chart.js but found a lot of trouble due to mismatched versions between the various
Chart.js features I had tried to use. After a little research, I decided to use react-apexcharts. I found this to be a little more
simple to navigate. After getting all of the charts to render on the page, I decided to put each chart component inside a card to make
the charts more organized. Then I used bootstrap.css to format the cards.
