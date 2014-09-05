# AirStable - AirBnB For Horses

Yo!

You have a horse. You want to travel with your horse; but all the commercial
stables are absurdly expensive. Whatever do you do?!

Enter AirStable! AirStable lets people with extra stalls in their stable rent
stalls to horses on the go!

## Functional Requirements

1. Guest may register as a `User`
1. Guest may log in
1. `User` may create a Stall
1. `User` may see a list of available `Stall`s
1. `User` may create a pending `RentalRequest` for a `Stall`
1. `Stall` owner may see pending `RentalRequest`s
1. `RentalRequest`s requester may see pending `RentalRequest`s
1. `Stall` owner may deny `RentalRequest`s for their `Stall`
1. `Stall` owner may approve `RentalRequest`s for their `Stall`
1. `RentalRequest`s requester may see denied `RentalRequest`s
1. `Stall` renter may see allowed `RentalRequest`s


## STREEEETCH Features

1. `User` may include a message in the `RentalRequest`
1. `User` may include the date they want to use the `Stall` in the RentalRequest
1. `User` may search stalls based upon dates available
1. `User` may search stalls by location (Hint: use
   [graticule](https://github.com/collectiveidea/graticule)

## Learning Goals

1. Creating secure user registration and login
1. Building web applications with several related
   [models](https://github.com/codeunion/web-fundamentals/wiki/Glossary#model-mvc)
1. Sharing a
   [layout](https://github.com/codeunion/web-fundamentals/wiki/Glossary#layout-sinatra)
   across multiple views

## Imporant Philosophical Ramblings
**Good programs share the right data in the right form with the right people**.

Consider Uber: It combines your location, your ability to pay, and your desire to
travel a short distance and shares that with someone who is able to drive you.
It then shares that persons car information and distance so you can get in the
right car and be transported across the city; after which it transfers some data
from your credit card to their bank account.

From a technical perspective this isn't terribly complex. It has been solved in
the past with well-staffed call centers and radios. The reason Uber is "winning"
is because it automates away the cost of the call center and radios and lowers
the barriers to sharing the data to a few taps.

As a web developer, your job is to figure out what is the right data, what is
the right form fo rthat data, and who is the right people to have access to the
data.

## Getting Started
1. Fork and clone this repo
1. cd into it
1. Open `docs/mockups.png` file; Check that out!
1. Open `docs/model-relationship-diagram` file.
1. Build it. From scratch.

This project is an opportunity for you to start from the ground up and build an
application. There's no `Gemfile`. No `config.ru`. No `app.rb`. Just a series of
mockups and some requirements.

When you, inevitably, get stuck; review the commits I'm making against a similar
application,
[can-i-eat-here](https://github.com/codeunion/can-i-eat-here).

I am building can-i-eat-here step by step, annotating the code, linking to
relevant documentation, and providing commentary in the commit messages

can-i-eat-here is intended for reference. Do not copy paste. Typing helps you
remember and forces you to think about every single bit of syntax. **Every time
a programmer copy pastes a kitten cries. Don't make the kitten cry.**
