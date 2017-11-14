---
title: Projects
layout: default
---

# Presentations

As part of this course, you will be asked to give a presentation on a
programming language outside those that you have seen previously
during your degree.

## Procedure


#### Selecting a topic

In groups of 4 (or at most 5), please choose a topic from the list
below. You can claim any topic by opening a pull request on
[the repository hosting this website](https://github.com/wouter-swierstra/2017-CPD),
where you add the name of all the team members to the topic. I'll try
to merge these promptly, but you may want to check any open pull
requests to be sure no other team has chosen this subject.

#### Presentation

The aim of the presentations is to provide students with a broad
overview of modern programming languages. In your presentation, you
should try to give an overview of the language and try to position it
relative to other languages you may know. This includes addressing
questions such as:

* Is the language statically typed? Dynamically typed? Untyped?
* Are effects, such as assigments, controlled?
* Is the language call by value? Call by name? Call by need? 
* Does it have reference semantics? Or value semantics?
* Does it have algebraic data types? Objects? Structs? Records?
* ...

But more generally, it's not so important to describe the exact syntax
of for-loops -- try to focus on what makes this language interesting
and different. I've tried to include some key questions for each
topic, but there may be many issues that I've overlooked.

You should aim to talk approximately 30-40 minutes, leaving time for
questions.

#### Slide templates

Please use the slide template here:

[https://github.com/wouter-swierstra/concepts-slide-template/](https://github.com/wouter-swierstra/concepts-slide-template/)

Note that this requires [pandoc](http://pandoc.org/) to create .pdf
slides using LaTeX beamer from Markdown. There are instructions in the
slides.md file about building your slides. This should hopefully be
fairly straightforward to set up.

## Topics

#### Idris

What are *dependent types*? How can these be used to prove properties
of your programs? 

Team: Xander, Kevin, Stefan, Luca, Zan

#### Rust

What kind of language is Rust? What is the problem with aliasing? How
does Rust's borrowing mechanism address this?

Team:
Tobias van Driessel, Floris Schild, Mats Veldhuizen, Tom Freijsen, Ruben Schenkhuizen

#### Elm

What kind of language is Elm? What is the Elm architecture? How does
it compare to existing languages for front-end development such as
Javascript? What kind of code does Elm generate?

Team: ???

#### Purescript

What kind of language is Purescript? How does it compare to existing
languages for front-end development such as Javascript? What are
algebraic effects and effect handlers? What are some of the key
features of the type system?

Team: ???

#### Swift

What kind of language is Swift? How does it compare to object oriented
languages such as Java or C#? Is it garbage collected? What are
protocols and how are they related to Haskell's type classes? What are
optional types and how are they related to 'null' values in other
object oriented languages?

Team: ???

#### Scala

How does Scala combine functional and object-oriented programming?
What are traits? What are case classes and pattern matching? How can
you interface with Java?

Team: ??? 

#### F\#

How does F# differ from other .NET languages such as C#? How can F#
interoperate with existing C# code? What features from Haskell that
you may have seen in Functional Programming does F# support? What
features, such as type providers, are unique to F#?

Team: Martijn Boom, Zino Onomiwo, Tim Zoet & Rik van Toor 

#### Scala and lightweight modular staging

What is Lightweight Modular Staging? How is it implemented in Scala?
How is it used for embedding compilers in Scala? What DSLs are
implemented in this style? How does it compare to other approaches to
implementing DSLs that we have seen?

Team: ??? 

#### OCaml

What is OCaml's module system? How is it different from Haskell's?
What are signatures and functors? What is the difference between
generative and applicative functors?

Team: ??? 

#### Template programming in C++

What are C++ templates? What are they good for? What are their
limitations? How are they different from some of the other
metaprogramming frameworks we have seen in this course?

Team: ??? 

#### Logic programming in Prolog

What is logic programming? How does the Prolog engine find solutions?
What is cut? And when should it be used?

Team: ??? 

#### Rascal

What is a language designers workbench? How is this approach to domain
specific languages different from embedded or stand-alone languages?
What are the relative merits of all these approaches?

Team: ???

#### Other (domain specific) languages

Feel free to suggest other topics, provided these languages are
suitably distinct from those listed above. 

