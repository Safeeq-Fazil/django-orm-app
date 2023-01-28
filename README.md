# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

![entity](https://user-images.githubusercontent.com/118680361/215241165-4fa09060-063e-490b-a1b9-3df9d3bc7263.png)


## DESIGN STEPS

## Step 1:
create and collect customers infomartion using django application

## Step 2:
Implement that as Python code

## Step 3:
push that python code to github

Write your own steps

## PROGRAM
```
from django.db import models

# Create your models here. 
from django.db import models
from django.contrib import admin
# Create your models here.
class Customer(models.Model):
    customerid = models.CharField(max_length=8,primary_key=True)
    customername =models.CharField(max_length=100)
    mobilenumber =models.CharField(max_length=100)
    email = models.EmailField()
    quantity= models.IntegerField()
    

class CustomerAdmin(admin.ModelAdmin):
    list_display = ('customerid','customername','mobilenumber','email','quantity')
```
Include your code here

## OUTPUT

![djangooutput](https://user-images.githubusercontent.com/118680361/215241167-88102f18-436d-4b0a-b076-0ddf56da935b.png)

![image](https://user-images.githubusercontent.com/118680361/215241348-056860c2-1418-4044-bbd9-e61698638e6a.png)


## RESULT
The program was executed Successfully.
