..  Titling
    ##++::==~~--''``

Transcript
==========

Welcome to Noseygrindstone. This is tundish. You're listening to my occasional
podcast on small-scale game development.

So, your hobby is making a computer game, and it's likely to take a while.
Which means that you will spend a good period of time referring to it as a
`work in progress`.

When someone asks, it's nice to be able to show them that you're getting
somewhere, and also very useful to have early feedback on your ideas. What we need
is a prototype which we can put in front of people and talk about.
 
Prototyping a game is not the same as designing it. And it's certainly not the
same as testing it. Testing is a massive topic which I'm sure I'm going to be
tackling at some point as the series continues. But today we're prototyping.

Prototyping is useful for taking the risk out of an idea.
To prove that the objectives you have set yourself are within your capability.
To see if a new mechanic works well in the context of the game. And the
prototype can be a talking point to help create interest or increase awareness
of your project.

Today I'm going to show you what an early game prototype might look like, and
I'll demonstrate a couple of the mechanics of a game I'm working on called
Addison Arches.

First we are going to look at how easy it can be to put an interactive prototype
together. In my case, I'm developing in the Python language, which has a
standard module for doing interactive text programs. I'm going to show you
where to find that module if you decide to use Python.

.. topic:: Python ``cmd`` module

    * Show Python documentation

    This module is enough by itself to give you the framework of a turn-based
    text-driven game.

    The prototype I'm about to show you extends the command loop a bit so that
    time can pass in the background.

    If you're curious as to the details I'm posting a link at the end to the
    source code I'm using today.

So, the game prototype we are about to see responds to text-based commands.
This is not a text parser game; there are just a few supported commands and
they take well-defined arguments.

Addison Arches will eventually become a web-based game. It's going to have
graphics and sound effects and music and everything else. I'm hoping to cover
those aspects in future episodes, to give you an idea of how the whole thing
builds up.

What I can show you today is two of the features of the game; trading and
crafting.

.. topic:: Trading: Buying from NPCs

    #. Visit Kinh Ship Bulk buy
    #. Bargain for shipments of tables
    #. Return home

So, I've written into the game the concept of `drama`. A drama is the thing
that's going on in any character's life at any particular moment. The NPCs
sense that drama and they respond to it. So when you decide you want to buy
the tables, that's when Jimmy comes up with his opening price.

.. topic:: Trading: Selling to NPCs

    #. Visit the Goldhawk
    #. Try to sell Barry the tables

I used to doubt whether crafting was a necessary part of adventure games and
RPGs. Again, this is a topic which deserves a whole episode by itself, but
it turns out that transformation of objects is an essential part of a simulated
economy. So if you want to have a functioning money system, you need a crafting
mechanism.

.. topic:: Crafting

    #. Discover the `split` command
    #. Split up the shipments of tables
    #. Go and sell Barry some pallets

So the game lets you break things to bits, but there's not yet any command to let
you follow a recipe to make something. I'm not actually sure whether I want making
stuff to be part of the gameplay. The NPCs will be the ones crafting things behind
the scenes.

Anyway, thanks for listening. Here are some links you might want to check out.
Remember, `you and me from the ashes we can build a web made of games`.
Catch you next time on Noseygrindstone!
