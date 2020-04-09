# Car-Service-Api


In order to access the service, you need to sign up:

A POST request to the following url https://car-service-api.herokuapp.com/api/auth/signupwith the sample body below:

{
"email": "email",
"password": "password"
} 

returns your userId.

In order to get your access token, you need to login:

  A POST request to the following url https://car-service-api.herokuapp.com/api/auth/login
  with the sample body below:  

{
"email": "email",
"password": "password"
}  

returns your access token 

  A POST request to the following url https://car-service-api.herokuapp.com/api/carservice using the token gotten from login gives you access to the service. 
with the sample body below: 

{
"car_model": "Toyota Camry 2009",
"date": "January 24th 2007"
}

returns a price value
