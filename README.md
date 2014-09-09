---
tags: ruby, kids, oo, oop, object-orientation, todo
languages: ruby
level: 1
type: todo
---

##Raccoons and Pumas, BFFAE
 
####Step 1: 
Watch this [video](https://www.youtube.com/watch?v=vxiSP_ch_oI)

###Step 2: 
We're going to build two classes. A Raccoon class and a Puma class. 

####Your Raccoon class:
1 Should have 4 attributes: name, age, has_puma_bff?, and puma_points. You can decide which data types each attribute should be.

2 Should be able to initialize a new instance of the Raccoon class with both a name and an age.

3 Every instance of the Raccoon class should automatically have a puma bff. You'll need to set the value has_puma_bff? during initialization.

4. Raccoons aren't born with puma_points. They have to be given to them by their puma best friend. You'll need to set that value to zero.

5. Each instance of your Raccoon class should be able to talk to it's puma bff. You'll want to build a method that allows each raccoon to tell it's best friend "I LOVE YOU PUMA BEST FRIEND". 

6. Raccoons need to be able to give raccoon_points to their puma bff. You'll need to create a method called `give_raccoon_points`. This method should accept any argument (the instance of the puma class to give the points to) and should increment the raccoon_points attribute of the instance of the Puma class.

####Your Puma Class:
Your Raccoon class:
1 Should have 4 attributes: name, age, has_raccoon_bff?, and raccoon_points. You can decide which data types each attribute should be.

2 Should be able to initialize a new instance of the Puma class with both a name and an age.

3 Every instance of the Puma class should automatically have a raccoon bff. You'll need to set the value has_raccoon_bff? during initialization.

4. Pumas aren't born with raccoon_points. They have to be given to them by their raccoon best friend. You'll need to set that value to zero.

5. Each instance of your Puma class should be able to talk to it's puma bff. You'll want to build a method that allows each raccoon to tell it's best friend "I LOVE YOU RACCOON BEST FRIEND". 

6. Pumas need to be able to give puma_points to their puma bff. You'll need to create a method called `give_puma_points`. This method should accept any argument (the instance of the puma class to give the points to) and should increment the puma_points attribute of the instance of the Raccoon class.

7. Finally, Pumas need to be able to drop their best friend, and get another. You'll need to create a method called `drop_raccoon_bestie`. This method should accept an instance of the Raccoon class as an argument. The body of the method should set the has_puma_bff? attribute of the Raccoon class to false.

