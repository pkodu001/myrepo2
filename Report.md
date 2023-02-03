------------------------------------------------------------------------

## output: github_document

Title: HW2, CS625, Spring 2023  
Author: Priyanka KOduru  
Date: 2023-02-02  

# Part - 1

# Cleaning the whole dataset

# 1.What kind of pet is this

Edit cells —\> cluster and edit  
Then I manually edited some of the names because when I did cluster and
edit some names remain same they are  
Chinchilla(other) -\> Chinchilla  
cat -\> Cat  
other-goldfish -\> Goldfish  
turtle -\> Tortoise  
Roomba -\> Robot  
Bunny -\> Rabbit

# 2.Pet’s Full Name

Edit cells —\> Cluster and edit

# 3.Pet’s everyday name

Edit cells —\> Cluster and edit

# 4.Pet’s age

Edit cells —\> Transform —\> GREL  
value.replace(“years”,““).replace(”year
“,”“).replace(”ish”,““).replace(”years” ,““)  
value.replace(”two”,“2”).replace(“six”,
“6”).replace(“seven”,“7”).replace(“½”,”
.5”).replace(“1/2”,“.5”).replace(”
“,”“).replace(”\~“,”“).replace(”&“,”“).r
replace(”≈“,”“).replace(”()“,”“).replace (”yo”,““).replace(”old”,““)

# 5.Pet’s breed

Edit Cells —\> Cluster and edit  
Some names are edited manually like  
Mixed breed Boomer, Mixed cat,mixes —\> Mixed breed  
Golden, Golden mix —\> Golden retriever mix  
Mutt(boxer, pug, beagle, Boston), Mutt: half terrific, half amazing —\>
Mutt  
Pit bull ish, Pit bull mix, Pit mix —\> Pit bill mix  
Orange tabby (DSH) —\> Orange teddy

# Part - 2

# Analyze Cleaned Data

# 1.How many types (kinds) of pets are there?

Facet —\> Text facet —-\> 29 Types

# 2.How many dogs?

Dogs —\> 1132

# 3.How many breeds of dogs?

Dog —\> Pet’s breed —\> Facet —\> Text Facet —\> 479

# 4.What’s the most popular dog breed?

Dog —\> Pet’s breed —\> Facet —\> Text facet —\> Sort by Count —\>
Golden Retriever —\> 174

# 5.What’s the age range of the dogs?

Dog —\>\> Pet’s age —\> Sort —\> Number —\> Largest —\> 20  
and then sort —\> Number —\> Smallest —\> 0  
Then the range —\> 0-20

# 6.What’s the age range of the guinea pigs?

Guinea Pig —\> Pets’s age —\> Sort —\> Number —\> Largest —\> 5 Then
Sort —\> number —\> smallest — 0.08  
Then the range is 0.08-5

# 7.What is the oldest pet?

Pets age —\> Sort —\> Number —\> Largest —\> 167 that is Cat

# 8.Which are more popular, betta fish or goldfish? How many of each?

Bettafish —\> Facet —\> Text facet —\> count 2  
Goldfish —\> Facet —\> Text facet —\> Count 7  
More popular fish is Goldfish

# 9.What’s the most popular everyday name for a cat?

Cat —\> Pet’s everyday name —\> Facet —\> Text facet —\> sort by count
—\> Kitty-7(count) !\[Cat popular

# 10.What’s the most popular full name for a dog?

Dog —\> Pet’s Full Name —\> Facet —\> Text Facet —\> Sort by count —\>
Maggie 7(count) !\[Popular full
