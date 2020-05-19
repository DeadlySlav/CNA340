# 4.17 LAB: Warm up: Automobile service cost
In this lab we will write a program for Automobile Service Cost that will take the user input and print the services requested. In the lab we were provide the servies that are available: Oil change -- $35, Tire rotation -- $19, Car wash -- $7. 

## Getting Started
These instructions will install Pycharm on your local machine.

### Prerequisites
Python requires Pycharm to run, with with no other packages. The link to Pycharm's download will install Pycharm onto your system. 
Link: [Pycharm](https://www.jetbrains.com/pycharm/download/#section=windows) 

## Running
Once Pycharm is installed on your system you can run it:
click on create new project.
Copy and paste code into Pycharm. 

**4.17 LAB: Warm up: Automobile service cost**

service_choice = input('Enter desired auto service:\n')
print('You entered:', service_choice)
service_choice = service_choice.upper()
service_cost = 0
if service_choice == 'OIL CHANGE':
        service_cost = 35
if service_choice == 'TIRE ROTATION':
        service_cost = 19
if service_choice == 'CAR WASH':
        service_cost = 7
if service_cost == 0:
        print('Error: Requested service is not recognized')
else:
        print('Cost of', service_choice.lower() + ': $' + str(service_cost))
        
 
*Inputs*
```
Oil change
``` 
*Output*
```
Enter desired auto service:
You entered: Oil change
Cost of oil change: $35
```

## Thanks
To Luma for showing me how to edit the readme file!
