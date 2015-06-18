..  Titling
    ##++::==~~--''``

Transcript
==========

Welcome to the Noseygrindstone!

This is a podcast on various aspects of game development. Very small-scale
game development by individuals.

If your hobby is making a computer game, it's likely to be taking a while.
Which means that you will spend a good period of time referring to it as a
`work in progress`.

When people ask, it's important to show them that you're getting somewhere,
and also very useful to have early feedback on your ideas. What's needed
then, is a prototype which you can show to people and talk about.
 
Prototyping a game is not the same as designing it. And it's certainly not the
same as testing it. Testing is a massive topic which I'm sure I'm going to have
to tackle at some point if this series continues.

Prototyping is useful for taking the risk out of an idea.
To prove that the objectives you have set yourself are within your capability.
To see if a new mechanic works well in the context of the game. And the
prototype can be a talking point to help create interest or increase awareness
of your project.

Today I'm going to show you what an early game prototype might look like, and
I'll demonstrate a couple of the mechanics of a game I'm working on called
Addison Arches.

First though, we'll look at how easy it is to put an interactive prototype
together. Now, in my case, I'm developing in the Python language, which has a
standard module for doing interactive text programs.

.. topic:: Python ``cmd`` module

    * Show Python documentation

    This module is enough by itself to give you the framework of a turn-based
    text-driven game.

    The prototype I'm about to show you extends the command loop a bit so that
    time can pass in the background.

    If you're curious as to the details I'll post a link at the end to the
    source code I'm using today.

So, the game prototype we are about to see responds to text-based commands.
This is not a text parser game; the commands take well-defined arguments, so
it's more akin to filling out the fields of a web form, only on a command line.
In fact, Addison Arches will eventually become a web-based game, with graphics
and sound effects and music and everything else.

What I can show you today is two of the features of the game; trading and
crafting.

.. topic:: Trading: Buying from NPCs

    #. Visit Kinh Ship Bulk buy
    #. Bargain for shipments of tables
    #. Return home

So, I've written into the game the concept of `drama`. A drama is the thing
that's going on in any character's life at any particular moment. The NPCs
sense that drama and they respond to it. So when you decide you want to buy
the tables, that's when Jimmy pipes up with his price.

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

The game lets you break things to bits, but there's not yet any command to let
you follow a recipe to make something yet.

Anyway, thanks for listening to this podcast. I'm going to leave you with some
useful links.

Look forward to the next time on Noseygrindstone!
