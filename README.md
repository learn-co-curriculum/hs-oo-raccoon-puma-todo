
### Raccoons and Pumas, BFFAE
<img src="https://after-school-assets.s3.amazonaws.com/puma.jpg" width="600px">
### Step 1: 
Watch this [YouTube video](https://www.youtube.com/watch?v=vxiSP_ch_oI).

### Step 2: 
We're going to build two classes. A `Raccoon` class and a `Puma` class. 

### Each instance of the Raccoon class...
1. Should have 4 attributes: `name`, `age`, `has_puma_bff?`, and `puma_points`. You can decide which data type each attribute should be.

2. Should initialize with a unique name and an age.

3. Should automatically have a puma bff. Set the value `has_puma_bff?` during initialization.

4. Starts without any `puma_points`. Each `Raccoon` object has to be given `puma_points` by their puma best friend. Set that value to zero at initialization.

5. Should be able to talk to it's puma bff. Write a method that allows each raccoon to tell it's best friend, "I love you, Puma Best Friend." 

6. Should be able to give `raccoon_points` to their puma bff. Create a method called `give_raccoon_points`. This method should accept any argument (the instance of the `Puma` class it'll give the points to) and should increment the `raccoon_points` attribute of the instance of the `Puma` class.

### Each Instance of the Puma Class...
1. Should have 4 attributes: `name`, `age`, `has_raccoon_bff?`, and `raccoon_points`. You can decide which data type each attribute should be.

2. Should initialize with a unique name and an age.

3. Should automatically have a raccoon bff. Set the value `has_raccoon_bff?` during initialization.

4. Starts without any `raccoon_points`. Each `Puma` object has to be given `raccoon_points` by their raccoon best friend. Set that value to zero at initialization.

5. Should be able to talk to it's raccoon bff. Write a method that allows each puma to tell it's best friend, "I love you, Raccoon Best Friend." 

6. Should be able to give `puma_points` to their raccoon bff. Create a method called `give_puma_points`. This method should accept any argument (the instance of the `Raccoon` class it'll give the points to) and should increment the `puma_points` attribute of the instance of the `Raccoon` class.

7. Finally, Pumas need to be able to drop their best friend, and get another. Create a method called `drop_raccoon_bestie`. This method should accept an instance of the `Raccoon` class as an argument. The body of the method should set the `has_puma_bff?` attribute of the `Raccoon` class to false.

<a href='https://learn.co/lessons/hs-oo-raccoon-puma-todo' data-visibility='hidden'>View this lesson on Learn.co</a>
