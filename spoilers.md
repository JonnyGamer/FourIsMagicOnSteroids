# Spoilers!
Are you sure you want to read this?

---
### MAJOR SPOILER IN LINK: What am I to do with these numbers?
I found an entry from [The On-Line Encyclopedia of Integer Sequences](https://oeis.org/) aka OEIS  
The sequence is [A058230](https://oeis.org/draft/A058230)  
The sequence is described as
> Numbers k such that the product of the lengths of the words in the name of k in American English is equal to k.

Unfortunately, this sequence only keeps track of numbers of type `a -> a`.
However, I am adding my 3 newly discovered terms to it.


---
### Small Spoiler: How many solutions have I found?

I have found 9 solutions of type `a -> a`.  
A tenth solution will be greater than `10^138`, if it exists.
	
Solutions for `a -> a`  
  4, 24, 84672, 1852200, 829785600, 20910597120, 92215733299200, 1239789303244800000, 887165996513213819259682435576627200000000
  
I have found 25 solutions of type `a -> b -> c -> ... -> a`  
I have only discovered 6 distinct loops.
The numbers below are the smallest such numbers.  
A 26th solution (or 7th loop) would be greater than `10^27`, if it exists

Solutions for `a -> b -> c -> ... -> a`  
 168, 175, 420, 441, 525, 588, 672, 840, 10584, 16128, 35280, 24192, 72576, 98784, 201600, 10668672, 22226400, 38896200, 1170993438720, 5576159232000, 85384938240000, 204923851776000, 1874561426506137600000, 2624385997108592640000, 22494737118073651200000

Here they are in array form:
- [4]
- [24]
- [168, 525, 672, 441, 420]
- [175, 588, 840]
- [10584, 16128, 35280, 24192, 72576, 98784, 201600]
- [84672]
- [1852200]
- [10668672, 38896200, 22226400]
- [829785600]
- [20910597120]
- [5576159232000, 1170993438720, 204923851776000, 85384938240000]
- [92215733299200]
- [1239789303244800000]
- [2624385997108592640000, 22494737118073651200000, 1874561426506137600000]
- [887165996513213819259682435576627200000000]


---
### Small Spoiler: Proofs

Adding proofs like, solutions of type `a -> a` will never be odd.
Coming soon.

- If `fourFour(n) = n` is true, and `n` has a prime factor greater than 100,  
then n must be greater than (10^1063333335) which is a billion digit number!  
Why?  
Because quattuorquinquagintatrecentilliquattuorquadragintaquadringentilliquattuorquadragintaquadringentillion is the first word with 101 characters.

---
### Other numbers with other features
fourFour(n) = n * 10^k (where k is an integer > 0)

- 1185408 -> 11854080
- 1580544 -> 15805440
- 1481760 -> 14817600
- 14224896 -> 142248960
- 248935680 -> 2489356800
- 5227649280 -> 52276492800
- 13115126513664 -> 131151265136640
- 195954154450774917120 -> 195954154450774917120000
- 195954154450774917120000 -> 1959541544507749171200000
- 30718588420985991231386419200 -> 30718588420985991231386419200000
- 44253198479272418967935275499520000 -> 442531984792724189679352754995200000000
- 3696524985471724246915343481569280000000 -> 369652498547172424691534348156928000000000
- 14831967027420913484439425535191285760000000 -> 148319670274209134844394255351912857600000000

Note that 195954154450774917120 -> 195954154450774917120000 -> 1959541544507749171200000  
Which is kind of mind boggling.

