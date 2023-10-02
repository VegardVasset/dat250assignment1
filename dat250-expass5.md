# Technical report

Link to code: https://github.com/VegardVasset/dat250expass5

All the tutorial code is placed inside src/main/java/com/example in different packages the experiment 1 and 2 are the same
since exp 1 was only downloading the initial. 

## Experiment 1
No problems doing the initial spring setup doing it on the web and downloading the zip file
proved to be unproblematic. 

## Experiment 2
Had some problems running sdk run app.groovy, as it states run is not a valid command did not find out why this occurred 
as I downloaded the spring CLI as stated in the tutorial, but everything else worked fine

## Experiment 3
No problems here the html index page showed and when typing with the argument name= it displayed hello whatever argument
i typed in

## Experiment 4 
No problems here either here is a copy paste of the output i got which
is similar to what is stated in the tutorial

Customers found with findAll():

Customer[id=1, firstName='Jack', lastName='Bauer']
Customer[id=2, firstName='Chloe', lastName='O'Brian']
Customer[id=3, firstName='Kim', lastName='Bauer']
Customer[id=4, firstName='David', lastName='Palmer']
Customer[id=5, firstName='Michelle', lastName='Dessler']

Customer found with findById(1L):

Customer[id=1, firstName='Jack', lastName='Bauer']

Customer found with findByLastName('Bauer'):

Customer[id=1, firstName='Jack', lastName='Bauer']
Customer[id=3, firstName='Kim', lastName='Bauer']
