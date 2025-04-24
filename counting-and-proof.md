# Counting and proof

## Introduction exercises

### 1

At WEBS, America’s Yarn Store, there are two aisle displays of sale yarns,
six aisle displays of closeout yarns in the back warehouse, one aisle display
of Grandpa’s Garage Sale yarns in the back warehouse, and one display
shelving unit of über-clearance $2/ball yarns in the retail area. To how many
display areas can you go in WEBS to buy yarn that is not full price?

The answer is 10 because there is 10 aisle with yarns not full price.

### 2
A group of friends goes out for single-scoop ice-cream cones. There are
sugar cones, cake cones, and waffle cones. But there are only five flavors
of ice cream left (peppermint, hoarhound, chocolate malt, gingerbread, and
squirrel). How many cone/ice cream combinations can be ordered?

3 kind of cones * 5 flavors

The answer is 15

### 3

At this ice-cream store, ice-cream scoops are stored right in the ice-cream
containers between uses. At least how many ice-cream scoops must be in
use if two of them have to be stored in the same flavor ice-cream container?

6 scoops must be in use if there is 1 container by flavor 
 
### 4

A server at the Luminous Nose restaurant goes to this same ice-cream store
but decides to get a triple-decker cone. The stacking of scoops on the cone is
important: a cone with peppermint atop two scoops of squirrel tastes differ-
ent than a cone with two scoops of squirrel atop a scoop of peppermint, so an
order of peppermint-squirrel-squirrel is different from an order of squirrel-
squirrel-peppermint. How many possible triple-decker ice-cream orders are
there?


5^3 which is 125 possibility.

### 5

Some people heading to a party stop by the ice-cream store to buy quarts of
ice cream. How many orders of three quarts could they make?

35  because 10 combinations for 3 distinct flavours + 5 combinations for the full tree same flavours each + 20 when there is 2 with each flavors. 

What if the three flavors have to be different? 

There is 10 combinations possible

What if no one will agree to order squirrel ice cream?

It will be 20 without squirrel same logic than for the first question

### 6

Four teams are attending a local Ultimate Frisbee meet. If each team plays
each other team exactly once, how many games are played?

team 1 played team 2
team 1 played team 3
team 1 played team 4
team 2 played team 3
team 2 played team 4
team 3 played team 4

There are 6 games played.

### 7

Some of the Ultimate Frisbee players decide to form temporary teams in
an arbitrary way. They put royal blue and lime green armbands into a bag,
and each player closes hir eyes and grabs an armband to see which tempo-
rary team ze’ll be on. How many armbands need to be grabbed in order
to ensure that one of the teams has at least two players? 

At least 3 

How many arm-bands need to be grabbed in order to assure that one of the teams has at least
seven players?

At least 13 

### 8

Some Ultimate Frisbee meet attendees saunter over to the Healthy Snack
Box Machine, where they each choose one of five kinds of fruit, one of
three herbal teas, and one of six flavors of wrap sandwich to get packed in
a box. How many possible snack boxes are there?

5 * 3 * 6 = 90


### 9

Let’s generalize Problem 6 to a regional Ultimate Frisbee tournament where
there are n teams attending. Teams are assigned numbers (1 through n) when
they register. As before, each team will play each other exactly once

How many games does Team 1 play?

Team 1 plays n - 1 games.

How many games does Team 2 play? Wait, that counts the Team 1
versus Team 2 game twice. How many not-yet-counted games does
Team 2 play?

Team 2 plays n - 2 games.

Keep going. How many “new” (uncounted) games does Team i play?

Team i plays n - i games.

How many games are played in total?

It is a suite like n - 1 + n - 2 + n - i ...

the formula is n (n - 1) / 2

### 10

Let’s also generalize Problems 2 and 3 to a more reasonable ice-cream store.
There are still three kinds of cones (the usual), but now there are k flavors
of ice cream.

(a) How many different single-scoop ice-cream cones can be ordered?

3 * k flavours 

(b) How many ice-cream scoops must be in use if two of them have to be stored in the same flavor ice-cream container?

k + 1 

### 11

Terminology alert: We write finite sets as lists of their members (also called
elements). For example, {2, 3, 5, 7} is an excellent set. So is {1, 4}. These
sets are disjoint because they have no members in common. On the other
hand, {1, 2} is not disjoint from either {2, 3, 5, 7} or {1, 4}. The union of
two sets A, B (or many sets A, B, . . . , N) is a set containing all members of
A and of B (and of C, . . . , N). The union of the three sets listed so far is
{1, 2, 3, 4, 5, 7}.

(a) How many elements are in the union of two disjoint finite sets?

Elements of set 1 + elements of set 2 because they are disjoints so they have no elements in common.

(b) How many members does a union of finitely many disjoint finite sets
have?

The sum of the elements of all the disjoint finite sets.

(c) Are the previous two questions related to any of the previous prob-
lems?

Yes they are related to most of the problem asked previously

Yes the problem 6 for example.

(d) How many members does the union of n disjoint sets, each with m
elements, have?

The union of n disjoint sets, with each m elements has n * m members

### 12

Another terminology alert: We call the notation (a, b) an ordered pair and
(a, b, c) an ordered triple (and yes, we call (a, b, . . . , n) an ordered n-tuple).
Generally, the first member of the pair (or triple, etc.) is from some set A,
and the second member of the pair (or triple, etc.) is from some set B, etc.
If A has m elements and B has k elements, how many ordered pairs can be
formed from A and B? 

We can form  m * k ordered pair.

Is this related to any of the previous problems?

Yes the problem 10.A for example.

## Preliminaries on Proofs and Disproofs

### 1

Gelly Roll pens come in 6 solid colors of fine point and 11 of medium point, 10
moonlight colors, 10 shadow colors, 12 stardust colors, and 14 metallic colors.
(Not kidding.) How many different Gelly Roll pens are there?

Using the sum princple 6 + 11 + 10 + 10 + 12 + 14 = 63


### 2

When redeeming a prize coupon, you may choose one of six charms and either one
of three carabiners or one of two bracelets. How many different prize choices could
you make?

Using the product pinciple and the sum principle (6 * 3) + (6 * 2)  = 30

### 3

Challenge: Invent your own problem that uses both the sum principle and the prod-
uct principle.

In a Greek restaurant you can choose between 3 starters and either 2 main course and 3 desserts how many menu choices could you make ?

---------

24= 5 + 19= 7 + 17= 11 + 13.
8= 3 + 5.
38= 19 + 19= 7 + 31.

What property do the numbers on the left-hand sides of the equations have
in common?

They are all even 

What property do the numbers on the right-hand sides of the equations have
in common?

They are all odd and prime number

Come up with three more examples that fit this pattern.

4 = 1 + 3
6 = 3 + 3

Do you think the pattern always holds?

Yes i guess this pattern old true for x >= 4

What is your conjecture? (We will revisit this later.)

My conjecture is that you can always decompose an even number >= 2 with 2 prime numbers numbers

## direct Proofs

Prove that if n is even, then n^2 is even.

Lets us show that for any even number that we will represent by n, n^2 is even.
Well, the definition of an even number says that it is a multiple of 2.
So that means that n = 2m for some integer m. 
We can substitute this into the expression we want to know about n ^ 2
to see that n ^ 2 = (2 m) ^2 = 4 (m ^ 2) = 2 (2 m ^2)
Since 2 (2 m ^2) is divisible by 2 it proves that n ^ 2 will always be even.
Q.E.D

-----

Prove that if n is odd, then n2 + 5n− 3 is also odd.

Putting it all together:
n2 + 5n − 3 = (4k2+4k+1) +(10k+5)−3
n^2 + 5n - 3 = (4k^2 + 4k + 1) + (10k + 5) - 3
n2+5n−3=(4k2+4k+1)+(10k+5)−3
Now combine like terms:
=4k 2+ 14k+3
= 4k^2 + 14k + 3
=4k2+14k+3
We can factor out a 2:
=2(2k2+7k+1)+1
= 2(2k^2 + 7k + 1) + 1
=2(2k2+7k+1)+1
This expression is clearly of the form
2m +1
2m + 1
2m+1, where
m =2k 2 + 7 k + 1
m = 2k^2 + 7k + 1
m=2k2+7k+1 is an integer. Therefore, the result is an odd number.
Q.E.D.

-----
Challenge: Invent your own false proposition and accompany it with a counterex-
ample

Every prime number is odd.

false there is a counter exemple which is 2 who is also a prime number because only divisible by itself and one.

## Pigeons and Correspondences

### 1

List all the subsets of {egg, duck, goose}. How many are there?
there are 2^3 subsets which is 8 subsets
{}
{egg}
{duck}
{goose}
{egg,duck}
{egg,goose}
{duck,goose}
{egg,duck,goose}
How many of them
contain egg? … duck? … goose?

Half of the subsets contains each of them.
4 contains egg, 4 contains duck and 4 contains goose

### 2

Consider a standard deck of cards with suits hearts (♡), spades (♠), clubs (♣), and
diamonds (♢), and values 2–10, jack, queen, king, and ace. 

How many cards must you deal out before being assured that two will have the same suit? 

At least 5 because there is 4 suits and if we follow the Pigeons hole princple there will be 4 hole and at the fifth card all holes will be already filled.

How many must you deal out before being assured that two will have the same value?

At least 14 because there is 8 numbers + 1 jack + 1 queen + 1 king + 1 ace which is 13.

and if you deal 13 cards of the same colors you will be forced to deal out another card of the another color at the 14th turned thus 2 card will have the same value.

### 3


Challenge: Invent your own counting question that can be answered using the pigeonhole principle.

You've got 4 teams of basketball, one team can play one other team once. 

How many games has to be played before being assured that a team has played two games.

The answer is 3 





