- [CSharp](#csharp)
  - [Solutions](#solutions)
    - [Create instance using type of a class](#create-instance-using-type-of-a-class)
    - [Logger module using events](#logger-module-using-events)
        - [Logger class 👇](#logger-class-)
        - [makin' a logger 👇](#makin-a-logger-)
        - [Constructor of a module which uses logger 👇](#constructor-of-a-module-which-uses-logger-)
        - [Logging 👇](#logging-)
  - [Libraries](#libraries)
    - [EPPlus: write a excel file](#epplus-write-a-excel-file)
    - [System.Xml](#systemxml)

# CSharp


## Solutions

I'm going to list my complicated solutions in csharp programming. It will reveal frontier of my knowledge about csharp. you will find frontier between things I know and I don't know in csharp, if you're better than me in csharp and pay attention to this solutions


### Create instance using type of a class

![create instance](</pics/create_instance.png>)

In this case we need to a structure for making external modules for a service, the service needs to make multiple instance of that modules, then we make a system which stores the type of that modules ( each module is a class which inherited from BaseDataGenerator class ) then makes instance using Activator module in csharp.

<br/>
<br/>


### Logger module using events

I was making a module for a service in Behpouyan *[SII] then I recognized, main service needs to read and save log of module I was making, then I made a new module for this problem

##### Logger class 👇

![logger class](</pics/logger_class_csharp.png>)


##### makin' a logger 👇

![logger](</pics/use_of_logger_1.1.png>)


##### Constructor of a module which uses logger 👇

![logger](</pics/use_of_logger_0.png>)


##### Logging 👇

![logger](</pics/use_of_logger_2.png>)

## Libraries

This is a list of libraries and modules I had used in csharp

### EPPlus: write a excel file

![excel in csharp](</pics/excel_csharp.png>)

This is a simple insert data to excel file using EPPlus Package [SII]

### System.Xml

I would work with xml files in csharp, this is a example [SII]

![xml in csharp](/pics/xml_in_csharp.png)

