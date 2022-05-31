PROJECT- RESTAPIS USING CYPRESS

DESCRIPTION
Used cypress as a testing tool to automate an assert the following routes;

/employee
/employee/{id}
/create
/update/{id}
/delete/{id}
SET UP

Deployment
Download Node js and NPM
install Node js
create a folder in a desired location
Use VScode as IDE
Running Test
npx cypress open

Run Locally
npm install
npm install cypress --save-dev
####LIMITIATIONS

Verified each route on Postman locally to ascertain the HTTP response as well as verify the data returned from the response body. Since these are fake online REST APIs, there are some limitiations. Example, after creating a POST request, this returned a unique ID, to verify that the data has been created successfuly, i retrieved the data using GET method. however, anytime you run the same request, the ID changes intemitently.

Also, after performing a delete request, to verify that the data has been successfully deleted, i performed a GET request and this returned data as null, and the response message as > Successfully! Record has been fetched.

SCREENSHOTS
Screenshot 2022-05-23 at 20 55 55Screenshot 2022-05-23 at 21 06 55 Screenshot 2022-05-23 at 20 58 59 Screenshot 2022-05-23 at 20 59 13 Screenshot 2022-05-23 at 21 09 08
