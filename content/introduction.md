Title: Episode 1 - The Naive Philospher asks "what is living"?
Date: 2019-07-30
Category: pseudophilosophy

#### In the beginning there was a question

So I was playing with my 3yo kid the other day, or at least was pretending to play 
while scrolling endlessly in some app in my phone, when something happened. 
He asked me a question -

_kid_: Why is this rabbit not taking care of itself?

_i_: What? Which rabbit?

_kid_: That toy rabbit over there. See, it has a spot on its eye!

_i_: Oh that! That's a toy, probably fell down.

_kid_: But it should have taken care of itself, right?

_i_: How can a toy take care of itself?

_kid_: Why not? We all should take care of ourselves, like you said!

_i_: Well, yeah! But a toy is not a living thing!

_kid_: Then what is a living thing? Are we living? Or are we toys too?

See, that's the kind of questions that goes _"TRRRIINGGGG!"_ in my head these days since that 
enlightened morning when I decided to take the **Introduction to Philosophy** course on Coursera. 
So I immediately launched a Plato style dialogue in my head with an imaginary kid.

------------
It's not always very easy or convenient to launch a Plato
in your head, because you have stuffs to do with real human beings - like shopping or picking up people from shopping - 
and failing to do so often causes real anxieties that may lead to even deeper
philosophical questions like "Why is living?"  
------------

Back to dialectics now.

#### Next there were some dialogues

_kid_: So what then, father, is living? How do I know that it is a toy
and not an object which is alive?

_i_: Indeed that is a great question! Come to think of it, the first thing
that comes to me - a property of living objects - is to be able to move.

_kid_: But father, my toy robot moves too. Does it mean it is alive?

_i_: No, of course not. It does not move out of its own volition. Rather it
moves because you make it so.

_kid_: So, moving on its own makes it alive?

_i_: Possibly.

_kid_: Then father, is it the movement of alive things make it alive or
just the ability to do so? Remember when my old grandfather was bed ridden
for several days and he couldn't move at all, not without help from others. 
Event if he wanted to move on his own, he could not. But he was still alive,
wasn't he?

_i_: Yes, you are right. However, it was only temporarily that he could not
move. His internal organs were functioning as is.

_kid_: So may be movement isn't a necessary property of aliveness? May be
something deeper - something to do with the organs of a being?

_i_: Perhaps you are right. Perhaps we should go much deeper. 

_kid_: How so?

_i_: We use reduction and go to that level where we talk in terms of the basic
elements of living objects - i.e. cells.

_kid_: But can we not go further still and say that everything is made of 
elementary particles and such? 

_i_: We could, but that will lead us no where I am afraid! Because then at the basic level
nothing is alive! Elementary particles which constitutes everything in the world - 
they cannot be termed alive, but it is only a specific configuration of them - forming molecules
and then higher complexities upto say a cellular system which can posses the properties
that we can define as life.

_kid_: What is so puzzling is the fact that at the lowest level we do not have
life but only after a certain complexity is achieved, can we term it as life! 
Therefore, should we say that complexity is what determines life?

_i_: Yes, but I think there must be some other fundamental properties too. A black hole is
an enormously complex system, yet it is not alive. Or think of our earth as planetary
whole - so complex, delicately balanced and non linear - yet not alive. Complexity
is only an emergent behaviour of these fundamental ideas. I think if
we stop at the level of cells, we can arrive at some definitions of aliveness.

_kid_: How so?

_i_: I think we can say that a system is alive if it has at least **N** cells which are
alive. Now, **N** is a number that can vary between species or between 
individuals of that species as well. But for a particular object, we can define **N**
in terms of some rules that can be determined biologically.

_kid_: Interesting, but is it not a recursive definition? We define **Alive(System)** in terms 
of **Count({Alive(cell) | cell ∈ System})**. Then how do we determine the boundary 
condition?

_i_: Perhaps we need to separate the criterion for aliveness of cell from
that of system. 

_kid_: Or make **Alive** polymorphic!

_i_: Yes! Excellent! Lets do that. We define a living cell as:

----------------
**Alive(cell: Cell): Boolean** = 

    If
        * cell has a set of purposes AND
        * cell is interested in survival of the self AND
        * cell carries a program for constructing the system it belongs to AND
        * cell one or more running processes which directly or indirectly satisfy the above
-----------------

All of above must be in place to call a cell alive.

_kid_: Ok. So an alive system becomes something like:

-------------

**Alive(system: System): Boolean** = 

    Let alive_cells = Count({Alive(cell) | cell ∈ system})
        N = MinAliveCellsCount(system, System) // Minimum alive cells in the system to keep it alive
    If
        * alive_cells >= N
-------------

Thus we come to the conclusion of how to determine an alive system!

_i_: Right! And with this you can tell whether the toy rabbit is alive or not.


#### In the end there was a big cliff hanger

As I stop the Plato process in my head and relax on my couch, a nagging sensation
makes its way into my mind. I feel our philosophical argument, however satisfying it
appears to me, lacks something - something very fundamental. And then it hits me!


