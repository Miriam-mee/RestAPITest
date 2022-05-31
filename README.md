# PROJECT- TEST RESTAPI USING CYPRESS

## DESCRIPTION
 Used cypress as a testing tool to automate an assert the following routes;

```
/employee
/employee/{id}
/create
/update/{id}
/delete/{id}

```

## SET UP
###### Deployment
```
Download Node js and NPM
install Node js
create a folder in a desired location
Use VScode as IDE

```

###### Running Test
```
npx cypress open
npx cypress run
```

## LIMITIATIONS

> Verified each route on Postman locally to ascertain the HTTP response as well as verify the data returned from the response body. Since these are fake online REST APIs, there are some limitiations. Example, after creating a POST request, this returned a unique ID, to verify that the data has been created successfuly, i retrieved the data using GET method. however, anytime you run the same request, the ID changes intemitently.

> Also, after performing a delete request, to verify that the data has been successfully deleted, i performed a GET request and this returned data as null, and the response message as > Successfully! Record has been fetched.


## SCREENSHOTS


![image](https://user-images.githubusercontent.com/58312167/171144861-978e31d2-f355-420b-bb77-074ed7770139.png)

![image](https://user-images.githubusercontent.com/58312167/171144932-5e020fff-7c76-4861-8959-370b9b426b4d.png)


![image](https://user-images.githubusercontent.com/58312167/171144981-f2eac6fa-7dc7-4254-96f9-92f1d330d78a.png)


![image](https://user-images.githubusercontent.com/58312167/171145062-18efe58a-5e7b-456b-876a-ceaf537a2a7f.png)



![image](https://user-images.githubusercontent.com/58312167/171145091-e5cd5a80-7e12-443e-a5cc-50b26620cfc2.png)


