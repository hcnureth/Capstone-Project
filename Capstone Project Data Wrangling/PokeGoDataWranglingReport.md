*PokémonGo* Data Wrangling
================
Hunter Campbell
June 15, 2017

<br>

The steps I took were set up into two categories:

1.  Create a cleaned up dataset
2.  Create a few subsets

<br>

Step 1:

I first selected the columns that I found would be most useful to predict outcomes with. Once I selected the columns I wanted to work with, I sorted them according to the Pokémon Id column. I then checked for NA and blank values, and fixed any dummy variables. I then fixed the kilometer columns to read as meter columns, because it was easier to read the numbers as 125.6m instead of 0.1256km.

<br>

Step 2:

I made two subsets. One subset was to make it easier to test water type Pokémon against near water. This way I could see if there was a correlation between the two. After making that subset I made a subset to test non-water type Pokémon against near water. This way I could test the two subsets against each other. I figured I didn't need any other subsets, because I could use my cleaned up dataset to test other variables, such as Pokémon Id versus population density, Pokémon Id versus near a gym or near a pokéstop, etc.