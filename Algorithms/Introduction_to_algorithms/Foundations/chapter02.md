## Insertion sort

We start with insertion sort, which is an efficient algorithm for sorting a small
number of elements. Insertion sort works the way many people sort a hand of
playing cards.

We start with an empty left hand and the cards face down on the
table. We then remove one card at a time from the table and insert it into the
correct position in the left hand. To find the correct position for a card, we compare
it with each of the cards already in the hand, from right to left.

> At all times, the cards held in the left hand are sorted, and these cards
> were originally the top cards of the pile on the table.

We state these properties of -- formally as a loop invariant:

At the start of each iteration of the for loop of lines 1–8, the subarray
A[1...j-1] consists of the elements originally in A[1...j-1], but in sorted order.

*We use loop invariants to help us understand why an algorithm is correct. We
must show three things about a loop invariant:*

* Initialization: It is true prior to the first iteration of the loop.
* Maintenance: If it is true before an iteration of the loop, it remains true before the next iteration.
* Termination: When the loop terminates, the invariant gives us a useful property that helps show that the algorithm is correct.

We will use these further to prove the algorithms

## Analyzing algorithms

Analyzing an algorithm has come to mean predicting the resources that the algorithm requires.

> Occasionally, resources such as memory, communication bandwidth, or computer
> hardware are of primary concern, but most often it is **computational time** that we want to measure.

